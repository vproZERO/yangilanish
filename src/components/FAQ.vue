<template>
    <div
        @click="$emit('toggleOpen', index)"
        :class="open ? 'faq open' : 'faq'"
        class="border-b-[1.5px] mx-auto 2xl:max-w-[800px] max-w-[330px] mx-auto 2xl:pb-[20px] 2xl:mb-[20px] pb-[10px] mb-[10px]"
    >
        <div class="question text-[16px]   font-bold 2xl:text-[23px] 2xl:leading-[59px] aos-init aos-animate" data-aos="fade-up-right"  data-aos-duration="1500">
            <p class="max-w-[270px] 2xl:max-w-[900px] aos-init aos-animate">{{ faq.question }}</p>
        </div>
        <div class="answer font-medium text-[14px] text-[#47474F] 2xl:text-[20px] 2xl:leading-[32px]">
            <p class="max-w-[270px] 2xl:max-w-[900px]">{{ faq.answer }}</p>
        </div>
    </div>
</template>
<script>
export default {
    name: 'FAQ',
    props: ['faq', 'index' , 'open']
}
</script>
<style lang="">
    
</style>