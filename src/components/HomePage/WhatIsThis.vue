<template>
  <section class="dark:bg-gray-900 bg-zinc-900">
    <div class="max-w-screen-lg mx-auto py-10 px-4">
      <h1
        class="mb-10 text-xl font-light tracking-tight leading-none text-gray-100 md:text-2xl lg:text-3xl dark:text-white text-center"
      >
        What is this?
      </h1>
      <h1
        class="mb-4 text-sm font-medium tracking-tight leading-none text-gray-100 md:text-base lg:text-lg dark:text-white"
      >
        What is <span class="text-[#ff2d20]">Lara</span
        ><span class="text-[#41b883]">Vue</span
        ><span class="text-[#38bdf8]">Tail</span> ?
      </h1>
      <p
        class="mb-2 text-sm font-light tracking-tight text-gray-100 md:text-sm lg:text-sm dark:text-white"
      >
        LaraVueTail is a library of Open source(MIT) web applications built with
        Laravel, Vue and Tailwind CSS.
      </p>
      <p
        class="mb-2 text-sm font-light tracking-tight text-gray-100 md:text-sm lg:text-sm dark:text-white"
      >
        We have carefully harnessed the power of Laravel's robust backend
        capabilities, combined it with the dynamic frontend functionality of
        Vue.js, and embraced the modern design philosophy of Tailwind CSS. The
        result is a library that empowers developers to harness the full
        potential of these technologies effortlessly.
      </p>

      <div class="flex items-center space-x-4 mb-5">
        <img
          class="w-14 h-14 rounded-full"
          :src="$route.meta.siteUrl + '/assets/ameer.jpg'"
          alt=""
        />
        <div class="font-medium text-gray-200 text-sm">
          <div>C Ameerali</div>
          <p class="text-sm text-gray-300 font-light">
            Full-Stack Developer, <br />Creator of
            <span class="text-[#ff2d20]">Lara</span
            ><span class="text-[#41b883]">Vue</span
            ><span class="text-[#38bdf8]">Tail</span>
          </p>
          <a
            href="https://ameer.website"
            target="_blank"
            class="text-xs text-gray-300 font-light flex gap-1 items-center hover:underline hover:text-vue"
            ><svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-3 h-3"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M12 21a9.004 9.004 0 008.716-6.747M12 21a9.004 9.004 0 01-8.716-6.747M12 21c2.485 0 4.5-4.03 4.5-9S14.485 3 12 3m0 18c-2.485 0-4.5-4.03-4.5-9S9.515 3 12 3m0 0a8.997 8.997 0 017.843 4.582M12 3a8.997 8.997 0 00-7.843 4.582m15.686 0A11.953 11.953 0 0112 10.5c-2.998 0-5.74-1.1-7.843-2.918m15.686 0A8.959 8.959 0 0121 12c0 .778-.099 1.533-.284 2.253m0 0A17.919 17.919 0 0112 16.5c-3.162 0-6.133-.815-8.716-2.247m0 0A9.015 9.015 0 013 12c0-1.605.42-3.113 1.157-4.418"
              />
            </svg>
            ameer.website</a
          >
        </div>
      </div>

      <p
        class="mb-2 text-sm font-medium tracking-tight text-vue hover:text-tailwind md:text-sm lg:text-sm dark:text-white hover:underline"
      >
        <a href="http://laravuetail.com" target="_blank">
          Visit: laravuetail.com
        </a>
      </p>
      <p
        class="mb-10 text-sm font-medium tracking-tight text-gray-100 md:text-sm lg:text-sm dark:text-white"
      >
        Current Projects (Last Updated: 14/06/2023):
      </p>
      <div
        class="grid grid-cols-2 md:grid-cols-6 mb-10 place-content-center w-fit mx-auto gap-10"
      >
      <a
          href="http://openai.laravuetail.com"
          target="_blank"
          class="grid place-content-center justify-items-center text-sm md:text-sm font-medium text-gray-100 rounded-2xl w-32 h-32 border border-[#41b883]/10 hover:bg-black/50 hover:shadow-[#38bdf8] hover:border-[#38bdf8] hover:border-2 shadow-lg hover:shadow-xl shadow-[#41b883] bg-black/30"
        >
          <img
            class="w-10 h-10 mr-2"
            :src="$route.meta.siteUrl + '/assets/logos/lvt-openai-logo.svg'"
            alt="logo"
          />
          LVTOpenAI
          <p class="text-xs font-light">OpenAI</p>
        </a>
        <a
          href="http://lms.laravuetail.com"
          target="_blank"
          class="grid place-content-center justify-items-center text-sm md:text-sm font-medium text-gray-100 rounded-2xl w-32 h-32 border border-[#41b883]/10 hover:bg-black/50 hover:shadow-[#38bdf8] hover:border-[#38bdf8] hover:border-2 shadow-lg hover:shadow-xl shadow-[#41b883] bg-black/30"
        >
          <img
            class="w-10 h-10 mr-2"
            :src="$route.meta.siteUrl + '/assets/logos/lvt-lms-logo.svg'"
            alt="logo"
          />
          LVTLearn
          <p class="text-xs font-light">LMS</p>
        </a>
        <a
          href="http://ecommerce.laravuetail.com"
          target="_blank"
          class="grid place-content-center justify-items-center text-sm md:text-sm font-medium text-gray-100 rounded-2xl w-32 h-32 border border-[#41b883]/10 hover:bg-black/50 hover:shadow-[#38bdf8] hover:border-[#38bdf8] hover:border-2 shadow-lg hover:shadow-xl shadow-[#41b883] bg-black/30"
        >
          <img
            class="w-10 h-10 mr-2"
            :src="$route.meta.siteUrl + '/assets/logos/lvt-ecommerce-logo.svg'"
            alt="logo"
          />
          LVTShop
          <p class="text-xs font-light">ecommerce</p>
        </a>
        
        <a
          href="http://blog.laravuetail.com"
          target="_blank"
          class="grid place-content-center justify-items-center text-sm md:text-sm font-medium text-gray-100 rounded-2xl w-32 h-32 border border-[#41b883]/10 hover:bg-black/50 hover:shadow-[#38bdf8] hover:border-[#38bdf8] hover:border-2 shadow-lg hover:shadow-xl shadow-[#41b883] bg-black/30"
        >
          <img
            class="w-10 h-10 mr-2"
            :src="$route.meta.siteUrl + '/assets/logos/lvt-blog-logo.svg'"
            alt="logo"
          />
          LVTBlog
          <p class="text-xs font-light">blog</p>
        </a>
        <a
          href="http://cms.laravuetail.com"
          target="_blank"
          class="grid place-content-center justify-items-center text-sm md:text-sm font-medium text-gray-100 rounded-2xl w-32 h-32 border border-[#41b883]/10 hover:bg-black/50 hover:shadow-[#38bdf8] hover:border-[#38bdf8] hover:border-2 shadow-lg hover:shadow-xl shadow-[#41b883] bg-black/30"
        >
          <img
            class="w-10 h-10 mr-2"
            :src="$route.meta.siteUrl + '/assets/logos/lvt-cms-logo.svg'"
            alt="logo"
          />
          LVTCMS Tools
          <p class="text-xs font-light">CMS</p>
        </a>
        <a
          href="http://dashboard.laravuetail.com"
          target="_blank"
          class="grid place-content-center justify-items-center text-sm md:text-sm font-medium text-gray-100 rounded-2xl w-32 h-32 border border-[#41b883]/10 hover:bg-black/50 hover:shadow-[#38bdf8] hover:border-[#38bdf8] hover:border-2 shadow-lg hover:shadow-xl shadow-[#41b883] bg-black/30"
        >
          <img
            class="w-10 h-10 mr-2"
            :src="$route.meta.siteUrl + '/assets/logos/lvt-dashboard-logo.svg'"
            alt="logo"
          />
          LVTDashboard
          <p class="text-xs font-light">Dashboard</p>
        </a>
      </div>
      <div class="grid md:grid-cols-2 gap-2 md:gap-10">
        <div>
          <h1
            class="mb-4 text-sm font-medium tracking-tight leading-none text-gray-100 md:text-base lg:text-lg dark:text-white"
          >
            What is OpenAI
          </h1>
          <p
            class="mb-2 text-sm font-light tracking-tight text-gray-100 md:text-sm lg:text-sm dark:text-white"
          >
            OpenAI is an artificial intelligence research organization at the
            forefront of AI development. It aims to ensure that artificial
            general intelligence (AGI) benefits all of humanity. Established in
            2015, OpenAI has contributed significantly to natural language
            processing advancements, creating powerful language models like
            GPT-3, capable of understanding and generating human-like text. It
            fosters an open-source approach, publishing research and tools to
            promote collaboration and accessibility in the AI community.
            OpenAI's innovative technologies have applications in various
            fields, from chatbots and language translation to creative writing
            and problem-solving, paving the way for transformative AI-driven
            solutions in the future.

            This is OpenAI in OpenAI's terms.
          </p>
        </div>
        <div class="place-self-center">
          <div class="rounded-lg shadow-xl w-56 md:w-96 mx-auto">
            <img
              class="object-cover h-full w-full shadow-xl rounded-lg opacity-80"
              :src="$route.meta.siteUrl + '/assets/openai-image.jpg'"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script></script>
