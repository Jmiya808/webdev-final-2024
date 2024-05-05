<template>
  <header class="flex items-center justify-between py-4 px-6 bg-slate-900">
    <nuxt-link to="/" class=" text-center text-lg font-bold sm:w-fit sm:text-left">
        <span class="text-slate-100 text-2xl">JM</span>
        <span class="dark:text-yellow-500 text-sm">studios</span>
    </nuxt-link>
    <nav class="hidden  text-base sm:block">
      <ul class="flex items-center space-x-2 gap-4">
        <li class="group relative">
          <nuxt-link to="/pricing"
            class="block whitespace-nowrap px-3 py-2 text-sm font-semibold text-grey-400 no-underline transition text-white hover:text-slate-900 dark:hover:text-slate-50"
            href="/">
            Pricing
          </nuxt-link>
        </li>
        <li class="group relative">
          <a
            class="block whitespace-nowrap px-3 py-2 text-sm font-semibold text-white no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
            href="#"
          >
            Portfolio
          </a>
          <ul
            class="invisible absolute z-30 space-y-2 rounded-lg border border-slate-50 bg-white p-4 opacity-0 shadow-xl transition-opacity delay-75 ease-in-out group-hover:visible group-hover:opacity-100 dark:border-great-blue-500 dark:bg-great-blue-500"
          >
            <li>
              <a
                class="undefined block whitespace-nowrap px-3 py-2 text-sm font-semibold text-white transition hover:text-slate-900 hover:underline dark:hover:text-slate-50"
                href="https://www.youtube.com/watch?v=DgLVDiyOVc8&list=PLNgGpdynUv7xF2VdDIL3EwSPDkNZ7XdWy&index=2"
              >
                Wedding
              </a>
            </li>
            <li>
              <a
                class="undefined block whitespace-nowrap px-3 py-2 text-sm font-semibold text-white transition hover:text-slate-900 hover:underline dark:hover:text-slate-50"
                href="https://www.youtube.com/watch?v=MV-Yay3rg1g&list=PLNgGpdynUv7yf5miTqAr6w7t4TZEq2rsB&index=2"
              >
                Music Video
              </a>
            </li>
            <li>
              <a
                class="undefined block whitespace-nowrap px-3 py-2 text-sm font-semibold text-white transition hover:text-slate-900 hover:underline dark:hover:text-slate-50"
                href="https://www.youtube.com/watch?v=iR48O2T36qc"
              >
                Social Media Awareness
              </a>
            </li>
          </ul>
        </li>
        <li class="group relative">
          <nuxt-link to="/about"
            class="block whitespace-nowrap px-3 py-2 text-sm font-semibold text-white no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
            href="/about"
            >
            About
        </nuxt-link>
        </li>
        <li class="group relative">
          <nuxt-link to="/book"
            class="block whitespace-nowrap px-3 py-2 text-sm font-semibold text-white no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
            href="/contact"
          >
            Book
          </nuxt-link>
        </li>
      </ul>
    </nav>
    <button
      class="block text-slate-400 hover:text-slate-900 dark:hover:text-slate-50 sm:hidden"
      title="Open navigation menu"
    >
      <svg
        preserveAspectRatio="xMidYMid meet"
        viewBox="0 0 24 24"
        width="1.2em"
        height="1.2em"
      >
        <path
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          d="M4 6h16M4 12h16M4 18h16"
        ></path>
      </svg>
    </button>
    <nav
      class="fixed -right-1/2 top-0 z-20 h-full w-1/2 transform overflow-y-auto bg-white py-4 text-base transition dark:bg-slate-900 sm:hidden"
    >
      <ul class="flex flex-col space-y-2">
        <li class="text-right">
          <button
            class="px-6 py-2 text-slate-400 hover:text-slate-900 dark:hover:text-slate-50"
          >
            <svg
              preserveAspectRatio="xMidYMid meet"
              viewBox="0 0 24 24"
              width="1.2em"
              height="1.2em"
            >
              <path
                fill="none"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="2"
                d="M5 12h14m-4 4l4-4m-4-4l4 4"
              ></path>
            </svg>
          </button>
        </li>
        <li class="group relative w-full overflow-x-visible text-right">
          <a
            class="mx-4 block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
            href="/"
          >
            Home
          </a>
        </li>
        <li class="group relative w-full overflow-x-visible text-right">
          <a
            class="mx-4 block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
            href="#"
          >
            Services
          </a>
          <ul
            class="h-0 space-y-2 overflow-y-hidden bg-slate-50 px-4 py-0 transition-all delay-75 ease-in-out group-hover:h-full group-hover:py-4 dark:bg-slate-800"
          >
            <li>
              <a
                class="undefined block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
                href="/services/web-development"
              >
                Web development
              </a>
            </li>
            <li>
              <a
                class="undefined block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
                href="/services/digital-marketing"
              >
                Digital marketing
              </a>
            </li>
            <li>
              <a
                class="undefined block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
                href="/services/brand-strategy"
              >
                Brand strategy
              </a>
            </li>
          </ul>
        </li>
        <li class="group relative w-full overflow-x-visible text-right">
          <a
            class="mx-4 block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-400 no-underline transition hover:text-slate-900 dark:hover:text-slate-50"
            href="/about"
          >
            About
          </a>
        </li>
        <li class="group relative w-full overflow-x-visible text-right">
          <a
            class="mx-4 block whitespace-nowrap px-3 py-2 text-sm font-semibold text-slate-900 no-underline transition hover:text-slate-900 dark:text-slate-50 dark:hover:text-slate-50"
            href="/contact"
          >
            Contact
          </a>
        </li>
      </ul>
    </nav>
  </header>
</template>