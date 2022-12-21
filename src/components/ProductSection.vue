<template>
  <section class="product">
    <div class="mx-4 mb-8 lg:container lg:mx-auto">
      <h2 class="text-3xl font-bold">Just Coming This Month</h2>

      <ul
        class="flex flex-wrap mt-4 text-sm font-medium text-center text-gray-500 dark:text-gray-400"
      >
        <li class="mr-2">
          <a
            href="#"
            class="inline-block px-4 py-3 text-white bg-gray-600 rounded-lg active"
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
    <div
      class="grid grid-cols-1 gap-4 mx-4 lg:container lg:mx-auto lg:grid-cols-4"
    >
      <div v-for="item in 4" :key="item" class="w-full">
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
</template>
