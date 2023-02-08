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
          <tr class="bg-gray-800 text-white">
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
          <tr class="bg-gray-100">
            <td class="border px-4 py-2">Product 1</td>
            <td class="border px-4 py-2">#0001</td>
            <td class="border px-4 py-2">01/01/2022</td>
            <td class="border px-4 py-2">John Doe</td>
            <td class="border px-4 py-2">Pending</td>
            <td class="border px-4 py-2">$100</td>
            <td class="border px-4 py-2">
              <button class="bg-blue-500 text-white py-2 px-4 rounded">
                View
              </button>
            </td>
          </tr>
          <tr class="bg-gray-100">
            <td class="border px-4 py-2">Product 2</td>
            <td class="border px-4 py-2">#0002</td>
            <td class="border px-4 py-2">02/01/2022</td>
            <td class="border px-4 py-2">Jane Doe</td>
            <td class="border px-4 py-2">Processing</td>
            <td class="border px-4 py-2">$200</td>
            <td class="border px-4 py-2">
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
