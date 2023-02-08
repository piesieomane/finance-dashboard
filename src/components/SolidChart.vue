<script>
import { Chart as ChartJS, ArcElement, Tooltip, Legend } from "chart.js";
import { Doughnut } from "vue-chartjs";
import * as chartConfig from "./chartConfig.js";

ChartJS.register(ArcElement, Tooltip, Legend);

export default {
  //   name: "SolidChart",
  components: {
    Doughnut,
  },
  data() {
    return chartConfig;
  },
};
</script>

<template>
  <div class="flex flex-col items-center justify-between">
    <div class="flex flex-row items-center w-full justify-between">
      <h1 class="text-xl font-bold">Most Solid Items</h1>
      <button class="w-10 border-2 border-[#e2e8f0] p-2 rounded-sm">...</button>
    </div>
    <div class="flex flex-row items-center">
      <div>
        <Doughnut :data="data" :options="options" />
      </div>
      <div>
        <ul>
          <li>Jeans</li>
          <li>Shirts</li>
          <li>Caps</li>
          <li>Others</li>
        </ul>
      </div>
    </div>
  </div>
</template>
