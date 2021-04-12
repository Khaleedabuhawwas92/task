<template>
  <div class="container mx-36">
    <div class="container-navbar flex justify-between">
      <div class="flex flex-row bluer padd filter text-base">
        <p class="pr-4 text-white border-r-2 font-bold">تسجيل دخول</p>
        <p class="pl-4 text-white font-bold">انشاء حساب</p>
      </div>

      <div class="flex padd flex-row-reverse">
        <div
          class="pl-16 pr-3 border-red-700 ele font-bold border-r flex flex-row-reverse"
        >
          <p>الاصول</p>
          <img
            src="~/assets/image/home-page/icons8-expand-arrow-15.png"
            alt="pl-16"
            width="20px"
            class="mr-4 cursor-pointer"
          />
        </div>
        <div
          class="pl-16 pr-3 border-red-700 ele font-bold border-r flex flex-row-reverse"
        >
          <p>الشهادات</p>
          <img
            src="~/assets/image/home-page/icons8-expand-arrow-15.png"
            alt="pl-16"
            width="20px"
            class="mr-4 cursor-pointer"
          />
        </div>
        <div
          class="pl-16 pr-3 border-red-700 ele font-bold border-r flex flex-row-reverse"
        >
          <p>التدريب</p>
          <img
            src="~/assets/image/home-page/icons8-expand-arrow-15.png"
            alt="pl-16"
            width="20px"
            class="mr-4 cursor-pointer"
          />
        </div>
        <div
          class="pl-16 pr-3 border-red-700 ele font-bold border-r flex flex-row-reverse"
        >
          <p>البرامج</p>
          <img
            src="~/assets/image/home-page/icons8-expand-arrow-15.png"
            alt="pl-16"
            width="20px"
            class="mr-4 cursor-pointer"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container-navbar .ele {
  font-size: 14px;
}
.bluer {
  backdrop-filter: blur(20px);
}
.padd {
  padding: 20px;
}
</style>
