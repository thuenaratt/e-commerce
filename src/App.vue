<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HeaderNav from './component/HeaderNav.vue';
</script>

<template>
  <div class="header flex h-20 justify-between">
    <img class="" src="/public/Logo2.png" alt="">
    <div class="header-middle flex items-center justify-between w-1/3 text-2xl">
      <h1>SKIN</h1>
      <h1>MAKE UP</h1>
      <h1>BODY</h1>
    </div>
    <div class="action flex justify-between h-full w-[13%] items-center">
      <img class="h-10" src="https://cdn-icons-png.flaticon.com/512/3287/3287968.png" alt="">
      <div class="flex">
        <img class="h-10" src="https://cdn-icons-png.flaticon.com/512/3144/3144456.png" alt="">
        <h1 class=" text-3xl">cart</h1>
      </div>
    </div>
  </div>
  <div class="bg-[#ffd8d8] h-14 flex items-center pl-8 my-6">
    <h1 class="text-xl">HOME</h1>
  </div>
  <div class=" h-40 bg-[#83adb1] mt-12 flex">
    <div class="left w-1/3 flex flex-col items-center pt-4">
      <h1 class=" text-4xl mb-4">Beauty Refresh</h1>
      <div class=" bg-white w-fit px-4">
        <h1 class="text-[#83adb1] text-6xl">SALE</h1>
      </div>
    </div>
    <div class="middle flex flex-col items-center justify-center">
      <h1 class=" text-4xl text-white">UP TO 20% OFF <span class="font-bold">SKIN CARE</span></h1>
      <p>Cleansers, moisturizers, eye creams & more: </p>
      <p>your spring skin care routine is waiting.</p>
      <p class="font-bold">Code: REFRESH</p>
    </div>
    <div class="left flex justify-center items-center w-1/4">
      <button class="text-xl bg-black p-2 text-white hover:bg-white hover:text-black">SHOP NOW</button>
    </div>
  </div>
  <div class="h-20 w-full grid grid-cols-5">
    <img class="" src="https://static.thcdn.com/images/small/webp/widgets/208-us/56/DS_Round_Nav_-_Untitled_Page_%2839%29-083456.png" alt="">
    <img src="https://static.thcdn.com/images/small/webp/widgets/208-us/12/DS_Round_Nav_-_Untitled_Page_%2838%29-083512.png" alt="">
    <img src="https://static.thcdn.com/images/small/webp/widgets/208-us/36/DS_Round_Nav_-_Untitled_Page_%2837%29-083536.png" alt="">
    <img src="https://static.thcdn.com/images/small/webp/widgets/208-us/07/DS_Round_Nav_-_Untitled_Page_%2834%29-083607.png" alt="">
    <img src="https://static.thcdn.com/images/small/webp/widgets/208-us/13/DS_Round_Nav_-_Untitled_Page_%2835%29-083613.png" alt="">
    <img src="https://static.thcdn.com/images/small/webp/widgets/208-us/25/DS_Round_Nav_-_Untitled_Page_%2836%29-083625.png" alt="">
    <img src="https://static.thcdn.com/images/small/webp//productimg/original/13956540-1194996957905834.jpg" alt="">
    </div>
    <div class="discription">
      <div class="productlistPage">
        <div class="mainContain">
          <div class="productlistHeader">
            <div class="Header_wrapper">
              <h2 id="product-title">Skin Care</h2>
              <p id="product-results">3003 results</p>

            </div>
            <div class="readmore">
              <div class="readmore_content">
                "Shop professional-strength, dermatologist recommended skin care products from top skin care brands including SkinCeuticals, 
                 SkinMedica, EltaMD, Obagi and more. Choose from a variety of cleansers, toners and exfoliators to help clear your skin of dirt, oil and impurities. 
                 Shop skin care with SPF and help protect your skin from harmful UV rays and reduce signs of aging.Find skin care products with your favorite ingredients such as vitamin c, 
                 hyaluronic acid, retinol and take on any skin care concerns. Weather you have dry, oily or combination skin, you'll be able to find skin care products that best fit your skin type and concerns. "
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    

  
</template>

<style scoped lang="scss">
  .discription{
    max-width: 1400px;
    margin-top: 24px;
    margin-left: auto;
    margin-right: auto;
    display: block;
    .productlistPage{
      box-sizing: border-box;
      display: flex;
      flex-wrap: nowrap;
      padding-left: 8px;
      padding-right: 8px;
      max-width: 1400px;
      margin-top: 24px;
      margin-left: auto;
      margin-right: auto;
      background: 0 0;
      flex-direction: row-reverse;
      .mainContain{
        margin-left: 0!important;
        margin-right: 0!important;
        box-sizing: border-box!important;
        flex-grow: 0!important;
        flex-shrink: 1!important;
        .productlistHeader{
          margin-left: auto!important;
          margin-right: auto!important;
          box-sizing: border-box!important;
          flex-direction: column!important;
          width: auto !important;
          display: flex !important;
          margin-bottom: 24px !important;
          max-width: 1400px!important;
          .Header_wrapper{
            display: flex !important;
            flex-direction: column !important;
            #product-title{
              font-family: "Poly Regular","Times New Roman",serif !important;
              font-size: 24px !important;
              line-height: 32px !important;
              //color: #000;
              font-weight: 400!important;
              letter-spacing: 0!important;
              text-transform: none!important;
              color: inherit!important;
              padding: 0 0 8px 0!important;
                margin: 0!important;
                flex-grow: 1!important;
            }
            #product-results{
              display: flex !important;
              font-family: "lato regular",Helvetica,Arial,sans-serif;
              font-size: 14px;
              line-height: 1.428;
              color: #000;
              font-weight: 500;
              letter-spacing: 0;
              text-transform: none;
              color: inherit;
              padding: 0;
              margin: 0;
              display: flex;
            }

          }
          .readmore{
            margin: 24px 0 0 0;
            width: 100%;
            position: relative;
            overflow: hidden;
            transition: height .5s ease;
            .readmore_content{
              font-family: "lato regular",Helvetica,Arial,sans-serif;
              font-size: 14px;
              line-height: 1.428;
              color: #000;
              font-weight: 500;
              letter-spacing: 0;
              text-transform: none;
              overflow: hidden;
            }
          }
          
    
        }
      }
    }
    
    
    

  }

  
</style>
