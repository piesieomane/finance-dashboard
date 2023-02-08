<script>
export default {
  props: [
    "title",
    "price",
    "message",
    "color",
    "percentage",
    "percentagewheel",
  ],
  data(props) {
    //console.log("DDDDDD", props.percentagewheel, props.percentage, props.title);
    return { props };
  },
};
</script>
<template>
  <div
    class="flex flex-row items-center justify-between border-spacing-1 border-2 rounded-3xl p-4"
  >
    <div class="flex flex-col">
      <h4 class="font-bold">{{ title }}</h4>
      <h1 class="text-3xl font-extrabold">{{ props.price }}</h1>
      <p>{{ props.message }}</p>
    </div>
    <div>
      <div class="relative h-32 w-32 mx-auto">
        <svg class="absolute top-0 left-0" viewBox="0 0 100 100">
          <circle
            cx="50"
            cy="50"
            r="40"
            fill="transparent"
            stroke="#e2e8f0"
            stroke-width="5 "
          />
          <circle
            cx="50"
            cy="50"
            r="40"
            fill="transparent"
            :stroke="props.color"
            stroke-width="4"
            stroke-dasharray="282.74"
            :stroke-dashoffset="props.percentagewheel"
          />
        </svg>
        <div
          class="absolute top-0 left-0 h-full w-full flex items-center justify-center"
        >
          <div class="text-3xl text-center text-black-500">
            {{ props.percentage }}
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
