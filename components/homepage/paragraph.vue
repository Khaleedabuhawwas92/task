<template>
  <div>
    <div
      class="container-paragraph my-4 container mx-auto px-4 flex flex-col text-center"
    >
      <div class="title m-10">
        <div class="title-background"></div>
        <div class="insde-title">
          <span>لماذا</span> <span class="mr-2"> أصول؟</span>
        </div>
      </div>
      <div class="descraption mb-24">
        أصول تقدم أفضل الخدمات التدريبية والاستشارية بمنهجية علمية، والمساهمة في
        تأهيل وتطوير وتمكين الموارد البشرية والمؤسسات العربية، من خلال مواكبة
        المستجدات العالمية، واختيار أفضل الخبراء أكاديميـاً ومهنيـاً
      </div>
      <div class="button mb-8">
        <nuxt-link to="">اطلب عرضاً توضيحيا</nuxt-link>
      </div>
      <div class="boxs mt-4 flex justify-between relative">
        <div class="box1 mx-8 ml-auto border p-20 bluer flex justify-between">
          <h2 class="pl-60">آخرين</h2>
          <div class="par">
            <p class="">
              أصول تقدم أفضل الخدمات التدريبية والاستشارية بمنهجية علمية،
              والمساهمة في تأهيل وتطوير وتمكين الموارد البشرية والمؤسسات
              العربية، من خلال مواكبة المستجدات العالمية، واختيار أفضل الخبراء
              أكاديميـاً ومهنيـاً
            </p>
          </div>
          <div class="par">
            <p class="">
              أصول تقدم أفضل الخدمات التدريبية والاستشارية بمنهجية علمية،
              والمساهمة في تأهيل وتطوير وتمكين الموارد البشرية والمؤسسات
              العربية، من خلال مواكبة المستجدات العالمية، واختيار أفضل الخبراء
              أكاديميـاً ومهنيـاً
            </p>
          </div>
        </div>
        <div class="box1 mx-8 mr-auto border p-20 bluer flex justify-between">
          <h1>لايوجد</h1>
          <h2 class="">وجه مقارنة, لكن هذا ما يميزنا</h2>

          <div class="par">
            <p class="">
              أصول تقدم أفضل الخدمات التدريبية والاستشارية بمنهجية علمية،
              والمساهمة في تأهيل وتطوير وتمكين الموارد البشرية والمؤسسات
              العربية، من خلال مواكبة المستجدات العالمية، واختيار أفضل الخبراء
              أكاديميـاً ومهنيـاً
            </p>
          </div>
          <div class="par">
            <p class="">
              أصول تقدم أفضل الخدمات التدريبية والاستشارية بمنهجية علمية،
              والمساهمة في تأهيل وتطوير وتمكين الموارد البشرية والمؤسسات
              العربية، من خلال مواكبة المستجدات العالمية، واختيار أفضل الخبراء
              أكاديميـاً ومهنيـاً
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.container-paragraph {
  height: 500px;
  width: 100%;
}
.container-paragraph .title {
  font-size: 50px;
  font-weight: bold;
  position: relative;
}
.container-paragraph .title .insde-title span {
  z-index: 99;
  max-width: 300px;
  position: relative;
}
.container-paragraph .title .insde-title span:nth-child(1) {
  color: black;
}
.container-paragraph .title .title-background {
  width: 50px;
  background: #a71c24;
  padding: 39px 107px;
  position: absolute;
  top: 5px;
  left: 645px;
  z-index: 1;
}
.descraption {
  max-height: 1435px;
  font-size: 32px;
}
.button a {
  width: 50%;
  background-color: #000000;
  color: white;
  padding: 14px 20px;
  margin: 0px;
  font-weight: bold;
  font-size: 16;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  text-align: center;
}

.boxs {
  padding: 20px;
  text-align: right;
}
.boxs .box1 .par {
  width: 230px;
  height: 72px;
  overflow: hidden;
}
.boxs .box1 .par p {
  direction: rtl;
}
.boxs .box1 {
  width: 674px;
  height: 170px;
  border: 1px solid #a71c24;
}
.boxs .box1 h1 {
  position: absolute;
  bottom: 102px;
  left: 582px;
  font-size: 50px;
  font-weight: bold;
  border-bottom: 3px solid #a71c24;
}
.boxs .box1 h2 {
  position: absolute;
  bottom: 102px;
  left: 272px;
  font-size: 24px;
}
</style>
