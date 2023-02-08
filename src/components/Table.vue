<script>
export default {
  // name: Orders,
};
</script>
<template>
  <div
    class="flex flex-col w-full items-center justify-between mt-5 border-2 rounded-xl"
  >
    <div class="flex flex-row justify-between w-full items-center">
      <div class="flex flex-row justify-between w-full items-center p-6">
        <h2 class="text-xl font-bold">Latest Orders</h2>
        <div class="flex flex-row items-center justify-between">
          <p class="mr-2">Data Updates Every 3 Hours</p>
          <button class="bg-[#2563eb] p-2 rounded-lg text-white">
            View All Orders
          </button>
        </div>
      </div>
    </div>
    <div class="w-full">
      <table class="table-auto w-full text-center">
        <thead>
          <tr class="bg-[#e2e8f0] p-1">
            <th class="px-4 py-2">Product</th>
            <th class="px-4 py-2">Order ID</th>
            <th class="px-4 py-2">Date</th>
            <th class="px-4 py-2">Customer Name</th>
            <th class="px-4 py-2">Status</th>
            <th class="px-4 py-2">Amount</th>
            <th class="px-4 py-2">Action</th>
          </tr>
        </thead>
        <tbody>
          <tr class="">
            <td
              class="px-4 py-2 flex flex-row items-center justify-items-center justify-center space-x-2"
            >
              <img
                class="w-8 h-8 p-1 rounded-md ring-2 ring-gray-300 dark:ring-gray-500"
                src="./images/logo.svg"
                alt="Rounded avatar"
              />
              <p>Product 1</p>
            </td>
            <td class="px-4 py-2">#0001</td>
            <td class="px-4 py-2">01/01/2022</td>
            <td class="px-4 py-2">John Doe</td>
            <td class="px-4 py-2">Pending</td>
            <td class="px-4 py-2">$100</td>
            <td class="px-4 py-2">
              <button class="bg-blue-500 text-white py-2 px-4 rounded">
                View
              </button>
            </td>
          </tr>
          <tr class="">
            <td
              class="px-4 py-2 flex flex-row items-center justify-items-center justify-center space-x-2"
            >
              <img
                class="w-8 h-8 p-1 rounded-md ring-2 ring-gray-300 dark:ring-gray-500"
                src="./images/logo.svg"
                alt="Rounded avatar"
              />
              <p>Product 2</p>
            </td>
            <td class="px-4 py-2">#0002</td>
            <td class="px-4 py-2">02/01/2022</td>
            <td class="px-4 py-2">Jane Doe</td>
            <td class="px-4 py-2">Processing</td>
            <td class="px-4 py-2">$200</td>
            <td class="px-4 py-2">
              <button class="bg-blue-500 text-white py-2 px-4 rounded">
                View
              </button>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>
