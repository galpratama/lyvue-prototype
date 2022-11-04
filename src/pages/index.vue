<script setup lang="ts"></script>

<template>
  <main>
    <nav
      class="bg-white px-2 sm:px-4 py-2.5 fixed w-full z-20 top-0 left-0 border-b border-gray-200"
    >
      <div
        class="container flex flex-wrap items-center justify-between mx-auto"
      >
        <a href="https://flowbite.com/" class="flex items-center">
          <span class="self-center text-xl font-semibold whitespace-nowrap"
            >Lavye</span
          >
        </a>
        <div class="flex md:order-2">
          <span
            class="self-center mr-4 text-xl font-semibold whitespace-nowrap"
          >
            🛒</span
          >
          <button
            type="button"
            class="text-white bg-purple-700 hover:bg-purple-800 focus:ring-4 focus:outline-none focus:ring-purple-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center mr-3 md:mr-0"
          >
            Sign In
          </button>
          <button
            data-collapse-toggle="navbar-sticky"
            type="button"
            class="inline-flex items-center p-2 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200"
            aria-controls="navbar-sticky"
            aria-expanded="false"
          >
            <span class="sr-only">Open main menu</span>
            <svg
              class="w-6 h-6"
              aria-hidden="true"
              fill="currentColor"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
                clip-rule="evenodd"
              ></path>
            </svg>
          </button>
        </div>
        <div
          class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1"
          id="navbar-sticky"
        >
          <ul
            class="flex flex-col p-4 mt-4 border border-gray-100 rounded-lg bg-gray-50 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium md:border-0 md:bg-white"
          >
            <li>
              <a
                href="#"
                class="block py-2 pl-3 pr-4 text-white bg-purple-700 rounded md:bg-transparent md:text-purple-700 md:p-0"
                aria-current="page"
                >Featured</a
              >
            </li>
            <li>
              <a
                href="#"
                class="block py-2 pl-3 pr-4 text-gray-700 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-purple-700 md:p-0"
                >Categories</a
              >
            </li>
            <li>
              <a
                href="#"
                class="block py-2 pl-3 pr-4 text-gray-700 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-purple-700 md:p-0"
                >Sale</a
              >
            </li>
            <li>
              <a
                href="#"
                class="block py-2 pl-3 pr-4 text-gray-700 rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-purple-700 md:p-0"
                >Designers</a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <section class="mt-20 bg-white">
      <div
        class="max-w-screen-xl px-4 py-8 mx-auto text-center lg:py-16 lg:px-12"
      >
        <h1
          class="mb-4 text-4xl font-extrabold leading-none tracking-tight text-gray-900 md:text-5xl lg:text-6xl"
        >
          Your Kid Deserve <br />Better Clothing
        </h1>
        <p
          class="mb-8 text-lg font-normal text-gray-500 lg:text-xl sm:px-16 xl:px-48"
        >
          Not only covering their body up but to <br />show up everyday who are
          they and meant to be
        </p>
        <div
          class="flex flex-col mb-8 space-y-4 lg:mb-16 sm:flex-row sm:justify-center sm:space-y-0 sm:space-x-4"
        >
          <a
            href="#"
            class="inline-flex items-center justify-center px-5 py-3 text-base font-medium text-center text-white bg-purple-600 rounded-lg bg-primary-700 hover:bg-primary-800 focus:ring-4 focus:ring-primary-300"
          >
            Start Browsing
          </a>
        </div>
      </div>
    </section>
    <section class="product">
      <div class="container mx-auto mb-8">
        <h2 class="text-3xl font-bold">Just Coming This Month</h2>

        <ul
          class="flex flex-wrap mt-4 text-sm font-medium text-center text-gray-500 dark:text-gray-400"
        >
          <li class="mr-2">
            <a
              href="#"
              class="inline-block px-4 py-3 text-white bg-purple-600 rounded-lg active"
              aria-current="page"
              >Daily Wear</a
            >
          </li>
          <li class="mr-2">
            <a
              href="#"
              class="inline-block px-4 py-3 rounded-lg hover:text-gray-900 hover:bg-gray-100 dark:hover:bg-gray-800 dark:hover:text-white"
              >Swimming</a
            >
          </li>
          <li class="mr-2">
            <a
              href="#"
              class="inline-block px-4 py-3 rounded-lg hover:text-gray-900 hover:bg-gray-100 dark:hover:bg-gray-800 dark:hover:text-white"
              >Hiking</a
            >
          </li>
          <li>
            <a
              class="inline-block px-4 py-3 rounded-lg hover:text-gray-900 hover:bg-gray-100 dark:hover:bg-gray-800 dark:hover:text-white"
              >Party</a
            >
          </li>
        </ul>
      </div>
      <div class="container grid grid-cols-4 gap-4 mx-auto">
        <div v-for="item in 4" :key="item" class="w-full max-w-sm">
          <div class="bg-gray-300 rounded-t h-72"></div>
          <div class="pb-5">
            <div class="flex flex-row">
              <div>
                <a href="#">
                  <h5
                    class="pt-2 text-xl font-semibold tracking-tight text-gray-900"
                  >
                    Kaos Kaki
                  </h5>
                  <span class="text-xl font-bold text-gray-900">$599</span>
                </a>
              </div>
              <div class="flex flex-row mt-10 mb-5 ml-auto">
                <svg
                  aria-hidden="true"
                  class="w-5 h-5 text-yellow-300"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <title>First star</title>
                  <path
                    d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z"
                  ></path>
                </svg>
                <span class="mr-2 font-semibold"> 5.0</span>
              </div>
              <div class="flex items-center justify-between"></div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="mb-24 product">
      <div class="container mx-auto mt-10 mb-8">
        <h2 class="text-3xl font-bold text-center">Explore Our Creative</h2>
      </div>
      <div class="container grid grid-cols-4 gap-4 mx-auto">
        <div class="col-span-2 p-8 text-lg bg-gray-400 h-96">Category</div>
        <div class="col-span-1 p-8 text-lg bg-gray-400 h-96">Category</div>
        <div class="grid grid-cols-1 col-span-1 gap-4">
          <div class="p-8 text-lg bg-gray-400 h-[45]">Category</div>
          <div class="p-8 text-lg bg-gray-400 h-[45]">Category</div>
        </div>
      </div>
    </section>
  </main>
</template>
