<template>
    <div class="container mx-auto pt-[150px] bg-white">
        <h1 class="text-center m-auto 2xl:text-[50px] text-[28px] font-bold text-[#152221] pb-[24px] max-w-[330px] 2xl:max-w-[690px] ">Tez-tez so'raladigan savollar</h1>
        <div class="faqs pb-[50px] mx-auto max-w-[330px] 2xl:max-w-[850px]">
            <FAQ
                v-for="(faq , i) in faqs"
                :faq="faq"
                :index="i"
                :key="i"
                :open="faq.open"
                @toggleOpen="toggleOpen"
            />
        </div>
    </div>
</template>
<script>
import FAQ from './FAQ.vue'
export default {
    components: {
        FAQ,
    },
    data: () => {
        return {
            faqs: [
                {
                    question: "Kitob olganimdan keyin to’lov qilsam bo’ladimi?",
                    answer: "Albatta, qo’lingizga kitob yetib kelgandan keyin to’lov qilish imkoniyati ham bor.",
                    open:false,
                },
                {
                    question: "Bir nechta kitobdan xarid qilsam chegirma bormi?",
                    answer: "Agar siz 2 ta kitob xarid qilsanigz 1 ta kitobni BEPUL qo’lga kiritasiz",
                    open:false,
                },
                {
                    question: "Chegirma muddati qancha vaqt davom etadi?",
                    answer: "Chegirmamiz joylar soni tugaguncha davom etadi.",
                    open:false,
                },
                {
                    question: " Kitob qanday yetkazib beriladi?",
                    answer: "Pochta orqali O’zbekistoning istalgan joyiga 1 kun ichida yetkazib beriladi. Kitob kelishi bilan sizga pochtadan telefon qilishadi va pochtaga kelib olib ketishingiz kerak bo’ladi.",
                    open:false,
                },
            ],
        };
    },
    methods: {
        toggleOpen: function (index) {
            this.faqs = this.faqs.map((faq , i) => {
                if(index === i) {
                    faq.open = !faq.open
                }else{
                    faq.open = false
                }

                return faq
            })
        }
    }
}
</script>
<style>
    .faq .question {
        position: relative;
        transition: all 0.4s linear;
    }
    .faq.open .question{
        margin-bottom: 15px;
    }
    .faq.open .question::after{
        transform: translateY(-50%) rotate(180deg);
        background-image: url("../assets/minus.png");
    }
    .faq.open .answer{
        opacity: 1;
        max-height: 1000px;
    }
    .faq .question::after {
        content: "";
        position: absolute;
        top: 50%;
        right: 0;
        transform: translateY(-50%) rotate(0deg);
        width: 30px;
        height: 30px;
        background-image: url("../assets/plus.png");
        background-position: center;
        background-size: contain;
        transition: all 0.4s linear;
    }
    .faq .answer {
        opacity: 0;
        overflow-y: hidden;
        max-height: 0;
        transition: all 0.4s ease-out;
    }
</style>