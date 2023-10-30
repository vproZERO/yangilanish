<template>
    <div class="footer w-full mx-auto py-[50px] 2xl:pb-[150px]">
        <div class="2xl:min-w-[900px] max-w-[380px]  m-auto  p-[20px] bg-[#FFFFFF1A] rounded-[10px] backdrop-blur-[39px] 2xl:mt-[25px]">
            <h1 class=" text-center text-white text-[24px] 2xl:text-[32px] font-bold 2xl:font-extrabold ">Kursga to'lov qilish</h1>
            <div class="2xl:w-[700px] flex items-center justify-between px-[15px] py-[12px] backdrop-blur-[8px] rounded-[10px] mt-[30px] mx-auto">
                <div class="flex items-center gap-[10px]">
                    <div>
                        <img src="../assets/union.svg" alt="union">
                    </div>
                    <div>
                        <h2 class="text-white text-[12px] font-medium">Siddiqova Shahnozaxon</h2>
                        <h1 class="text-white text-[16px] font-bold">8600030454974787</h1>
                    </div>
                </div>
                <div>
                    <img src="../assets/union2.svg" alt="union 2">
                </div>
            </div>
            <div class="gap-4 2xl:gap-[10px] pt-[30px] flex items-end justify-center ">
                <div class="flex items-center gap-[10px]">
                    <div>
                        <img src="../assets/union3.svg" alt="union 3">
                    </div>
                    <div>
                        <h2 class="text-white text-[14px] font-normal">Kurs narxi:</h2>
                        <h1 class="text-white text-[16px] font-semibold">79 000 so'm</h1>
                    </div>
                </div>
                <div class="flex items-center gap-[10px]">
                    <div>
                        <img src="../assets/union4.svg" alt="union4">
                    </div>
                    <p class="text-white text-[14px] font-normal w-[140px]">To'lovni qilib bo'lgach, skrinshotni jo'nating</p>
                </div>
            </div>
            <button class="hover:bg-[#009789] text-white text-[14px] font-bold bg-[#0ACCBA]  mt-[30px] px-[30px] w-full py-[15px] border-[#7AE4D980] border-[3px] rounded-[5px]  2xl:w-[700px] mx-auto flex items-center justify-center">Chekni Yuborish</button>

            <div class="w-[700px] mx-auto 2xl:block hidden">
                <h1 class="text-center text-white text-[32px] font-extrabold leading-8 py-[35px]">Ma'lumot olish</h1>
                <form >
                    <div class="flex items-center gap-[15px] justify-center px-[15px] py-[8px] mb-[20px] bg-[#FFFFFF1A] rounded-[10px]">
                        <div>
                            <img src="../assets/form1.svg" alt="form input">
                        </div>
                        <input class="bg-[#FFFFFF1A] outline-none w-[630px] flex items-center " type="text" placeholder="Ism familiyangiz*">
                    </div>
                    <div class="flex items-center gap-[15px] justify-center px-[15px] py-[8px] mb-[20px] bg-[#FFFFFF1A] rounded-[10px]">
                        <div>
                            <img src="../assets/form2.svg" alt="form input">
                        </div>
                        <input id="tel" class="bg-[#FFFFFF1A] outline-none w-[630px] flex items-center "  type="text" placeholder="Telefon raqamingiz*">
                    </div>
                </form>
            <button class=" hover:bg-[#009789] text-white text-[14px] font-bold bg-[#0ACCBA]  mt-[20px] mb-[30px]  py-[15px] border-[#7AE4D980] border-[3px] rounded-[5px]  w-[700px] mx-auto flex items-center justify-center">Yuborish</button>
            </div>
        </div>
        <div class="m-auto max-w-[380px] flex 2xl:hidden items-center justify-center flex-col gap-3 p-[20px] mt-[50px] bg-[#FFFFFF1A] rounded-[10px]">
            <h1 class="text-white text-[24px] font-bold">Ma'lumot olish</h1>
            <form >
                    <div class="flex items-center gap-[15px] justify-center px-[15px] py-[8px] mb-[20px] bg-[#FFFFFF1A] rounded-[10px]">
                        <div>
                            <img src="../assets/form1.svg" alt="form input">
                        </div>
                        <input class="bg-[#FFFFFF1A] outline-none w-[246px] flex items-center " type="text" placeholder="Ism familiyangiz*">
                    </div>
                    <div class="flex items-center gap-[15px] justify-center px-[15px] py-[8px] mb-[20px] bg-[#FFFFFF1A] rounded-[10px]">
                        <div>
                            <img src="../assets/form2.svg" alt="form input">
                        </div>
                        <input id="tel" class="bg-[#FFFFFF1A] outline-none w-[246px] flex items-center "  type="number" placeholder="Telefon raqamingiz*">
                    </div>
            </form>
            <button class=" hover:bg-[#009789] text-white text-[14px] font-bold bg-[#0ACCBA]  mt-[20px] mb-[30px]  py-[15px] border-[#7AE4D980] border-[3px] rounded-[5px]  w-[310px] mx-auto flex items-center justify-center">Yuborish</button>

        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .footer{
        background: linear-gradient(180deg,#18524c 0%,#02201c 100%);
        backdrop-filter: blur(50px);
    }
    input{
        background-color: transparent;
        color: white;
    }
</style>