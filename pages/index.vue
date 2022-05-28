<template>
  <section class="home">
<div class="home__box1">
  <nav class="home__box1-nav">
    <div class="home__box1-nav-right">اسم شرکت</div>
      <div class="home__box1-nav-left">
          <div class="home__box1-nav-left-menu">
              <div class="home__box1-nav-left-menu-home active">خانه</div>
              <div class="home__box1-nav-left-menu-weblog">وبلاگ</div>
              <div class="home__box1-nav-left-menu-qa">سوالات متداول</div>
              <div class="home__box1-nav-left-menu-contact">تماس با ما</div>
          </div>
          <div class="home__box1-nav-left-pannel">
              <button class="home__box1-nav-left-pannel-btn">پنل اعضا</button>
          </div>
      </div>
  </nav>
  <div class="home__box1-content">
    <div class="home__box1-content-right">
      <div class="home__box1-content-right-wellcome" :class="{box1right:box1right}">
        <p>آدرس سایت شرکت</p>
        <h1>به شرکت فلان خوش آمدید!</h1>
      </div>
      <div class="home__box1-content-right-Introduction" :class="{box1bottom:box1bottom}">
        <p>شرکت فلان ارائه دهنده جدیدترین سرویس ها</p>
      </div>
      <div class="home__box1-content-right-panell" :class="{box1bottom:box1bottom}">
        <button><i class="fa-solid fa-arrow-right-to-bracket"></i> ورود به پنل اعضا</button>
      </div>
    </div>
    <div class="home__box1-content-left">
      <div class="home__box1-content-left-logo" :class="{box1bottom:box1bottom}">لوگو شرکت</div>
    </div>
  </div>
</div>
<div class="home__box2">
  <div class="home__box2-content">
    <div class="home__box2-content-right" :class="{box1right:box2right}">
      <div class="home__box2-content-right-top">
      <p>پنل مدیریت اعضا</p>
      <h1>آنچه نیاز دارید در یک جا!</h1>
      </div>
      <div class="home__box2-content-right-bottom">
        <p>ما برای شما پنل ویژه با تمامی امکانات مورد نیازتان تدارک دیده ایم!</p>
        <div class="home__box2-content-right-bottom-btn">
        <button>ورود به پنل</button>
        </div>
      </div>
    </div>
    <div class="home__box2-content-left" :class="{box1bottom:box2bottom}">
      <div class="home__box2-content-left-right">
        <div class="home__box2-content-left-right-boxtop">
          <div class="home__box2-content-left-right-boxtop-img">
            <i class="fa-solid fa-display"></i>
          </div>
          <div class="home__box2-content-left-right-boxtop-title">
            قابل استفاده در همه جا
          </div>
          <div class="home__box2-content-left-right-boxtop-des">
            با هر سیستمی و در هرجایی در یک آن به پنل خود دسترسی پیدا کنید!
          </div>
        </div>
        <div class="home__box2-content-left-right-boxbottom">
          <div class="home__box2-content-left-right-boxbottom-img">
            <i class="fa-solid fa-shield"></i>
          </div>
          <div class="home__box2-content-left-right-boxbottom-title">
            امنیت کامل
          </div>
          <div class="home__box2-content-left-right-boxbottom-des">
            اطلاعات شما بصورت کاملا امن نگهداری میشوند!
          </div>
        </div>
      </div>
      <div class="home__box2-content-left-left">
        <div class="home__box2-content-left-left-boxtop">
          <div class="home__box2-content-left-left-boxtop-img">
            <i class="fa-solid fa-baseball"></i>
          </div>
          <div class="home__box2-content-left-left-boxtop-title">
            پشتیبانی 24/7
          </div>
          <div class="home__box2-content-left-left-boxtop-des">
            در صورت وجود هرگونه سوال یا ابهام میتوانید از بخش پشتیبانی پنل با ما در ارتباط باشید!
          </div>
        </div>
        <div class="home__box2-content-left-left-boxbottom">
          <div class="home__box2-content-left-left-boxbottom-img">
            <i class="fa-solid fa-gear"></i>
          </div>
          <div class="home__box2-content-left-left-boxbottom-title">
            مدیریت همه چیز
          </div>
          <div class="home__box2-content-left-left-boxbottom-des">
            در پنل خود میتوانید تمام انچه نیاز دارید مدیریت و ویرایش کنید!
          </div>
        </div>
      </div>
    </div>
  </div>
</div>
  <div class="home__box3" >
    <div class="home__box3-top">
      <svg id="wave" style="transform:rotate(0deg); transition: 0.3s" viewBox="0 0 1440 190" version="1.1" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0"><stop stop-color="rgba(136.138, 190.578, 255, 0.34)" offset="0%"></stop><stop stop-color="rgba(0, 220.448, 255, 0.29)" offset="100%"></stop></linearGradient></defs>
      <path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,0L26.7,12.5C53.3,25,107,50,160,57.5C213.3,65,267,55,320,55C373.3,55,427,65,480,57.5C533.3,50,587,25,640,25C693.3,25,747,50,800,52.5C853.3,55,907,35,960,35C1013.3,35,1067,55,1120,52.5C1173.3,50,1227,25,1280,35C1333.3,45,1387,90,1440,105C1493.3,120,1547,105,1600,90C1653.3,75,1707,60,1760,55C1813.3,50,1867,55,1920,55C1973.3,55,2027,50,2080,55C2133.3,60,2187,75,2240,87.5C2293.3,100,2347,110,2400,102.5C2453.3,95,2507,70,2560,57.5C2613.3,45,2667,45,2720,47.5C2773.3,50,2827,55,2880,67.5C2933.3,80,2987,100,3040,107.5C3093.3,115,3147,110,3200,95C3253.3,80,3307,55,3360,40C3413.3,25,3467,20,3520,17.5C3573.3,15,3627,15,3680,25C3733.3,35,3787,55,3813,65L3840,75L3840,150L3813.3,150C3786.7,150,3733,150,3680,150C3626.7,150,3573,150,3520,150C3466.7,150,3413,150,3360,150C3306.7,150,3253,150,3200,150C3146.7,150,3093,150,3040,150C2986.7,150,2933,150,2880,150C2826.7,150,2773,150,2720,150C2666.7,150,2613,150,2560,150C2506.7,150,2453,150,2400,150C2346.7,150,2293,150,2240,150C2186.7,150,2133,150,2080,150C2026.7,150,1973,150,1920,150C1866.7,150,1813,150,1760,150C1706.7,150,1653,150,1600,150C1546.7,150,1493,150,1440,150C1386.7,150,1333,150,1280,150C1226.7,150,1173,150,1120,150C1066.7,150,1013,150,960,150C906.7,150,853,150,800,150C746.7,150,693,150,640,150C586.7,150,533,150,480,150C426.7,150,373,150,320,150C266.7,150,213,150,160,150C106.7,150,53,150,27,150L0,150Z"></path>
      <path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,105L26.7,92.5C53.3,80,107,55,160,50C213.3,45,267,60,320,70C373.3,80,427,85,480,95C533.3,105,587,120,640,112.5C693.3,105,747,75,800,55C853.3,35,907,25,960,17.5C1013.3,10,1067,5,1120,2.5C1173.3,0,1227,0,1280,10C1333.3,20,1387,40,1440,62.5C1493.3,85,1547,110,1600,112.5C1653.3,115,1707,95,1760,75C1813.3,55,1867,35,1920,40C1973.3,45,2027,75,2080,87.5C2133.3,100,2187,95,2240,90C2293.3,85,2347,80,2400,85C2453.3,90,2507,105,2560,100C2613.3,95,2667,70,2720,52.5C2773.3,35,2827,25,2880,27.5C2933.3,30,2987,45,3040,50C3093.3,55,3147,50,3200,45C3253.3,40,3307,35,3360,50C3413.3,65,3467,100,3520,115C3573.3,130,3627,125,3680,120C3733.3,115,3787,110,3813,107.5L3840,105L3840,150L3813.3,150C3786.7,150,3733,150,3680,150C3626.7,150,3573,150,3520,150C3466.7,150,3413,150,3360,150C3306.7,150,3253,150,3200,150C3146.7,150,3093,150,3040,150C2986.7,150,2933,150,2880,150C2826.7,150,2773,150,2720,150C2666.7,150,2613,150,2560,150C2506.7,150,2453,150,2400,150C2346.7,150,2293,150,2240,150C2186.7,150,2133,150,2080,150C2026.7,150,1973,150,1920,150C1866.7,150,1813,150,1760,150C1706.7,150,1653,150,1600,150C1546.7,150,1493,150,1440,150C1386.7,150,1333,150,1280,150C1226.7,150,1173,150,1120,150C1066.7,150,1013,150,960,150C906.7,150,853,150,800,150C746.7,150,693,150,640,150C586.7,150,533,150,480,150C426.7,150,373,150,320,150C266.7,150,213,150,160,150C106.7,150,53,150,27,150L0,150Z"></path>
      <path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,0L30,12.5C60,25,120,50,180,57.5C240,65,300,55,360,55C420,55,480,65,540,57.5C600,50,660,25,720,25C780,25,840,50,900,52.5C960,55,1020,35,1080,35C1140,35,1200,55,1260,52.5C1320,50,1380,25,1440,35C1500,45,1560,90,1620,105C1680,120,1740,105,1800,90C1860,75,1920,60,1980,55C2040,50,2100,55,2160,55C2220,55,2280,50,2340,55C2400,60,2460,75,2520,87.5C2580,100,2640,110,2700,102.5C2760,95,2820,70,2880,57.5C2940,45,3000,45,3060,47.5C3120,50,3180,55,3240,67.5C3300,80,3360,100,3420,107.5C3480,115,3540,110,3600,95C3660,80,3720,55,3780,40C3840,25,3900,20,3960,17.5C4020,15,4080,15,4140,25C4200,35,4260,55,4290,65L4320,75L4320,150L4290,150C4260,150,4200,150,4140,150C4080,150,4020,150,3960,150C3900,150,3840,150,3780,150C3720,150,3660,150,3600,150C3540,150,3480,150,3420,150C3360,150,3300,150,3240,150C3180,150,3120,150,3060,150C3000,150,2940,150,2880,150C2820,150,2760,150,2700,150C2640,150,2580,150,2520,150C2460,150,2400,150,2340,150C2280,150,2220,150,2160,150C2100,150,2040,150,1980,150C1920,150,1860,150,1800,150C1740,150,1680,150,1620,150C1560,150,1500,150,1440,150C1380,150,1320,150,1260,150C1200,150,1140,150,1080,150C1020,150,960,150,900,150C840,150,780,150,720,150C660,150,600,150,540,150C480,150,420,150,360,150C300,150,240,150,180,150C120,150,60,150,30,150L0,150Z"></path>
      </svg>
    </div>
    <div class="home__box3-title">
      <p class="home__box3-title-top" :class="{box1right:box3right}">کانال ما</p>
      <h1 :class="{box1right:box3right}">در کانال رسمی ما عضو شوید!</h1>
      <p class="home__box3-title-bottom">با عضویت در کانال ما از هیچ رویدادی بی خبر نمی مانید!</p>
    </div>
    <div class="home__box3-btn">
      <button :class="{box1bottom:box3bottom}"><i class="fa-brands fa-telegram"></i> عضویت</button>
    </div>
  </div>
  <div class="home__box4">
    <div class="home__box4-cunter">
      <div class="home__box4-cunter-box1">
        <p class="title">{{consent}}%</p>
        <p class="des">رضایت</p>
      </div>
      <div class="home__box4-cunter-box2">
         <p class="title">{{ option }}</p>
        <p class="des">خدمت متنوع</p>
      </div>
      <div class="home__box4-cunter-box3">
         <p class="title">{{ Customer }}</p>
        <p class="des">مشتری فعال</p>
      </div>
      <div class="home__box4-cunter-box4">
         <p class="title">{{ Experience }}</p>
        <p class="des">تجربه</p>
      </div>
    </div>
  </div>
  <div class="home__box5">
    <div class="home__box5-top">
      <p class="title" :class="{box1bottom:box5bottom}">پلن های قیمت گذاری</p>
      <h1 :class="{box1bottom:box5bottom}">قیمت های استثنایی!</h1>
      <p class="des">علاوه بر طرح های زیر, میتوانید بصورت شارژی (آزاد) نیز از خدمات ما استفاده کنید!</p>
    </div>
    <div class="home__box5-bottom">
      <div class="home__box5-bottom-box1" :class="{box1bottom:box5box1bottom}">
        <div class="home__box5-bottom-box1-img"><div><i class="fa-solid fa-box-archive"></i></div></div>
        <div class="home__box5-bottom-box1-title">پلن برنزی</div>
        <div class="home__box5-bottom-box1-option">
          <p><i class="fa-solid fa-check"></i> تمامی وبسرویس ها</p>
          <p><i class="fa-solid fa-check"></i> یکماهه تا سه ماهه</p>
          <p><i class="fa-solid fa-check"></i> تا 10 درصد تخفیف</p>
          <p><i class="fa-solid fa-check"></i> تحویل فوری بعد از پرداخت</p>
        </div>
        <div class="home__box5-bottom-box1-des">1 هزار درخواست /روزانه</div>
        <div class="home__box5-bottom-box1-btn">
          <button>سفارش دهید</button>
        </div>
      </div>
      <div class="home__box5-bottom-box2" :class="{box1bottom:box5box2bottom}">
        <div class="home__box5-bottom-box2-img"><div><i class="fa-solid fa-box-archive"></i></div></div>
        <div class="home__box5-bottom-box2-title">پلن نقره ای</div>
        <div class="home__box5-bottom-box2-option">
          <p><i class="fa-solid fa-check"></i> تمامی وبسرویس ها</p>
          <p><i class="fa-solid fa-check"></i> یکماهه تا سه ماهه</p>
          <p><i class="fa-solid fa-check"></i> تا 10 درصد تخفیف</p>
          <p><i class="fa-solid fa-check"></i> تحویل فوری بعد از پرداخت</p>
        </div>
        <div class="home__box5-bottom-box2-des">1 هزار درخواست /روزانه</div>
        <div class="home__box5-bottom-box2-btn">
          <button>سفارش دهید</button>
        </div>
      </div>
      <div class="home__box5-bottom-box3" :class="{box1bottom:box5box3bottom}">
        <div class="home__box5-bottom-box3-img"><div><i class="fa-solid fa-box-archive"></i></div></div>
        <div class="home__box5-bottom-box3-title">پلن طلایی</div>
        <div class="home__box5-bottom-box3-option">
          <p><i class="fa-solid fa-check"></i> تمامی وبسرویس ها</p>
          <p><i class="fa-solid fa-check"></i> یکماهه تا سه ماهه</p>
          <p><i class="fa-solid fa-check"></i> تا 10 درصد تخفیف</p>
          <p><i class="fa-solid fa-check"></i> تحویل فوری بعد از پرداخت</p>
        </div>
        <div class="home__box5-bottom-box3-des">1 هزار درخواست /روزانه</div>
        <div class="home__box5-bottom-box3-btn">
          <button>سفارش دهید</button>
        </div>
      </div>
      <div class="home__box5-bottom-box4" :class="{box1bottom:box5box4bottom}">
        <div class="home__box5-bottom-box4-img"><div><i class="fa-solid fa-box-archive"></i></div></div>
        <div class="home__box5-bottom-box4-title">پلن الماسی</div>
        <div class="home__box5-bottom-box4-option">
          <p><i class="fa-solid fa-check"></i> تمامی وبسرویس ها</p>
          <p><i class="fa-solid fa-check"></i> یکماهه تا سه ماهه</p>
          <p><i class="fa-solid fa-check"></i> تا 10 درصد تخفیف</p>
          <p><i class="fa-solid fa-check"></i> تحویل فوری بعد از پرداخت</p>
        </div>
        <div class="home__box5-bottom-box4-des">1 هزار درخواست /روزانه</div>
        <div class="home__box5-bottom-box4-btn">
          <button>سفارش دهید</button>
        </div>
      </div>
    </div>
  </div>
  <div class="home__box6">
    <svg id="wave" style="transform:rotate(0deg); transition: 0.3s" viewBox="0 0 1440 490" version="1.1" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="sw-gradient-0" x1="0" x2="0" y1="1" y2="0"><stop stop-color="rgba(252.24, 252.608, 253.043, 1)" offset="0%"></stop><stop stop-color="rgba(225.397, 244.972, 255, 1)" offset="100%"></stop></linearGradient></defs><path style="transform:translate(0, 0px); opacity:1" fill="url(#sw-gradient-0)" d="M0,392L120,326.7C240,261,480,131,720,65.3C960,0,1200,0,1440,57.2C1680,114,1920,229,2160,236.8C2400,245,2640,147,2880,114.3C3120,82,3360,114,3600,147C3840,180,4080,212,4320,196C4560,180,4800,114,5040,138.8C5280,163,5520,278,5760,334.8C6000,392,6240,392,6480,359.3C6720,327,6960,261,7200,204.2C7440,147,7680,98,7920,130.7C8160,163,8400,278,8640,318.5C8880,359,9120,327,9360,326.7C9600,327,9840,359,10080,367.5C10320,376,10560,359,10800,359.3C11040,359,11280,376,11520,326.7C11760,278,12000,163,12240,122.5C12480,82,12720,114,12960,114.3C13200,114,13440,82,13680,57.2C13920,33,14160,16,14400,65.3C14640,114,14880,229,15120,294C15360,359,15600,376,15840,392C16080,408,16320,425,16560,383.8C16800,343,17040,245,17160,196L17280,147L17280,490L17160,490C17040,490,16800,490,16560,490C16320,490,16080,490,15840,490C15600,490,15360,490,15120,490C14880,490,14640,490,14400,490C14160,490,13920,490,13680,490C13440,490,13200,490,12960,490C12720,490,12480,490,12240,490C12000,490,11760,490,11520,490C11280,490,11040,490,10800,490C10560,490,10320,490,10080,490C9840,490,9600,490,9360,490C9120,490,8880,490,8640,490C8400,490,8160,490,7920,490C7680,490,7440,490,7200,490C6960,490,6720,490,6480,490C6240,490,6000,490,5760,490C5520,490,5280,490,5040,490C4800,490,4560,490,4320,490C4080,490,3840,490,3600,490C3360,490,3120,490,2880,490C2640,490,2400,490,2160,490C1920,490,1680,490,1440,490C1200,490,960,490,720,490C480,490,240,490,120,490L0,490Z"></path></svg>
    <div class="home__box6-register">
      <div class="home__box6-register-content" :class="{box1bottom:box6bottom}">
      <p class="title">ثبت نام</p>
      <h1>همین الان شروع کنید</h1>
      <p class="des">نقطه عطف کسب و کار شما همینجاست!</p>
      <div class="home__box6-register-content-btn">
        <button><i class="fa-solid fa-arrow-right-to-bracket"></i> الان ثبت نام کنید</button>
      </div>
      </div>

    </div>
  </div>
  </section>
</template>

<script>
export default {
  name: 'IndexPage',
  data(){
    return{
      box1bottom: false ,
      box2bottom: false ,
      box3bottom: false ,
      box5bottom: false ,
      box5box1bottom: false ,
      box5box2bottom: false ,
      box5box3bottom: false ,
      box5box4bottom: false ,
      box6bottom: false ,
      box1right: false ,
      box2right: false ,
      box3right: false ,
      cunter: false ,
      consent : 30 ,
      option: 30 ,
      Customer : 49 ,
      Experience: 44
    }
  } ,
  mounted(){
    setTimeout(() => {
      this.box1bottom = true;
    }, 500);
    window.addEventListener('scroll' , this.changeTags);
  },
  methods:{
    changeTags(e){
      // console.log(document.documentElement.scrollTop);
      if(document.documentElement.scrollTop > 70){
        this.box1right = true;
      }
      if(document.documentElement.scrollTop > 400){
        this.box2bottom = true;
        setTimeout(() => {
          this.box2right = true;
        }, 1000);
      }
      if(document.documentElement.scrollTop > 1300){
        this.box3bottom = true;
        this.box3right = true;
      }
      if(document.documentElement.scrollTop > 1600){
          this.cunter = true;
      }
      if(document.documentElement.scrollTop > 1900){
          this.box5bottom = true;
      }
      if(document.documentElement.scrollTop > 2100){
          this.box5box1bottom = true;
          setTimeout(() => {
            this.box5box2bottom = true;
          }, 500);
          setTimeout(() => {
            this.box5box3bottom = true;
          }, 700);
          setTimeout(() => {
            this.box5box4bottom = true;
          }, 900);
      }
      if(document.documentElement.scrollTop > 2600){
          this.box6bottom = true;
      }
    }
  } , 
  watch:{
    cunter(){
     const reapet = setInterval(() => {
             this.consent++;
              this.option++;
              this.Customer++;
              this.Experience++;
            }, 20);
            setTimeout(() => {
              if(this.option >= 10){
                clearInterval(reapet);
              }
            }, 1000);
    }
  }
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
.home{
  width: 100%;
  &__box1{
    width: 100%;
    height: 100vh;
    padding-bottom: 11rem;
    background: url('@/assets/img/box1.png');
    background-position: bottom center;
    background-repeat: no-repeat;
    // border: 1px solid black;
    &-nav{
      border-top: 1px solid $bordercolor;
      width: 95%;
      display: flex;
      margin: auto;
      color: white; 
      &-right{
            width: 50%;
            padding: 1rem 0;
            // border: 1px solid black;
        }
        &-left{
            width: 50%;
            text-align: left;
            padding: 1rem 0rem;
            display: flex;
            // border: 1px solid green;
            &-menu{
              // border: 1px solid green;
                width: 80%;
                padding: 0.5rem;
                display: flex;
                div{
                    width: 25%;
                    padding: 0.5rem 0;
                    text-align: center;
                    transition: 250ms;
                    &:hover{
                      color: $colorbtn;
                      cursor: pointer;
                    }
                }
            }
            &-pannel{
                width: 20%;
                padding: 0.7rem;
                // border: 1px solid green;
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
    &-content{
      width: 95%;
      height: 80vh;
      margin: auto;
      display: flex;
      overflow: hidden;
      color: white;
      // border: 1px solid black;
      &-right{
        transition: 250ms;
        width: 50%;
        // border: 1px solid black;
        &-wellcome{
          transform: translateX(500px); //////
          transition: 1s;
          height: 40vh;
          display: flex;
          flex-direction: column;
          justify-content: end;
          // border: 1px solid black;
          p{
            font-size: 0.8rem;
          }
          h1{
            font-size: 2.5rem;
          }
        }
        &-Introduction{
          transform: translateY(350px); ////
          transition: 1s;
          height: 20vh;
          display: flex;
          flex-direction: column;
          justify-content: center;
          // border: 1px solid black;
          // padding: 1rem 0;
        }
        &-panell{
          transform: translateY(350px);
          transition: 1s;
          height: 20vh;
          display: flex;
          flex-direction: column;
          justify-content: center;
          // border: 1px solid black;
          button{
            @extend %btn;
            width: 30%;
            &:hover{
              background: linear-gradient(90deg,#080808 0%,#919191 100%);
            }
          }
        }
      }
      &-left{
        width: 50%;
        // border: 1px solid black;
        &-logo{
          transform: translateY(350px);
          transition: 1s;
          width: 70%;
          height: 70vh;
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          overflow: hidden;
          font-size: 5rem;
          // border: 1px solid black;
        }
      }
    }
  }
  &__box2{
    width: 100%;
    overflow: hidden;
    // border: 1px solid black;
    &-content{
      width: 90%;
      height: 100vh;
      margin: auto;
      display: grid;
      grid-template-columns: 1fr 2fr;
      // border: 1px solid red;
      &-right{
        transform: translateX(500px); //////
        transition: 1s;
        overflow: hidden;
        // border: 1px solid black;
        &-top{
          p{
            // border: 1px solid black;
            padding: 1rem 0;
            color: $colorbtn;
          }
          h1{
            // border: 1px solid black;
            padding: 1rem;
          }
        }
        &-bottom{
          // border: 1px solid black;
          p{
            // border: 1px solid black;
            width: 80%;
            padding: 1rem 0;
          }
          &-btn{
            // border: 1px solid black;
            padding: 1rem 0.5rem;
            button{
              @extend %btn;
              width: 30%;
              box-shadow: 1px 1px 11px $colorbtn;
              &:hover{
                background: linear-gradient(90deg,#080808 0%,#919191 100%);
                box-shadow: none;
              }
            }
          }
        }
      }
      &-left{
        transform: translateY(650px); ////
          transition: 1s;
        overflow: hidden;
        display: grid;
        grid-template-columns: 1fr 1fr;
        // border: 1px solid black;
        &-right{
          display: flex;
          flex-direction: column;
          justify-content: start;
          align-items: center;
          // border: 1px solid black;
          &-boxtop{
            margin-bottom: 2rem;
            &-img{
              color: $colorbtn;
              background: #a6fbd363;
            }
            &-title{
              color: $colorbtn;
            }
          }
          &-boxbottom{
              &-img{
              color: #9572FB;
              background: #c0d9f763;
            }
            &-title{
              color: #9572FB;
            }
            }
          &-boxtop , &-boxbottom{
            width: 90%;
            height: 40vh;
            border-radius: 5px;
            border: 1px solid $bordercolor;
            box-shadow: 1px 20px 30px rgba(190, 190, 190, 0.212);
            &-img{
              display: flex;
              justify-content: center;
              align-items: center;
              width: 30%;
              height: 40%;
              border-radius: 50%;
              margin: 20px auto;
              // border: 1px solid black;
              i{
                font-size: 2rem;
              }
            }
            &-title{
              // border: 1px solid black;
              padding: 0.5rem 0;
              text-align: center;
              font-weight: bold;
            }
            &-des{
              // border: 1px solid black;
              padding: 1rem 0;
              padding: 0.5rem;
              text-align: center;
            }
          }
        }
          // border: 1px solid black;
          &-left{
          display: flex;
          flex-direction: column;
          justify-content: space-around;
          align-items: center;
          // border: 1px solid green;
          &-boxtop , &-boxbottom{
            width: 90%;
            height: 40vh;
            border-radius: 5px;
            border: 1px solid $bordercolor;
            box-shadow: 1px 20px 30px rgba(190, 190, 190, 0.212);
            &-img{
              display: flex;
              justify-content: center;
              align-items: center;
              width: 30%;
              height: 40%;
              border-radius: 50%;
              margin: 20px auto;
              // border: 1px solid black;
              i{
                font-size: 2rem;
              }
            }
            &-title{
              // border: 1px solid black;
              padding: 0.5rem 0;
              text-align: center;
              font-weight: bold;
            }
            &-des{
              // border: 1px solid black;
              padding: 0.5rem 0;
              padding: 1rem;
              text-align: center;
            }
          }
          &-boxtop{
            &-img{
              color: orange;
              background: rgb(255, 228, 177);
            }
            &-title{
              color: orange;
            }
          }
          &-boxbottom{
            &-img{
              color: rgb(58, 58, 255);
              background: rgb(198, 198, 255);
            }
            &-title{
              color: rgb(58, 58, 255);
            }
          }
        }
      }
    }
  }
  &__box3{
    width: 100%;
    height: 85vh;
    // border: 1px solid black;
    &-top{
      width: 100%;
      height: 15vh;
      // border: 1px solid black;
    }
    &-title{
      overflow: hidden;
      text-align: center;
      // border: 1px solid black;
      background: linear-gradient(360deg , #80C4FD , white);
      height: 40vh;
      &-top{
        transform: translateX(800px); //////
        transition: 1s;
        // border: 1px solid black;
        width: 40%;
        padding: 4rem 0 0;
        margin: auto;
        color: green;
      }
      &-bottom{
        padding: 1rem 0 0;
        color: gray;
        // border: 1px solid black;
      }
      h1{
        transform: translateX(880px); //////
        transition: 1s;
          // border: 1px solid black;
          padding: 1rem 0;
          font-size: 2rem;
        }
    }
    &-btn{
      // border: 1px solid black;
      height: 30vh;
      text-align: center;
      background: linear-gradient(180deg , #80C4FD , white);
     button{
       transform: translateY(800px); //////
        transition: 1s;
       @extend %btn;
       width: 10%;
       &:hover{
         background: linear-gradient(90deg,#080808 0%,#919191 100%);
       }
     }
    }
  }
  &__box4{
    width: 100%;
    height: 50vh;
    position: relative;
    background:  rgb(252, 252, 252);
    // border: 1px solid black;
    &-cunter{
      box-shadow: 1px 1px 70px rgb(190, 190, 190);
      display: grid;
      grid-template-columns: repeat(4 , 1fr);
      width: 90%;
      height: 40vh;
      position: absolute;
      right: 5%;
      top: -20%;
      border-radius: 10px;
      background: white;
      // border: 1px solid black;
      &-box1 , &-box2, &-box3 , &-box4{
        // border: 1px solid black;
        display: grid;
        text-align: center;
        justify-content: center;
        align-content: center;
        .title{
          font-size: 3rem;
        }
      }
      &-box1{
        p{
          color: $colorbtn;
        }
      }
      &-box2{
        p{
          color: #80C4FD;
        }
      }
      &-box3{
        p{
          color: #9572FB;
        }
      }
      &-box4{
        p{
          color: orange;
        }
      }
    }
  }
  &__box5{
    width: 100%;
    height: 110vh;
    overflow: hidden;
    // border: 1px solid black;
    &-top{
      width: 100%;
      text-align: center;
      // border: 1px solid black;
      .title{
        color: $colorbtn;
        transition: 1s;
        transform: translateY(800px); //////
        padding: 1rem 0;
      }
    h1{
      transition: 1s;
      transform: translateY(800px); //////
      font-size: 2rem;
      padding: 1rem 0;
    }
    .des{
      padding: 1rem 0 2rem 0; 
      color: rgb(163, 163, 163);
    }
    }
    &-bottom{
      text-align: center;
      display: grid;
      grid-template-columns: repeat(4 , 1fr);
      grid-gap: 1rem;
      // border: 1px solid black;
      width: 95%;
      margin: auto;
      height: 70vh;
      &-box1 , &-box2 , &-box3 , &-box4{
        transform: translateY(600px); //////
        box-shadow: 0px 2px 5px rgb(214, 214, 214);
        transition: 250ms;
        border: 1px solid $bordercolor;
        background: rgb(250, 250, 250);
        border-radius: 5px;
        &-img{
          padding: 1rem 0;
          div{
              width: 30%;
              padding: 1.5rem 0;
              border-radius: 50%;
              margin: auto;
              background: white;
              box-shadow: 1px 1px 5px rgb(214, 214, 214);
              i{
                font-size: 2rem;
                color: $colorbtn;
              }
          }
        }
        &-title{
          padding: 1rem 0;
          color: $colorbtn;
        }
        &-option{
          padding: 1rem 0;
          p{
            color: rgb(163, 163, 163);
            i{
              color: $colorbtn;
            }
          }
        }
        &-des{
          font-size: 1.5rem;
          padding: 1rem 0;
          font-weight: bold;
        }
        &-btn{
          padding-bottom: 1rem;
          button{
            @extend %btn;
            width: 35%;
            background: white;
            color: $colorbtn;
            border: 1px solid $bordercolor;
            box-shadow: 1px 1px 5px rgb(214, 214, 214);
            &:hover{
            background: linear-gradient(90deg,#080808 0%,#919191 100%);
            color: white;
       }
          }
        }
        &:hover{
          border: 1px solid $colorbtn;
          box-shadow: none;
          background: white;
        }
      }
    }
  }
  &__box6{
    width: 100%;
    height: 70vh;
    position: relative;
    // border: 1px solid black;
    &-register{
      width: 95%;
      height: 45vh;
      margin: auto;
      position: absolute;
      background: #8f6affbb;
      overflow: hidden;
      text-align: center;
      border-radius: 10px;
      right: 2%;
      top: 15%;
      // border: 1px solid black;
      &-content{
        transform: translateY(300px); //////
        transition: 1s;
        width: 70%;
        margin: auto;
        // border: 1px solid black;
        .title{
          padding: 1rem 0;
          color: $colorbtn;
        }
        h1{
          padding: 0.5rem 0;
          font-size: 3rem;
          color: white;
          font-weight: bold;
        }
        .des{
          padding: 1rem 0;
          color: white;
        }
        &-btn{
          padding: 1rem;
          button{
            @extend %btn;
            width: 20%;
            &:hover{
              background: linear-gradient(90deg,#080808 0%,#919191 100%);
       }
          }
        }
      }
    }
  }
  .box1bottom{
    transform: translateY(0);
  }
  .box1right{
    transform: translateX(0);
  }
}
.active{
        color: $colorbtn !important;
    }
</style>
