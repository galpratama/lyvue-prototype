<template>
  <div class="container mx-auto mb-10">
    <div class="mx-4 mb-8 lg:container lg:mx-auto">
      <h2 class="mb-10 text-3xl font-bold">Shopping Item</h2>
      <div class="w-full mx-auto bg-white">
        <div class="p-3 overflow-x-auto">
          <table class="w-full table-auto">
            <tbody class="text-sm divide-y divide-gray-100">
              <!-- record 1 -->
              <tr v-for="i in 6">
                <td class="w-24 p-2">
                  <img
                    src="https://place-hold.it/800x600"
                    alt="Dino Jacket Outfit"
                    class="w-24"
                  />
                </td>
                <td class="p-2">
                  <div class="font-medium text-gray-800">
                    Dino Jacket Outfit Masa Holiday
                  </div>
                </td>
                <td class="p-2">
                  <div class="text-left">1</div>
                </td>
                <td class="p-2">
                  <div class="font-medium text-left text-gray-500">
                    $2,890.66
                  </div>
                </td>
                <td class="p-2">
                  <div class="flex justify-center">
                    <button>
                      <svg
                        class="w-8 h-8 p-1 rounded-full hover:text-gray-600 hover:bg-gray-100"
                        fill="none"
                        stroke="currentColor"
                        viewBox="0 0 24 24"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M19 7l-.867 12.142A2 2 0 0116.138 21H7.862a2 2 0 01-1.995-1.858L5 7m5 4v6m4-6v6m1-10V4a1 1 0 00-1-1h-4a1 1 0 00-1 1v3M4 7h16"
                        ></path>
                      </svg>
                    </button>
                  </div>
                </td>
              </tr>
            </tbody>
          </table>
        </div>

        <!-- total amount -->
        <div
          class="flex justify-end px-5 py-4 space-x-4 text-2xl font-bold border-t border-gray-100"
        >
          <div>Total</div>
          <div class="text-gray-600">$20,000</div>
        </div>
      </div>
    </div>
    <!-- Checkout button -->
    <div class="flex justify-end">
      <button
        class="px-8 py-3 text-lg font-semibold text-white bg-gray-600 rounded-lg shadow-md hover:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-gray-600 focus:ring-opacity-50"
      >
        Proceed to Checkout
      </button>
    </div>
  </div>
</template>
