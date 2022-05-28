<template>
  <nav class="nav">
      <div class="nav__right">اسم شرکت</div>
      <div class="nav__left">
          <div class="nav__left-menu">
              <div class="nav__left-menu-home active">خانه</div>
              <div class="nav__left-menu-weblog">وبلاگ</div>
              <div class="nav__left-menu-qa">سوالات متداول</div>
              <div class="nav__left-menu-contact">تماس با ما</div>
          </div>
          <div class="nav__left-pannel">
              <button class="nav__left-pannel-btn">پنل اعضا</button>
          </div>
      </div>
  </nav>
</template>

<script>
export default {
    name: 'NavPage'
}
</script>

<style lang="scss" scoped>
@import '@/assets/color/color.scss';
%btn{
    width: 90%;
    padding: 0.6rem 0;
    border-radius: 20px;
    border: none;
    outline: none;
    background: linear-gradient(1deg,#34d78a 0%,#78e013 100%);
    color: white;
    font-weight: bolder;
}
    .nav{
        display: none;
        &__right{
            width: 50%;
            padding: 1rem 2rem;
            border: 1px solid black;
        }
        &__left{
            width: 50%;
            text-align: left;
            padding: 0 2rem;
            display: flex;
            border: 1px solid green;
            &-menu{
                width: 80%;
                padding: 0.5rem;
                display: flex;
                div{
                    width: 25%;
                    padding: 0.5rem 0;
                    text-align: center;
                }
            }
            &-pannel{
                width: 20%;
                padding: 0.5rem;
                &-btn{
                    @extend %btn;
                    box-shadow: 1px 1px 20px $colorbtn;
                    &:hover{
                        background: linear-gradient(90deg,#080808 0%,#919191 100%);
                        box-shadow: none;
                    }
                }
            }
        }
    }
    .active{
        color: $colorbtn;
    }
</style>