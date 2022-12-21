<template>
  <div class="grid grid-cols-3 gap-4 mt-8">
    <div class="w-full col-span-2">
      <div class="mb-4">
        <h2 class="text-lg font-semibold">How Designer Made</h2>
        <p class="text-gray-500">
          Sumberkima adalah desa tepi laut di sebelah Pemuteran yang dekat
          dengan Pulau Menjangan, surga menyelam dan menyelam. Tempat ini
          memiliki pemandangan yang beragam dan budaya asli yang kaya akan
          tradisi. Di sini Anda benar - benar bisa bersantai jauh dari hiruk
          pikuk selatan.
        </p>
      </div>
    </div>
    <div class="w-full">
      <div class="mb-4">
        <div class="p-8 border">
          <!-- size button -->
          <div class="mb-4">
            <div class="flex flex-wrap">
              <div class="block w-full">
                <div class="w-32 h-10 custom-number-input">
                  <div
                    class="relative flex flex-row w-full mt-1 bg-transparent rounded-lg"
                  >
                    <button
                      data-action="decrement"
                      class="w-24 h-full text-gray-600 bg-gray-300 rounded-l outline-none cursor-pointer hover:text-gray-700 hover:bg-gray-400"
                    >
                      <span class="m-auto text-2xl font-thin">−</span>
                    </button>
                    <input
                      type="number"
                      class="flex items-center w-full font-semibold text-center text-gray-700 bg-gray-300 outline-none focus:outline-none text-md hover:text-black focus:text-black md:text-basecursor-default"
                      name="custom-input-number"
                      value="0"
                    />
                    <button
                      data-action="increment"
                      class="w-24 h-full text-gray-600 bg-gray-300 rounded-r cursor-pointer hover:text-gray-700 hover:bg-gray-400"
                    >
                      <span class="m-auto text-2xl font-thin">+</span>
                    </button>
                  </div>
                </div>
              </div>
              <div class="w-full">
                <div class="flex flex-wrap gap-2">
                  <div class="">
                    <button
                      class="w-full px-4 py-2 text-sm font-semibold text-gray-700 bg-white border border-gray-300 rounded-md hover:bg-gray-50 focus:outline-none focus-visible:ring-2 focus-visible:ring-offset-2 focus-visible:ring-blue-500"
                    >
                      S
                    </button>
                  </div>
                  <div class="">
                    <button
                      class="w-full px-4 py-2 text-sm font-semibold text-gray-700 bg-white border border-gray-300 rounded-md hover:bg-gray-50 focus:outline-none focus-visible:ring-2 focus-visible:ring-offset-2 focus-visible:ring-blue-500"
                    >
                      M
                    </button>
                  </div>
                  <div class="">
                    <button
                      class="w-full px-4 py-2 text-sm font-semibold text-gray-700 bg-white border border-gray-300 rounded-md hover:bg-gray-50 focus:outline-none focus-visible:ring-2 focus-visible:ring-offset-2 focus-visible:ring-blue-500"
                    >
                      L
                    </button>
                  </div>
                </div>
              </div>
              <!-- Add to cart button -->
              <div class="w-full mt-4">
                <button
                  class="w-full px-4 py-2 text-sm font-semibold text-white bg-blue-600 rounded-md hover:bg-blue-700 focus:outline-none focus-visible:ring-2 focus-visible:ring-offset-2 focus-visible:ring-blue-500"
                >
                  Add to cart
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
