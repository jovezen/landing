<template>
  <div>
    <index-navbar />
    <section class="header relative items-center flex h-screen max-h-860-px">
      <div class="container mx-auto items-center flex flex-wrap">
        <div class="w-full md:w-8/12 lg:w-6/12 xl:w-6/12 px-4 pb-4">
          <div class="pt-32 sm:pt-0">
            <h2 class="font-semibold text-4xl text-gray-700">
              ZenChain Protocol
            </h2>
            <p class="mt-4 text-xl leading-relaxed text-gray-600">
              A Dedicated Blockchain That Is Optimized Specifically For DeFi And
              NFTs
            </p>
            <div class="mt-12">
              <a
                href="https://docs.zenchain.co"
                target="_blank"
                class="get-started text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-green-500 active:bg-green-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
              >
                Get started
              </a>
              <a
                href="https://github.com/zenchainprotocol"
                class="github-star ml-1 text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-gray-800 active:bg-gray-700 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
                target="_blank"
              >
                Github Star
              </a>
            </div>
          </div>
        </div>

        <img
          class="w-full md:w-8/12 lg:w-6/12 xl:w-6/12 px-4"
          :src="headerImg"
          alt="..."
        />
      </div>
    </section>

    <section class="pb-40 relative bg-gray-200">
      <div class="container mx-auto">
        <div class="flex flex-wrap items-center">
          <div class="w-10/12 md:w-6/12 lg:w-4/12 px-4 md:px-4 mr-auto ml-auto">
            <div
              class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6 shadow-lg rounded-lg bg-green-600"
            >
              <img
                alt="..."
                src="@/assets/img/wood.png"
                class="w-full align-middle rounded-t-lg"
              />
              <blockquote class="relative p-8 mb-4">
                <svg
                  preserveAspectRatio="none"
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 583 95"
                  class="absolute left-0 w-full block h-95-px -top-94-px"
                >
                  <polygon
                    points="-30,95 583,95 583,65"
                    class="text-green-600 fill-current"
                  ></polygon>
                </svg>
                <h4 class="text-xl font-bold text-white">
                  What is ZenChain?
                </h4>
                <p class="text-md font-light mt-2 text-white">
                  ZenChain is a dedicated blockchain that is optimized
                  specifically for DeFi and NFT applications
                </p>
              </blockquote>
            </div>
          </div>

          <div class="w-full md:w-6/12 px-4">
            <div class="flex flex-wrap">
              <div class="w-full md:w-6/12 px-4">
                <div class="relative flex flex-col mt-4 ">
                  <div class="px-4 py-5 flex-auto" data-aos="fade-up">
                    <div
                      class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-sitemap"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      Scalable, high-throughput Blockchain
                    </h6>
                    <p class="mb-4 text-gray-600">
                      Proof-of-Stake blockchain, built using the Cosmos SDK
                      which runs on top of the Tendermint Core consensus engine.
                    </p>
                  </div>
                </div>
                <div class="relative flex flex-col min-w-0">
                  <div class="px-4 py-5 flex-auto" data-aos="fade-up">
                    <div
                      class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fa fa-link"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      Cross-Chain
                    </h6>
                    <p class="mb-4 text-gray-600">
                      Support cross-chain with bridge solution between Ethereum,
                      Binance smartchain, Tron and more
                    </p>
                  </div>
                </div>
              </div>
              <div class="w-full md:w-6/12 px-4">
                <div class="relative flex flex-col min-w-0 mt-4">
                  <div class="px-4 py-5 flex-auto" data-aos="fade-right">
                    <div
                      class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-newspaper"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      Built for Defi & NFTs
                    </h6>
                    <p class="mb-4 text-gray-600">
                      With built-in core DApp for Defi & NFTs - ZenChain is
                      ready for Defi & NFTs ecosystem from start
                    </p>
                  </div>
                </div>
                <div class="relative flex flex-col min-w-0">
                  <div class="px-4 py-5 flex-auto" data-aos="fade-left">
                    <div
                      class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-white"
                    >
                      <i class="fas fa-drafting-compass"></i>
                    </div>
                    <h6 class="text-xl mb-1 font-semibold">
                      Supports smart contracts
                    </h6>
                    <p class="mb-4 text-gray-600">
                      ZenChain supports smart contracts, enabled by CosmWasm,
                      EVM technology.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="pt-20 pb-20">
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap justify-center text-center mb-24">
          <div class="w-full lg:w-6/12 px-4">
            <h2 class="text-4xl font-semibold">Core team</h2>
          </div>
        </div>
        <div class="flex flex-wrap">
          <div class="w-full md:w-6/12 lg:w-4/12 lg:mb-0 mb-12 px-4">
            <span
              class="animate-ping absolute inline-flex h-full w-full rounded-full bg-purple-400 opacity-75"
            ></span>

            <div class="px-6">
              <img
                alt="..."
                :src="team1"
                class="shadow-lg rounded-full mx-auto max-w-120-px"
              />
              <div class="pt-6 text-center">
                <h5 class="text-xl font-bold">Josiah Tan</h5>
                <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                  Founder
                </p>
                <div class="mt-6">
                  <button
                    class="bg-blue-400 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                    type="button"
                  >
                    <i class="fab fa-linkedin"></i>
                  </button>
                </div>
              </div>
            </div>
          </div>
          <div class="w-full md:w-6/12 lg:w-4/12 lg:mb-0 mb-12 px-4">
            <div class="px-6">
              <img
                alt="..."
                :src="team2"
                class="shadow-lg rounded-full mx-auto max-w-120-px"
              />
              <div class="pt-6 text-center">
                <h5 class="text-xl font-bold">Christopher Chan</h5>
                <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                  Business Development Manager
                </p>
                <div class="mt-6">
                  <button
                    class="bg-blue-400 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                    type="button"
                  >
                    <i class="fab fa-linkedin"></i>
                  </button>
                </div>
              </div>
            </div>
          </div>
          <div class="w-full md:w-6/12 lg:w-4/12 lg:mb-0 mb-12 px-4">
            <div class="px-6">
              <img
                alt="..."
                :src="team3"
                class="shadow-lg rounded-full mx-auto max-w-120-px"
              />
              <div class="pt-6 text-center">
                <h5 class="text-xl font-bold">Kawasaki Takao</h5>
                <p class="mt-1 text-sm text-gray-500 uppercase font-semibold">
                  Tech Lead
                </p>
                <div class="mt-6">
                  <button
                    class="bg-blue-400 text-white w-8 h-8 rounded-full outline-none focus:outline-none mr-1 mb-1"
                    type="button"
                  >
                    <i class="fab fa-linkedin"></i>
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="py-20 bg-gray-700 overflow-hidden">
      <div class="container mx-auto pb-64">
        <div class="flex flex-wrap justify-center">
          <div class="w-full md:w-5/12 px-12 md:px-4 ml-auto mr-auto md:mt-64">
            <div
              class="text-gray-600 p-3 text-center inline-flex items-center justify-center w-16 h-16 mb-6 shadow-lg rounded-full bg-white"
            >
              <i class="fas fa-code-branch text-xl"></i>
            </div>
            <h3 class="text-3xl mb-2 font-semibold leading-normal text-white">
              Open Source
            </h3>
            <p
              class="text-lg font-light leading-relaxed mt-4 mb-4 text-gray-500"
            >
              Since
              <a
                href="https://tailwindcss.com/?ref=creativetim"
                class="text-gray-400"
                target="_blank"
              >
                Tailwind CSS
              </a>
              is an open source project we wanted to continue this movement too.
              You can give this version a try to feel the design and also test
              the quality of the code!
            </p>
            <p
              class="text-lg font-light leading-relaxed mt-0 mb-4 text-gray-500"
            >
              Get it free on Github and please help us spread the news with a
              Star!
            </p>
            <a
              href="https://github.com/creativetimofficial/vue-notus?ref=vn-index"
              target="_blank"
              class="github-star mt-4 inline-block text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-gray-800 active:bg-gray-700 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
            >
              Github Star
            </a>
          </div>

          <div class="w-full md:w-4/12 px-4 mr-auto ml-auto mt-32 relative">
            <i
              class="fab fa-github text-gray-800 text-55 absolute -top-150-px -right-100 left-auto opacity-80"
            ></i>
          </div>
        </div>
      </div>
    </section>

    <section class="pb-16 bg-gray-300 relative pt-32">
      <div
        class="-mt-20 top-0 bottom-auto left-0 right-0 w-full absolute h-20"
        style="transform: translateZ(0);"
      >
        <svg
          class="absolute bottom-0 overflow-hidden"
          xmlns="http://www.w3.org/2000/svg"
          preserveAspectRatio="none"
          version="1.1"
          viewBox="0 0 2560 100"
          x="0"
          y="0"
        >
          <polygon
            class="text-gray-300 fill-current"
            points="2560 0 2560 100 0 100"
          ></polygon>
        </svg>
      </div>

      <div class="container mx-auto">
        <div
          class="flex flex-wrap justify-center bg-white shadow-xl rounded-lg -mt-64 py-16 px-12 relative z-10"
        >
          <div class="w-full text-center lg:w-8/12">
            <p class="text-4xl text-center">
              <span role="img" aria-label="love">
                😍
              </span>
            </p>
            <h3 class="font-semibold text-3xl">
              Do you love this Starter Kit?
            </h3>
            <p class="text-gray-600 text-lg leading-relaxed mt-4 mb-4">
              Cause if you do, it can be yours now. Hit the buttons below to
              navigate to get the Free version for your next project. Build a
              new web app or give an old project a new look!
            </p>
            <div class="sm:block flex flex-col mt-10">
              <a
                href="https://www.creative-tim.com/learning-lab/tailwind/vue/overview/notus?ref=vn-index"
                target="_blank"
                class="get-started text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-2 bg-green-500 active:bg-green-600 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
              >
                Get started
              </a>
              <a
                href="https://github.com/creativetimofficial/vue-notus?ref=vn-index"
                target="_blank"
                class="github-star sm:ml-1 text-white font-bold px-6 py-4 rounded outline-none focus:outline-none mr-1 mb-1 bg-gray-800 active:bg-gray-700 uppercase text-sm shadow hover:shadow-lg ease-linear transition-all duration-150"
              >
                <i class="fab fa-github text-lg mr-1"></i>
                <span>Help With a Star</span>
              </a>
            </div>
            <div class="text-center mt-16"></div>
          </div>
        </div>
      </div>
    </section>
    <footer-component />
  </div>
</template>
<script>
import IndexNavbar from '@/components/Navbars/IndexNavbar.vue'
import FooterComponent from '@/components/Footers/Footer.vue'

import patternVue from '@/assets/img/pattern_vue.png'
import componentBtn from '@/assets/img/component-btn.png'
import componentProfileCard from '@/assets/img/component-profile-card.png'
import componentInfoCard from '@/assets/img/component-info-card.png'
import componentInfo2 from '@/assets/img/component-info-2.png'
import componentMenu from '@/assets/img/component-menu.png'
import componentBtnPink from '@/assets/img/component-btn-pink.png'
import documentation from '@/assets/img/documentation.png'
import login from '@/assets/img/login.jpg'
import profile from '@/assets/img/profile.jpg'
import landing from '@/assets/img/landing.jpg'
import headerImg from '@/assets/img/header.png'
import team1 from '@/assets/img/zen/team-tan.png'
import team2 from '@/assets/img/zen/team-chan.png'
import team3 from '@/assets/img/zen/team-takao.png'

export default {
  data() {
    return {
      patternVue,
      componentBtn,
      componentProfileCard,
      componentInfoCard,
      componentInfo2,
      componentMenu,
      componentBtnPink,
      documentation,
      login,
      profile,
      landing,
      headerImg,
      team1,
      team2,
      team3,
    }
  },
  components: {
    IndexNavbar,
    FooterComponent,
  },
}
</script>
