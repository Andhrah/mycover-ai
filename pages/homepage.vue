<script>
import Button from '~/components/Button.vue'

export default {
  components: {
    Button,
  }
}
</script>

<style>
.bg-image {
  background: url('~/assets/images/home_bg.svg');
}
.contain-img {
  background: url('~/assets/images/dark_home_design.svg');
}
</style>

<template>
  <main class="h-screen">
    <section class="bg-fixed h-[90%] bg-image pl-36 pt-36">

      <div class="flex w-[33%] bg-[#F9FAFB] rounded-3xl px-1 h-[2.125rem] border border-[#F2F4F7] items-center justify-between">
        <p class="bg-[#47BFA3] text-[#FFFFFF] rounded-3xl px-3 text-xs	h-[1.625rem] flex items-center">Just in!</p>

        <p class="text-sm text-[#344054] font-light">Mycover.ai just launched there AI Inspection APP, </p>

        <i class="ri-arrow-right-line mr-1 text-[#667085]"></i>
      </div>

      <div class="flex justify-between h-[80%] items-center b">
        <div class="w-[40%] mt-14">
          <h1 class="text-5xl font-semibold text-transparent bg-clip-text bg-gradient-to-r from-[#000000] to-[#47BFA3] leading-tight">
            Revolutionizing the insurance experience in Africa
          </h1>

          <p class="mt-8 text-[#344054] font-light text-base">
            Our Open Insurance API enables businesses and innovators easily embed or build new insurtech solutions to distribute insurance to anyone, from anywhere. 
          </p>

          <div class="flex justify-between mt-20 w-[80%]">
            <Button class="text-[#FFFFFF] w-[11.6875rem]">Get Started</Button>
            <Button class="bg-[#F2F4F7] text-[#101828] w-[11.6875rem] flex items-center">
              View Demo
              <i class="ri-youtube-line text-[#475467] text-xl ml-2"></i>
            </Button>
          </div>
        </div>
        <img src="~/assets/images/home_insurance_img.png" alt="" class="h-full mt-8">
      </div>
    </section>

    <section class="flex flex-col pl-32 pt-24">
      <p class="text-[#344054] text-xl">Brands growing with us :</p>
      <div class="flex justify-between items-center mt-10 mr-36">
        <img src="~/assets/images/Bolt.svg" alt="bolt logo" class="h-10 w-[4.125rem]">

        <img src="~/assets/images/bitmama.svg" alt="bolt logo" class="">

        <img src="~/assets/images/black_copper.svg" alt="bolt logo" class="h-10 w-48">

        <img src="~/assets/images/jise.svg" alt="bolt logo" class="h-11 w-28">

        <img src="~/assets/images/transtura.svg" alt="bolt logo" class="h-10 w-36">

        <img src="~/assets/images/soft.svg" alt="bolt logo" class="h-12 w-48">
      </div>

      <div class="flex place-self-end h-6 bg-black w-[15.4375rem]">.</div>
    </section>

    <section class="bg-[#FAFBFD] text-center pt-20 text-[#1D2939] pb-24">
      <h2 class="text-3xl font-bold mb-2">Insurtech with innovators in mind</h2>
      <p class="text-xl font-light">Build insurtech solutions with Africa’s largest digital insurance infrastructure.</p>

      
      <div class="flex justify-between px-36 mt-24 text-left">
        <div class="w-[35rem] h-[31.875rem] bg-[#F4F3FF] rounded-xl pt-24 items-start">
          <div class="flex flex-col px-16 items-start">
            <img src="~/assets/images/built.svg" alt="bolt logo" class="h-12">
            <h3 class="text-2xl font-bold my-12">Built for Anyone</h3>
            <p class="text-xl font-light	mb-8">
              Direct access to several insurance companies in one place without worrying about multiple partnerships, integrations or compliance.
            </p>
          </div>
          <img src="~/assets/images/home_design.png" alt="bolt logo" class="h-30 w-56">
        </div>
       
        <div class="w-[35rem] h-[31.875rem] bg-[#ECFDF3] rounded-xl pt-16 items-start">
          <div class="flex flex-col px-16 items-start">
            <img src="~/assets/images/easy.svg" alt="bolt logo" class="h-12">
            <h3 class="text-2xl font-bold my-12">Easy to integrate APIs</h3>
            <p class="text-xl font-light	mb-14 leading-normal">
              Seamless and direct integrations into your platform. Built on a framework that lets you easily deploy insurance into the purchasing experience of customers.
            </p>
          </div>
          <img src="~/assets/images/home_design.png" alt="bolt logo" class="h-30 w-56">
        </div>
      </div>

      <div class="flex justify-between px-36 mt-6 text-left">
        <div class="w-[35rem] h-[31.875rem] bg-[#FFF6ED] rounded-xl pt-24 items-start">
          <div class="flex flex-col px-16 items-start">
            <img src="~/assets/images/automated.svg" alt="bolt logo" class="h-12">
            <h3 class="text-2xl font-bold my-12">Automated Claim Management</h3>
            <p class="text-xl font-light	mb-8">
              Your customers gets automated claim support, from notifications to loss assessments, and instant payouts using real-time data inputs.
            </p>
          </div>
          <img src="~/assets/images/home_design.png" alt="bolt logo" class="h-30 w-56">
        </div>
       
        <div class="w-[35rem] h-[31.875rem] bg-[#EFF8FF] rounded-xl pt-24 items-start">
          <div class="flex flex-col px-16 items-start">
            <img src="~/assets/images/end2end.svg" alt="bolt logo" class="h-12">
            <h3 class="text-2xl font-bold my-12">End-to-End Services</h3>
            <p class="text-xl font-light	mb-16">
              Get access to a significant tool in the insurance value chain; a robust admin support for policy and claims management.
            </p>
          </div>
          <img src="~/assets/images/home_design.png" alt="bolt logo" class="h-30 w-56">
        </div>
      </div>
    </section>

    <section class="text-center text-[#1D2939] pb-20">
      <div class="flex h-8 bg-[#1849A9] w-[15.4375rem]">.</div>

      <h2 class="text-3xl font-bold mb-3 mt-10">Exciting insurance products for all sectors </h2>
      <p class="text-xl font-light">
        Build insurtech solutions with Distribute tailor made products with access to multiple insurance companies.
      </p>

      <div class="flex justify-between px-36 mt-16">
        <div class="flex items-center w-[22.9375rem] h-[8.25rem] border rounded-md border-[#DBDFE4] px-10 shadow-sm">
          <img src="~/assets/images/home.svg" alt="home icon" class="h-8">
          <h2 class="ml-8 text-xl">Home</h2>
        </div>

        <div class="flex items-center w-[22.9375rem] h-[8.25rem] border rounded-md border-[#DBDFE4] px-10 shadow-sm">
          <img src="~/assets/images/auto.svg" alt="home icon" class="h-8">
          <h2 class="ml-8 text-xl">Auto</h2>
        </div>

        <div class="flex items-center w-[22.9375rem] h-[8.25rem] border rounded-md border-[#DBDFE4] px-10 shadow-sm">
          <img src="~/assets/images/gadgets.svg" alt="home icon" class="h-8">
          <h2 class="ml-8 text-xl">Gadget</h2>
        </div>
      </div>

      <div class="flex justify-between px-36 mt-8">
        <div class="flex items-center w-[22.9375rem] h-[8.25rem] border rounded-md border-[#DBDFE4] px-10 shadow-sm">
          <img src="~/assets/images/travel.svg" alt="home icon" class="h-8">
          <h2 class="ml-8 text-xl">Travel</h2>
        </div>

        <div class="flex items-center w-[22.9375rem] h-[8.25rem] border rounded-md border-[#DBDFE4] px-10 shadow-sm">
          <img src="~/assets/images/health.svg" alt="home icon" class="h-8">
          <h2 class="ml-8 text-xl">Health</h2>
        </div>

        <div class="flex items-center w-[22.9375rem] h-[8.25rem] px-10">
          <button class="ml-8 text-base text-[#47BFA3] mr-6">View more</button>
          <i class="ri-arrow-right-s-line"></i>
        </div>
      </div>
    </section>

    <section class="bg-[#FAFBFD] flex justify-between pl-36">
      <div class="pt-28">
        <h1 class="text-3xl">
          Manage all insurance activities from a unified platform
        </h1>

        <div class="flex justify-between mt-16">
          <div class="flex w-[55%]">
            <img src="~/assets/images/radio_btn_icon.svg" class="h-7 mt-5">
            <div class="text-[#1D2939] ml-4">
              <h1 class="text-3xl leading-loose">
                Designed for anyone
              </h1>

              <p class="text-xl font-normal">Sell to customers directly <br>from your dashboard.</p>
            </div>
          </div>

          <div class="flex w-[50%]">
            <img src="~/assets/images/radio_btn_icon.svg" class="h-7 mt-5">
            <div class="ml-4 text-[#1D2939]">
              <h1 class="text-3xl leading-loose">
                Manage policies
              </h1>

              <p class="text-xl font-normal">Process, activate and track customer policies. </p>
            </div>
          </div>
        </div>

        <div class="flex justify-between mt-16">
          <div class="flex w-[55%]">
            <img src="~/assets/images/radio_btn_icon.svg" class="h-7 mt-5">
            <div class="text-[#1D2939] ml-4">
              <h1 class="text-3xl leading-loose">
                Claims handling
              </h1>

              <p class="text-xl font-normal">SReliably automate claims <br>in real-time.</p>
            </div>
          </div>

          <div class="flex w-[50%]">
            <img src="~/assets/images/radio_btn_icon.svg" class="h-7 mt-5">
            <div class="ml-4 text-[#1D2939]">
              <h1 class="text-3xl leading-loose">
                Real-time analytics
              </h1>

              <p class="text-xl font-normal">Essential insights needed to grow your business.</p>
            </div>
          </div>
        </div>
      </div>
      
      <img src="~/assets/images/dashboard_img.svg" alt="dashoard image" class="">
    </section>

    <section>
      <div class="flex justify-between mt-32 contain-img px-32 h-[68.0625rem]">
        <div class="w-[55%] pt-32">
          <h2 class="text-[#47BFA3] text-3xl leading-relaxed">Everything you need to start building</h2>
          <p class="text-white text-xl my-6">
            We understand the crux of good developer experience while interfacing with an API. Our developer-friendly guide will get you started in no time.
          </p>

          <Button class="text-white mt-4 w-48">Read docs</Button>

          <div class="bg-[#1D2939] rounded-lg mt-14 p-10">

            <div class="flex mb-14">
              <img src="~/assets/images/radio_btn_icon.svg" class="h-7 mt-2">
              <div class="text-white ml-4">
                <h1 class="text-2xl mb-4">
                  APIs
                </h1>

                <p class="text-xl font-light">
                  Seamless API integrations designed to optimised user’s experience.
                </p>
              </div>
            </div>

            <div class="flex mb-14">
              <img src="~/assets/images/radio_btn_icon.svg" class="h-7 mt-2">
              <div class="text-white ml-4">
                <h1 class="text-2xl mb-4">
                  SDKs
                </h1>

                <p class="text-xl font-light">
                  Seamless API integrations designed to optimised user’s experience.
                </p>
              </div>
            </div>

            <div class="flex mb-14">
              <img src="~/assets/images/radio_btn_icon.svg" class="h-7 mt-2">
              <div class="text-white ml-4">
                <h1 class="text-2xl mb-4">
                  Claims
                </h1>

                <p class="text-xl font-light">
                  Reliably automate claims assessment with real-time data inputs, enabled by our API.
                </p>
              </div>
            </div>
          </div>
        </div>

        <div class="mt-16">
          <div class="flex flex-col bg-[#1D2939] rounded-lg mt-14 py-6 ml-8 items-center">
            <img src="~/assets/images/detail_logo.svg" class="mb-6">

            <img src="~/assets/images/detail_img.svg" class="">
          </div>

          <div class="bg-[#1D2939] p-8 rounded-lg mt-6 ml-8">
            <img src="~/assets/images/code_img.svg" class="">
          </div>
        </div>
      </div>
    </section>
  </main>
</template>
