<template>
  <div>
    <div class="conitenr flex justify-between">
      <div class="continer">
        <div class="overlay">
          <div class="logo"></div>
          <div class="paragraph">
            <div class="r-paragraph">
              <p>
                " كان مؤتمر المرأة منظم جدا, شمل مشاركات من الأردن و الوطن
                العربي "
              </p>
              <p class="my-8 name">كارولين فرج</p>
              <p class="my-8 desc">
                نائب الرئيس للخدمات العربية <span>CNN</span> دبي
                <span>2019</span>
              </p>
            </div>
            <div class="boluts">
              <ul>
                <li></li>
                <li></li>
                <li></li>
                <li class="active"></li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "background1",
};
</script>
<style scoped>
.continer {
  background: url("~/assets/image/registration-image/5.jpg") no-repeat center
    center;
  background-size: cover;
  min-height: 937px;
  position: relative;
  width: 676px;
}
.continer .logo {
  background: url("~/assets/image/registration-image/logo-footer-ar.png")
    no-repeat center right;
  top: -41px;
  min-height: 200px;
  position: relative;
  margin: 32px;
}
.continer .overlay {
  overflow: hidden;
  position: absolute;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  color: white;
  background-color: rgba(0, 0, 20, 0.5);
}

.continer .overlay h1 {
  font-size: 70px;
  margin-top: 100px;
}
.continer .overlay .paragraph {
  overflow: hidden;
  display: flex;
  flex-direction: column-reverse;
  width: 100%;
  height: 500px;
  position: relative;
  top: 192px;
}
.continer .overlay .paragraph .r-paragraph {
  flex-direction: column-reverse;
  direction: rtl;
  width: 406px;
  position: absolute;
  right: 30px;
  height: 243px;
}
.continer .overlay .paragraph .r-paragraph p {
  font-weight: bold;
  font-size: 21px;
}
.continer .overlay .paragraph .r-paragraph > .name {
  font-size: 18px;
  color: #a71c24;
  font-weight: 400;
}
.continer .overlay .paragraph .r-paragraph .desc span {
  color: #b7b7b7;
}
.continer .overlay .paragraph .r-paragraph > .desc {
  font-size: 18px;
  color: #f0eaea;
  font-weight: 400;
}
.boluts {
  position: absolute;
  top: 423px;
  left: 50px;
}
.boluts ul {
  list-style: none;
  margin: 0;
  text-align: center;
}
.boluts ul .active {
  opacity: 1;
}
.boluts ul li {
  display: inline-block;
  opacity: 0.5;
  background-color: #f7f7f7;
  color: #333;
  font-weight: bold;
  height: 15px;
  width: 15px;
  border-radius: 10px;
  margin: 0 2px;
  cursor: pointer;
  float: left;
}
</style>
