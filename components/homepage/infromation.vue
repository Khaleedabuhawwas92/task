<template>
  <div class="container-infromation container mx-auto text-center">
    <div class="mt-16 flex flex-row justify-between">
      <div class="mt-32 flex">
        <img
          src="~/assets/image/home-page/icons8-left-48.png"
          alt=""
          class="cursor-pointer mr-4"
        />
        <div class="mr-1 text-4xl">03</div>
        <div class="mt-3">/</div>
        <div class="mt-3">09</div>
        <img
          src="~/assets/image/home-page/icons8-right-48.png"
          alt=""
          class="cursor-pointer ml-4"
        />
      </div>
      <div class="ml-16">
        <div class="mb-16 content-titl">
          <div class="title">الدورات القصيرة</div>
          <div class="lay"></div>
        </div>
        <div class="des">
          أصول تقدم أفضل الخدمات التدريبية والاستشارية بمنهجية علمية، والمساهمة
          في تأهيل وتطوير وتمكين الموارد البشرية والمؤسسات العربية، من خلال
          مواكبة المستجدات العالمية، واختيار أفضل الخبراء أكاديميـاً ومهنيـاً
        </div>
      </div>
    </div>
    <div class="flex justify-center">
      <div class="card flex flex-col mt-24 overflow-hidden mb-8 mr-8">
        <img src="~/assets/image/home-page/card-1.jpg" alt="" class="" />
        <div class="text-right m-4">
          <div class="font-semibold">الاقتصاد و التنمية</div>
          <div class="text-sm mt-2">
            دورة الاقتصاد و التنمية تتحدث عن دور الاقتصاد برفع لخدمات التدريبية
            والاستشارية بمنهجية علمية، والمساهمة في تأهيل وتطوير وتمكين الموارد
            البشرية والمؤسسات العربية
          </div>
          <div class="mt-6 font-semibold text-sm">المحاضرين</div>
          <div class="text-right flex justify-end mt-2">
            <img
              src="~/assets/image/home-page/tec.jpg"
              alt=""
              class="rounded-full"
            />
            <img
              src="~/assets/image/home-page/tec.jpg"
              alt=""
              class="rounded-full"
            />
            <img
              src="~/assets/image/home-page/tec.jpg"
              alt=""
              class="rounded-full"
            />
          </div>
          <div class="flex justify-between mt-8">
            <nuxt-link to="">سجل الان</nuxt-link>
            <div class="flex justify-s">
              <p class="mt-4 mr-2">,آية جمال</p>
              <p class="mt-4 mr-2">,عيسى النهار</p>
              <p class="mt-4 mr-2">,محمود عيسى</p>
            </div>
          </div>
        </div>
      </div>
      <div class="card flex flex-col mt-24 overflow-hidden mb-8 mr-8">
        <img src="~/assets/image/home-page/card-1.jpg" alt="" class="" />
        <div class="text-right m-4">
          <div class="font-semibold">الاقتصاد و التنمية</div>
          <div class="text-sm mt-2">
            دورة الاقتصاد و التنمية تتحدث عن دور الاقتصاد برفع لخدمات التدريبية
            والاستشارية بمنهجية علمية، والمساهمة في تأهيل وتطوير وتمكين الموارد
            البشرية والمؤسسات العربية
          </div>
          <div class="mt-6 font-semibold text-sm">المحاضرين</div>
          <div class="text-right flex justify-end mt-2">
            <img
              src="~/assets/image/home-page/tec.jpg"
              alt=""
              class="rounded-full"
            />
            <img
              src="~/assets/image/home-page/tec.jpg"
              alt=""
              class="rounded-full"
            />
            <img
              src="~/assets/image/home-page/tec.jpg"
              alt=""
              class="rounded-full"
            />
          </div>
          <div class="flex justify-between mt-8">
            <nuxt-link to="">سجل الان</nuxt-link>
            <div class="flex justify-s">
              <p class="mt-4 mr-2">,آية جمال</p>
              <p class="mt-4 mr-2">,عيسى النهار</p>
              <p class="mt-4 mr-2">,محمود عيسى</p>
            </div>
          </div>
        </div>
      </div>
      <div class="card flex flex-col mt-24 overflow-hidden mb-8 mr-8">
        <img src="~/assets/image/home-page/card-1.jpg" alt="" class="" />
        <div class="text-right m-4">
          <div class="font-semibold">ادارة المشتريات والخازن</div>
          <div class="text-sm mt-2">
            دورة الاقتصاد و التنمية تتحدث عن دور الاقتصاد برفع لخدمات التدريبية
            والاستشارية بمنهجية علمية، والمساهمة في تأهيل وتطوير وتمكين الموارد
            البشرية والمؤسسات العربية
          </div>
          <div class="mt-6 font-semibold text-sm">المحاضرين</div>
          <div class="text-right flex justify-end mt-2">
            <img
              src="~/assets/image/home-page/tec.jpg"
              alt=""
              class="rounded-full"
            />
            <img
              src="~/assets/image/home-page/tec.jpg"
              alt=""
              class="rounded-full"
            />
            <img
              src="~/assets/image/home-page/tec.jpg"
              alt=""
              class="rounded-full"
            />
          </div>
          <div class="flex justify-between mt-8">
            <nuxt-link to="">سجل الان</nuxt-link>
            <div class="flex justify-s">
              <p class="mt-4 mr-2">,آية جمال</p>
              <p class="mt-4 mr-2">,عيسى النهار</p>
              <p class="mt-4 mr-2">,محمود عيسى</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="button mt-16"><nuxt-link to="">تصفح كل الدورات</nuxt-link></div>
  </div>
</template>
<style scoped>
.container-infromation {
  height: 1067px;
  color: white;
}
.container-infromation > div:nth-child(1) {
  text-align: right;
}
.container-infromation > div:nth-child(2) {
}
.container-infromation > div:nth-child(3) {
}
.content-titl {
  position: relative;
  font-size: 35px;
  font-weight: bold;
  z-index: 99;
}
.content-titl .lay {
  position: absolute;
  background: #a71c24;
  padding: 26px 70px;
  right: 130px;
  top: 6px;
  z-index: -1;
}

.des {
  width: 984px;
  font-size: 20px;
}
.card {
  width: 400px;
  background: black;
  transition-duration: 0.5s;
}
.card:hover {
  box-shadow: 7px -8px 0px 0px rgba(204, 38, 38, 0.9);
  -webkit-box-shadow: 7px -8px 0px 0px rgba(204, 38, 38, 0.9);
  -moz-box-shadow: 7px -8px 0px 0px rgba(204, 38, 38, 0.9);
}
.card a {
  background-color: #a71c24;
  color: white;
  padding: 10px 15px;
  margin: 0px;
  font-weight: bold;
  font-size: 16;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  text-align: center;
}
.card p {
  font-size: 15px;
}
.button a {
  width: 50%;
  background-color: #000000;
  color: white;
  padding: 20px 166px;
  margin: 0px;
  font-weight: bold;
  font-size: 16;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  text-align: center;
}
</style>
