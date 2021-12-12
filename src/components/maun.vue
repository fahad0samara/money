<template>
  <div class="bg-gray-300">
    <!-- this div for first div -->
    <div class="py-12">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="lg:text-center">
          <h2 class="text-base text-indigo-600 font-semibold tracking-wide uppercase focus">Transactions</h2>
          <p
            class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl"
          >A better way to send money</p>
          <p class="mt-4 max-w-2xl text-2xl text-indigo-700 lg:mx-auto font-extrabold">
            fish problem table notice satisfied shop trade program wash everyone
            certainly magnet nest source electric known yellow rubbed ball
            higher pretty value look goose
          </p>
        </div>
      </div>
    </div>
    <!-- this div for scand div -->
    <div
      class="grid grid-cols-1 sm:grid sm:grid-cols-1 md:mt-10 md:grid md:grid-cols-2 gap-x-12 gap-y-11 ml-10"
    >
      <div v-for="namefor in nametext" :key="namefor.name">
        <h1 class="text-3xl text-indigo-600">{{ namefor.name }}</h1>
        <p
          class="mt-3 max-w-1xl text-xl text-gray-900 font-bold leading-6 filter drop-shadow-lg"
        >{{ namefor.duscrpion }}</p>
        <button
          class="inline-flex items-center h-10 px-5 text-indigo-100 transition-colors duration-150 bg-indigo-700 rounded-lg focus:shadow-outline hover:bg-indigo-800 mb-9"
        >
          <span>more....</span>
          <svg
            xmlns="http://www.w3.org/2000/svg"
 
            class="h-6 w-6"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M15 15l-2 5L9 9l11 4-5 2zm0 0l5 5M7.188 2.239l.777 2.897M5.136 7.965l-2.898-.777M13.95 4.05l-2.122 2.122m-5.657 5.656l-2.12 2.122"
            />
          </svg>
        </button>
      </div>
    </div>

    <!-- this is acrol for the elmant an dhe we start -->
  </div>
  <nav class="flex justify-center mb-11 mt-9">
    <ul class="inline-flex space-x-2">
      <li>
        <button
          class="flex items-center justify-center w-12 h-12 text-indigo-600 transition-colors duration-150 rounded-full focus:shadow-outline hover:bg-indigo-100"
        >
          <svg class="w-12 h-12 fill-current " viewBox="0 0 20 20">
            <path
              d="M12.707 5.293a1 1 0 010 1.414L9.414 10l3.293 3.293a1 1 0 01-1.414 1.414l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 0z"
              clip-rule="evenodd"
              fill-rule="evenodd"
            />
          </svg>
        </button>
      </li>
      <li>
        <button
          class="w-12 h-12 text-indigo-600 transition-colors duration-150 rounded-full focus:shadow-outline hover:bg-indigo-100"
        >1</button>
      </li>
      <li>
        <button
          class="w-12 h-12 text-indigo-600 transition-colors duration-150 rounded-full focus:shadow-outline hover:bg-indigo-100"
        >2</button>
      </li>
      <li>
        <button
          class="w-12 h-12 text-white transition-colors duration-150 bg-indigo-600 border border-r-0 border-indigo-600 rounded-full focus:shadow-outline"
        >3</button>
      </li>
      <li>
        <button
          class="flex items-center justify-center w-12 h-12 text-indigo-600 transition-colors duration-150 bg-white rounded-full focus:shadow-outline hover:bg-indigo-100"
        >
          <svg class="w-12 h-12 fill-current" viewBox="0 0 20 20">
            <path
              d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z"
              clip-rule="evenodd"
              fill-rule="evenodd"
            />
          </svg>
        </button>
      </li>
    </ul>
  </nav>
  <!-- her start footer -->

  <footer class="text-gray-600 body-font bg-indigo-700">
    <div
      class="container mx-auto flex flex-wrap p-4 flex-col md:flex-row items-center justify-between"
    >
      <div class="text-indigo-50 flex items-center space-x-2">
        <span class="text-indigo-50 font-black">money</span>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-5 w-5"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
          />
        </svg>
      </div>

      <p class="text-sm max-w-1xl text-indigo-100 sm:border-gray-200 sm:py-2 sm:mt-0">© 2021 fahad</p>

      <span
        class="inline-flex sm:ml-auto sm:mt-0 mt-4 justify-center sm:justify-start text-indigo-100"
      >
        <a>
          <svg
            fill="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            class="w-5 h-5"
            viewBox="0 0 24 24"
          >
            <path d="M18 2h-3a5 5 0 00-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 011-1h3z" />
          </svg>
        </a>
        <a class="ml-3 text-purple-100">
          <svg
            fill="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            class="w-5 h-5"
            viewBox="0 0 24 24"
          >
            <path
              d="M23 3a10.9 10.9 0 01-3.14 1.53 4.48 4.48 0 00-7.86 3v1A10.66 10.66 0 013 4s-4 9 5 13a11.64 11.64 0 01-7 2c9 5 20 0 20-11.5a4.5 4.5 0 00-.08-.83A7.72 7.72 0 0023 3z"
            />
          </svg>
        </a>
        <a class="ml-2 text-purple-100">
          <svg
            fill="none"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            class="w-5 h-5"
            viewBox="0 0 24 24"
          >
            <rect width="20" height="20" x="2" y="2" rx="5" ry="5" />
            <path d="M16 11.37A4 4 0 1112.63 8 4 4 0 0116 11.37zm1.5-4.87h.01" />
          </svg>
        </a>
        <a class="ml-3 text-purple-100">
          <svg
            fill="currentColor"
            stroke="currentColor"
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="0"
            class="w-5 h-5"
            viewBox="0 0 24 24"
          >
            <path
              stroke="none"
              d="M16 8a6 6 0 016 6v7h-4v-7a2 2 0 00-2-2 2 2 0 00-2 2v7h-4v-7a6 6 0 016-6zM2 9h4v12H2z"
            />
            <circle cx="4" cy="4" r="2" stroke="none" />
          </svg>
        </a>
      </span>
    </div>
  </footer>
</template>
<script>
const nametext = [
  {
    name: "Competitive exchange rates",
    duscrpion:
      "symbol actual wall coming lower location or especially ball camp poor swing few pupil population wooden me trade piano either here about fell every",
  },
  {
    name: "Transfers are instant",
    duscrpion:
      "ranch between draw likely property over becoming gasoline bag crew steel influence base rear asleep previous combination hall seeing blanket burn planet transportation stuck",
  },
  {
    name: "No hidden fees",
    duscrpion:
      "part free gas whose if division frame below century news slip nearly light require opportunity pride well each sugar government oil nature according sentence",
  },
  {
    name: "Mobile notifications",
    duscrpion:
      "partly exactly wide here except they flight bank parallel soldier catch warm mathematics man guide inside shirt help pink familiar instrument independent fort equipment",
  },
];

export default {
  setup() {
    return {
      nametext,
    };
  },
};
</script>

<style>
.flip {
	animation: flip-2-hor-top-1 2s cubic-bezier(0.455, 0.030, 0.515, 0.955) infinite both;
}
@keyframes flip-2-hor-top-1 {
  0% {
    transform: translateY(0) rotateX(0);
    transform-origin: 50% 0%;
  }
  100% {
    transform: translateY(-100%) rotateX(-180deg);
    transform-origin: 50% 100%;
  }
}
.focus {
	animation: focus-in-contract 3s cubic-bezier(0.250, 0.460, 0.450, 0.940) 2s infinite both;
}
@keyframes focus-in-contract {
  0% {
    letter-spacing: 1em;
    filter: blur(12px);
    opacity: 0;
  }
  100% {
    filter: blur(0px);
    opacity: 1;
  }
}


</style>