<template>
  <div class="container-course container mx-auto flex">
    <div class="image flex justify-center flex-col">
      <img src="~/assets/image/home-page/cover-osool-1-2020-ar.png" alt="" />
      <div class="flex justify-between">
        <div class="ml-20 v1">2020</div>
        <div class="mr-20 v2 underline cursor-pointer">
          احصل على برامج الخطة التدريبية
        </div>
      </div>
    </div>
    <div class="form-c flex flex-col text-center justify-between mt-1">
      <div class="title">
        <div class="title-contint text-right">
          برامج أصول التدريبية المخصصة لحسب متطلبات شركتك المهنية و التقنية
        </div>
        <div class="lay"></div>
      </div>
      <div></div>
      <div class="contint-form flex text-right flex-col mx-10">
        <div class="mr-10">
          اطلب برنامجك المخصص من خلال تعبئة الحقول التالية
        </div>
        <div>
          <input type="text" placeholder="البريد الاكتروني" />
          <input type="text" placeholder="الاسم" />
        </div>
        <div class="">
          <input type="text" placeholder="جهة العمل " />
          <input type="text" placeholder="الهاتف " />
        </div>
        <div class="mr-10">
          <textarea name="" placeholder="للاستفسار "></textarea>
        </div>
      </div>
      <div><nuxt-link to="/loginScreen"> ارسل المعلومات</nuxt-link></div>
    </div>
  </div>
</template>
<style scoped>
.container-course {
  color: white;
  margin-bottom: 100px;
}
.container-course .image {
  width: 60%;
}
.container-course .form-c {
}
.v1 {
  font-size: 40px;
  font-weight: bold;
  color: #a71c24;
}
.v2 {
  font-size: 30px;
  font-weight: bold;
}
.title {
  position: relative;
}
.title-contint {
  font-size: 35px;
  z-index: 999;
}
.lay {
  background: #a71c24;
  padding: 20px;
  position: absolute;
  z-index: -1;
  width: 400px;
  left: 100px;
  top: 14px;
}
.contint-form {
  width: 100%;
}
.contint-form input {
  direction: rtl;
  padding: 9px 20px;
  margin: 6px 38px;
  width: 40%;
  background: #3f3e3e;
}
.contint-form input:hover {
  border: 1px solid #a71c24;
}
.contint-form textarea {
  direction: rtl;
  background: #3f3e3e;
  margin-top: 12px;
  padding: 9px 20px;
  width: 95%;
}
.contint-form textarea:hover {
  border: 1px solid #a71c24;
}
a {
  width: 50%;
  background-color: #000000;
  color: white;
  padding: 14px 157px;
  margin: 0px;
  font-weight: bold;
  font-size: 16;
  border: none;
  border-radius: 4px;

  text-align: center;
}
a:hover {
  border: 1px solid #a71c24;
}
</style>
