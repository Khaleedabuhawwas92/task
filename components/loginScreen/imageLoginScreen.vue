<template>
  <div>
    <div class="">
      <div class="continer1">
        <div class="overlay-image">
          <div class="logo"></div>
          <div class="paragraph">
            <div class="header1">
              <p>إصدار شركة أصول</p>
              <h2>المنصة القيادية الأفضل في الاستشارات و التدريب</h2>
            </div>
            <div class="contint">
              <div>دورات متنوعة</div>
              <div>شهادات معتمدة</div>
              <div>معايير عالية</div>
            </div>
            <nuxt-link to="/createAccount">اطلب عرضاً توضيحيا</nuxt-link>
          </div>
          <div class="footer1">
            <h3>نلنا الثقة من أكثر من 100 عميل</h3>
            <div class="brands">
              <img src="~/assets/image/login-image/3.png" />
              <img src="~/assets/image/login-image/1.png" />
              <img src="~/assets/image/login-image/2.png" />
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "background2",
};
</script>
<style scoped>
.continer1 {
  background: url("~/assets/image/login-image/5.jpg") no-repeat center center;
  background-size: cover;
  min-height: 937px;
  position: relative;
  width: 676px;
}
.continer1 .overlay-image {
  overflow: hidden;
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  color: white;
  background-color: rgba(0, 0, 20, 0.5);
}

.continer1 .overlay-image .logo {
  background: url("~/assets/image/registration-image/logo-footer-ar.png")
    no-repeat center right;
  top: -41px;
  min-height: 200px;
  position: relative;
  margin: 32px;
}
.continer1 .overlay-image .paragraph {
  box-sizing: border-box;
  margin-top: 100px;
  display: flex;
  flex-direction: column-reverse;
  width: 100%;
  height: 400px;
}
.continer1 .overlay-image .paragraph .header1 {
  text-align: center;
  position: relative;
  bottom: 350px;
  width: 568px;
  margin: 20px auto 0 auto;
}

.continer1 .overlay-image .paragraph .header1 h2 {
  font-size: 28px;
  font-weight: bold;
  margin: 20px auto 0 auto;
}

.continer1 .overlay-image .paragraph .contint {
  display: flex;
  flex-direction: row;
  margin: auto;
}
.continer1 .overlay-image .paragraph .contint div {
  padding: 5px 9px;
  margin: auto 2px;
  cursor: pointer;
}
.continer1 .overlay-image .paragraph .contint div:nth-child(2) {
  border-left: 1px solid #f7f3f3;
  border-right: 1px solid #f3f1f1;
}
.continer1 .overlay-image .paragraph a {
  position: relative;
  font-weight: bold;
  margin: 30px auto;
  top: 210px;
  padding: 15px 40px;
  background: crimson;
  color: white;
}
.overlay-image .footer1 {
  margin: auto;
  width: 100%;
  text-align: center;
}
.overlay-image .footer1 .brands {
  margin: 50px auto;
  display: flex;
  width: 100%;

  justify-content: space-around;
}
.overlay-image .footer1 .brands img {
  margin: 20px auto 15px 15px;
}
.overlay-image .footer1 .brands img:nth-child(1) {
  width: 162px;
  height: 54px;
}
.overlay-image .footer1 .brands img:nth-child(2) {
  width: 188px;
  height: 50px;
}
.overlay-image .footer1 .brands img:nth-child(3) {
  width: 151px;
  height: 54px;
}
</style>
