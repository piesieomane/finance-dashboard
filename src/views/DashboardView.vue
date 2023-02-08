<script>
import Hi from "../components/Hi.vue";
export default {
  components: {
    Hi,
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
  <div class="p-6">
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
  </div>
</template>

exp
