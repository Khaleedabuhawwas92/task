<template>
  <div class="container2">
    <h1>تسجيل الدخول</h1>
    <h1>قم بتعبئة المعلومات في الحقول</h1>
    <form>
      <input
        type="text"
        name="firstname"
        placeholder=" البريد الاكتروني أو رقم الهاتف"
      />

      <input type="text" name="lastname" placeholder="كلمة السر " />
      <div class="flex justify-between rember">
        <div class="contint-chexkbox">
          <input type="checkbox" class="checkbox" />
          <p>ذكرني</p>
        </div>
        <nuxt-link to="" class="forget">نسيت كلمة السر؟</nuxt-link>
      </div>

      <nuxt-link to="/" class="create">تسجيل الدخول</nuxt-link>
    </form>
    <div class="footer">
      <div>ليس لديك حساب؟</div>
      <nuxt-link to="/createAccount" class="login">انشى حساب الان </nuxt-link>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
body {
  box-sizing: border-box;
}
.container2 {
  color: white;
  direction: rtl;
  width: 1000px;
  margin: auto;
  display: flex;
  flex-direction: column;
}

.container2 .forget {
  color: white;
}
.container2 form {
  width: 900px;
}
.container2 form .rember {
  width: 100%;
  margin: 13px 5px;
  padding: 15px;
}
.contint-chexkbox {
  display: flex;
  flex-direction: row;
  text-align: center;
}
form input[type="checkbox"]:checked:after {
  color: white;
  margin: 0 -8px;
  padding: 15px 15px;
  content: "✔";
  font-size: 35px;
}
.contint-chexkbox p {
  margin: auto 15px;
}
.container2 input[type="checkbox"] {
  width: 40px;
  height: 40px;
  -webkit-appearance: none;
  -moz-appearance: none;
  -o-appearance: none;
  background: #2e2e2e;
  outline: none;
  border: none;
}
.container2 input:hover {
  background-color: #0000008a;
  border: 0.5px solid #a71c24;
}

.container2 input[type="text"] {
  width: 100%;
  padding: 12px 20px;
  margin: 15px auto;
  border-radius: 6px;
  box-sizing: border-box;
  color: rgb(243, 237, 237);
  border: none;
  background: #00000033;
  opacity: 1;
}

.container2 .create {
  float: left;
  width: 50%;
  background-color: #000000;
  color: white;
  padding: 12px 20px;
  margin: 0px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  text-align: center;
}
.container2 .footer a {
  color: #751920;
}

input:hover {
  background-color: #0000008a;
  border: 0.5px solid #a71c24;
}
input:focus {
  background-color: #0000008a;
  border: 0.5px solid #a71c24;
}
h1 {
  margin: 15px 30px;
  font-weight: bold;
}
.footer {
  margin: 35px auto 0px;
  position: relative;
  top: 200px;
  display: inline;
}
.footer div {
  display: inline;
}
</style>
