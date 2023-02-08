<script>
import Hi from "../components/Hi.vue";
import RevenueVue from "../components/Revenue.vue";
export default {
  components: {
    Hi,
    RevenueVue,
  },
  data() {
    return {
      items: [
        {
          post: {
            id: 1,
            title: "Todays Sales",
            price: "$20.4k",
            message: "We have sold 123 items",
            color: "#2563eb",
          },
        },
        {
          post: {
            id: 1,
            title: "Todays Revenue",
            price: "$8.2k",
            message: "Available to payout",
            color: "#65a30d",
          },
        },
        {
          post: {
            id: 1,
            title: "In Escrow",
            price: "$18.2k",
            message: "Available to payout",
            color: "#f97316",
          },
        },
      ],
    };
  },
};
</script>
<template>
  <div class="p-6 flex flex-col">
    <div class="flex flex-row justify-between">
      <div class="w-[30%]">
        <Hi
          :title="items[0].post.title"
          :price="items[0].post.price"
          :message="items[0].post.message"
          :color="items[0].post.color"
        />
      </div>
      <div class="w-[30%]">
        <Hi
          :title="items[1].post.title"
          :price="items[1].post.price"
          :message="items[1].post.message"
          :color="items[1].post.color"
        />
      </div>
      <div class="w-[30%]">
        <Hi
          :title="items[2].post.title"
          :price="items[2].post.price"
          :message="items[2].post.message"
          :color="items[2].post.color"
        />
      </div>
    </div>
    <div class="flex flex-row items-center justify-between mt-6">
      <div
        class="w-[60%] border-spacing-1 border-2 border-slate-800 rounded-3xl p-4"
      >
        <div class="flex flex-row justify-between">
          <h2 class="text-xl font-bold">Total Revenue</h2>
          <div class="flex flex-row items-center justify-between">
            <p class="mr-2">Data Updates Every 3 Hours</p>
            <button class="bg-[#e2e8f0] p-2 rounded-sm">View All Orders</button>
          </div>
        </div>
        <div class="flex flex-row w-[30%] justify-between items-center">
          <h1 class="text-2xl font-semibold">$50.4k</h1>
          <p class="text-[#65a30d]">8% than last month <span>&#8593</span></p>
        </div>
        <RevenueVue />
      </div>
      <div class="'w-[30%]'"><p>lorem10</p></div>
    </div>
  </div>
</template>

exp
