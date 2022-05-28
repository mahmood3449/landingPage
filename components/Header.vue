<template>
  <header class="header">
      <div class="header__date"> <i class="fa-solid fa-calendar-days"></i> امروز : <span class="header__date-day"> {{ day}}</span> <span class="header__date-mounth">{{ mounth }}</span> <span class="header__date-year">{{ year }}</span> ساعت : <span class="header__date-time">{{ time }}</span><span v-if="err">خطایی رخ داده است</span></div> 
  </header>
</template>

<script>
export default {
    name: 'HeaderPage' ,
    data(){
        return {
            day: null ,
            mounth: null ,
            year: null ,
            time: null , 
            err: false ,
        } 
    } ,
    fetch(){
        this.$axios.
        $get('https://api.keybit.ir/time/').then((data)=>{
            this.day = data.date.day.number.fa;
            this.mounth = data.date.month.name;
            this.year = data.date.year.number.fa;
            this.time = data.time24.full.fa;

        }).catch((e)=>{
            if(e.message === 'Network Error'){
                this.err = true;
            };
        })
    }
}
</script>

<style lang="scss" scoped>
@import '@/assets/color/color.scss';

    .header{
        background: $blue;
        // border: 1px solid black;
        &__date{
            width: 60%;
            color: white;
            padding: 1rem 2rem;
            // border: 1px solid green;
            i{
                padding-left: 0.5rem;
            }
        }
    }

</style>