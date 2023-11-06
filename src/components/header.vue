<template>
  <div class="2xl:flex items-center w-full mx-auto 2xl:h-auto bg-[#5F807D]">
    <div class="left_box 2xl:w-full py-[50px] px-[16px] 2xl:border-[#5F807D] 2xl:border-r-[20px] ">
      <div class="2xl:pl-[50px]">

        <div class="2xl:p-[41px] px-[18px] py-[16px] max-w-[380px] rounded-[15px] border-[1px] border-[#FFFFFF80] bg-[#73B2AC59] backdrop-blur-[20px] 2xl:max-w-[890px] mx-auto mb-2.5">
          <div class="flex items-center justify-start gap-1 2xl:gap-3">
            <span class="block 2xl:w-[30px] w-[15px] 2xl:h-[2px] h-[1.5px] bg-white"></span>
            <h2 class="text-white font-semibold 2xl:text-[20px] text-[15px]">
              Shaxsiy rivojlanish bo'yicha trening
            </h2>
          </div>
          <div>
            <h1 class="font-bold 2xl:pt-[2px] h-[40px] 2xl:h-[60px] text-[34px] text-white 2xl:text-[60px] 2xl:leading-[54px]">
              3 oylik
            </h1>
            <div class="2xl:flex 2xl:items-baseline ">
              <h1
                class="uppercase text-white text-[42px]  2xl:text-[100px] h-[50px] 2xl:pr-[10px] 2xl:h-[100px] font-extrabold 2xl:leading-[90px]"
              >
                yangilanish
              </h1>
              <p
                class="text-white 2xl:h-[80px] text-[24px]  2xl:text-[50px] font-bold 2xl:leading-[90px] 2xl:lowercase"
              >
                kursi
              </p>
            </div>
          </div>
          <div class="flex 2xl:items-center flex-col 2xl:flex-row 2xl:gap-6 flex-row 2xl:justify-between">
            <div
              class="relative flex items-center bg-[#C6FFF91A] rounded-[10px] backdrop-blur-[12.5px] mt-[45px] mb-[12px]"
            >
              <span
                class="flex items-center justify-center 2xl:h-[50px] h-[30px] text-[#00FFE6F2] text-[44px] mb-[4px] 2xl:mb-0 pr-[10px] 2xl:text-[80px] font-bold pl-[15px]"
                >+</span
              >
              <h1
                class="uppercase text-[#00FFE6] text-[24px]  2xl:text-[50px] font-extrabold py-[12px] 2xl:pr-[230px]"
              >
                bonus
              </h1>
              <div
                class="absolute 2xl:w-[250px] 2xl:h-[250px] h-[200px] w-[200px] right-0 bottom-[-60%] z-index-0"
              >
                <img src="../assets/book.png" alt="book" />
              </div>
            </div>
            <div
              class=" flex justify-center items-center bg-[#C6FFF91A] rounded-[10px] backdrop-blur-[17px] 2xl:mt-[34px] py-[8px] 2xl:h-[100px] 2xl:w-[330px] gap-2"
            >
              <div class="w-[45px] h-[45px]">
                <img src="../assets/fastdelivery.png" alt="fast delivery" />
              </div>
              <p class="w-[230px] text-white 2xl:text-[22px] text-[15px] font-medium">
                O'zbekiston bo'ylab yetkazib berish bepul
              </p>
            </div>
          </div>
        </div>
        <div
          class="bg-[#73B2AC59] backdrop-blur-[20px] max-w-[380px] 2xl:max-w-[890px] mt-[10px] mx-auto border-[#FFFFFF80] border-[1px] rounded-[15px] px-[28px] 2xl:px-[30px] 2xl:py-[20px]"
        >
          <div class="flex items-center justify-between max-w-[380px] 2xl:max-w-[890px] m-auto">
            <div class="flex flex-col">
              <h1
                class="text-[#FFFFFFB2] h-[35px] 2xl:h-[50px] text-[30px] 2xl:text-[50px] font-black line-through"
              >
                4.980.000
              </h1>
              <p class="text-[#FFFFFFB2] 2xl:text-[28px] text-[15px] font-medium">kurs narxi</p>
            </div>
            <div class="w-[174px] 2xl:block hidden" >
              <img src="../assets/atiga.png" alt="atiga" />
            </div>
            <div class="flex flex-col pr-[45px] pb-1 2xl:pr-[25px]">
              <h1 class="text-[#FFFFFF] text-[30px] 2xl:text-[50px] font-black 2xl:h-[50px] h-[35px]">
                79.000
              </h1>
              <p class="text-[#FFFFFF] text-[15px] 2xl:text-[28px] font-medium">dan oyiga</p>
            </div>
  
            <button
              v-on:click="isOpen = !isOpen"
              class="hover:bg-[#009789] hidden border-[3px] border-[#CFFFFA80] bg-[#0ACCBA] text-white font-bold 2xl:block text-[20px] px-[30px] py-[20px] rounded-[5px]"
            >
              Sotib olish
            </button>
          </div>
          
        </div>
        <div class="hover:bg-[#009789] mx-auto 2xl:hidden max-w-[380px] flex items-center justify-center mt-[24px] py-[16px] rounded-[5px] border-[#CFFFFA80] border-[3px] bg-[#0ACCBA] ">
            <button v-on:click="isOpen = !isOpen" class="text-white text-[16px] font-bold">Sotib oling</button>    
        </div>
      </div>
    </div>

    <div class="right_box w-full hidden 2xl:block py-[176px] px-[10px]">
      <div>
        <iframe
          data-v-b4304bcf
          class="m-auto md:w-[560px] md:h-[330px] w-[360px] h-[280px] rounded-[8px] p-[10px] bg-[#73B2AC59]"
          src="https://www.youtube.com/embed/kaJdoGFT56o?si=DYlKKGderXm7WsZy&controls=0"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen
          >
          
          </iframe
        >
      </div>
    </div>

    <div class="block 2xl:hidden m-auto bg-white  py-[50px]">
        <div class="">
          <div>
        <iframe
          data-v-b4304bcf
          class="m-auto md:w-[560px] md:h-[330px] w-[360px] h-[280px] rounded-[8px] p-[10px] bg-[#73B2AC59]"
          src="https://www.youtube.com/embed/kaJdoGFT56o?si=DYlKKGderXm7WsZy&controls=0"
          title="YouTube video player"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen
          >
          
          </iframe
        >
      </div>
        </div>
    </div>

    <div
      :class="isOpen ? 'block' : 'hidden'"
      class="bg-black fixed z-40 top-0 bottom-0 left-0 right-0 bg-opacity-[60%]"
    >
      <div
        class="bg-white 2xl:w-[700px] 2xl:h-[450px] p-[15px]  2xl:rounded-[30px] mx-auto 2xl:mt-[5%] mt-[5%] relative 2xl:p-[50px] w-[380px] h-[330px] rounded-[0.5rem]"
      >
        <button
          v-on:click="isOpen = !isOpen"
          class="absolute top-[-40px] right-[-30px]"
        >
          <span
            class="flex items-center justify-center h-[50px] text-white text-[50px] font-medium -rotate-45"
            >+</span
          >
        </button>
        <div>
          <h1 class="text-center 2xl:block hidden font-semibold text-[48px] mb-[40px]">
            Ma'lumot olish
          </h1>
          <div class="text-center 2xl:hidden block pb-[25px]">
            <h3 class="text-black text-[12px] font-normal"> Menejerdan ma’lumot olish uchun </h3>
            <h2 class="text-[#0ACCBA] text-[18px] font-extrabold text-center">Raqamingiz qoldiring</h2>
          </div>
          <form>
            <input
              class="border-[1px] border-[#C6C6C6] rounded-[12px] py-[16px] px-[15px] 2xl:py-[20px] 2xl:pl-[18px]   w-full mb-[16px] mx-auto"
              type="text"
              name="name"
              id="name"
              placeholder="Ismingiz"
            />
            <input
              class="border-[1px] border-[#C6C6C6] rounded-[12px] py-[16px] px-[15px] 2xl:py-[20px] 2xl:pl-[18px] w-full mb-[30px]"
              type="tel"
              name="tel"
              id="tel"
              placeholder="Telefon raqamingiz"
            />
          </form>
          <button
            class="w-full bg-[#0AD1BF] capitalize text-white 2xl:font-bold 2xl:text-[20px] 2xl:py-[20px] 2xl:rounded-[12px] rounded-[8px] text-[16px] py-[16px]"
          >
            yuborish
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data: () => {
    return {
      isOpen: false,
    };
  },
};
</script>
<style scoped>
.left_box {
  background-image: url("../assets/header.png");
  background-repeat: no-repeat;
  background-size: cover;
  background: center , cover , no-repeat;
}
.right_box {
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url("../assets/header2.png");
}
</style>
