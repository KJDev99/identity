<script lang="ts" setup>

</script>

<template>
   <div class="bg-black py-[72px]">
      <div class="container !mt-[60px] !mb-8 flex justify-between">
         <img src="@/assets/img/darkLogo.svg" alt="">
         <div class="flex gap-6 items-center ">
            <div class="flex gap-3 max-md:hidden">
               <a class="text-white font-Manrope-500" href="#">{{ $t('AboutCompany') }}</a>
               <a class="text-white font-Manrope-500" href="#">{{ $t('News') }}</a>
               <a class="text-white font-Manrope-500" href="#">{{ $t('Products') }}</a>
               <a class="text-white font-Manrope-500" href="#">{{ $t('Contacts') }}</a>
               <a class="text-white font-Manrope-500" href="#">{{ $t('ReportBug') }}</a>
            </div>
            <h2 class="font-Manrope-700 text-white">+998 99 324-42-13</h2>
            <button class="bg-white font-Manrope-700 text-black">{{ $t('RequestCall') }}</button>
         </div>
      </div>
      <div class="container flex justify-between max-sm:flex-col">
         <p class="max-md:text-xs max-sm:mb-4 text-gray-900">{{ $t('PersonalData') }}</p>
         <p class="max-md:text-xs text-gray-900">{{ $t('PrivacyPolicy') }}</p>
      </div>

   </div>
</template>