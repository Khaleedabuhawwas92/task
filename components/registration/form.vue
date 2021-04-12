<template>
  <div class="container1">
    <h1>انشاء حساب</h1>
    <h1>إنضم لدى عائلة أصول للتنمية و الإبداع</h1>
    <form>
      <input
        type="text"
        class="text"
        name="firstname"
        placeholder="اسم الثلاثي"
      />

      <input
        type="text"
        class="text"
        name="lastname"
        placeholder="البريد الكتروني"
      />
      <input
        type="tel"
        class="text"
        id="phone"
        pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"
        placeholder="رقم الهاتف"
      />
      <input
        type="tel"
        class="text"
        id="phone"
        pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"
        placeholder=" كلمة السر"
      />

      <nuxt-link to="/loginScreen" class="create">تسجيل الدخول</nuxt-link>
    </form>
    <div class="footer">
      <div>لديك حساب؟</div>
      <nuxt-link to="/loginScreen" class="login">سجل الدخول</nuxt-link>
    </div>
  </div>
</template>
<script>
export default {
  name: "form1",
};
</script>
<style scoped>
.container1 {
  color: white;
  direction: rtl;
  width: 1000px;
  margin: auto;
  display: flex;
  flex-direction: column;
}

.container1 a {
  color: #a71c24;
}

.container1 .text {
  min-width: 97%;
  padding: 12px 20px;
  margin: 15px 30px;
  border-radius: 6px;
  box-sizing: border-box;
  color: rgb(243, 237, 237);
  border: none;
  background: #00000033;
  opacity: 1;
}

.container1 .create {
  float: left;
  width: 50%;
  background-color: #000000;
  color: white;
  padding: 14px 15px;
  margin: 19px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  text-align: center;
}

.container1 input:hover {
  background-color: #0000008a;
  border: 0.5px solid #a71c24;
}
.container1 input:focus {
  background-color: #0000008a;
  border: 0.5px solid #a71c24;
}
.container1 h1 {
  margin: 15px 30px;
  font-weight: bold;
}
.container1 .footer {
  margin: 35px auto 0px;
  position: relative;
  top: 130px;
  display: inline;
}
.container1 .footer div {
  display: inline;
}
</style>
