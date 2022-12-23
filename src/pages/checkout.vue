<script setup lang="ts">
import NavigationBar from "@/components/NavigationBar.vue";
import CartPage from "@/components/CartPage.vue";
</script>

<template>
  <main>
    <NavigationBar />
    <div class="container mx-auto mb-10 checkout-page">
      <div class="grid grid-cols-2">
        <div>
          <h2 class="mb-10 text-3xl font-bold">Buyer Information</h2>
          <div class="space-y-2">
            <input
              type="text"
              class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-3/4 p-2.5"
              placeholder="Full Name"
              required
            />
            <input
              type="text"
              class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-3/4 p-2.5"
              placeholder="Address"
              required
            />
            <input
              type="text"
              class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-3/4 p-2.5"
              placeholder="City"
              required
            />

            <input
              type="text"
              class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-blue-500 focus:border-blue-500 block w-3/4 p-2.5"
              placeholder="Post Code"
              required
            />
          </div>
        </div>
        <div>
          <h2 class="mb-10 text-3xl font-bold">Payment Details</h2>
          <table class="w-3/4">
            <tr>
              <td>Total items</td>
              <td>$18.000</td>
            </tr>
            <tr>
              <td>TAX</td>
              <td>$201</td>
            </tr>
            <tr>
              <td>Shipping</td>
              <td>$800</td>
            </tr>
            <tr>
              <td>Grand Total</td>
              <td>$34.000</td>
            </tr>
            <tr>
              <td colspan="2">
                <!-- checkout button -->
                <button
                  class="w-1/2 px-4 py-2 mt-8 text-sm font-medium leading-5 text-white transition-colors duration-150 bg-blue-600 border border-transparent rounded-lg active:bg-blue-600 hover:bg-blue-700 focus:outline-none focus:shadow-outline-blue"
                >
                  Pay Now
                </button>
              </td>
            </tr>
          </table>
        </div>
      </div>
    </div>
  </main>
</template>
