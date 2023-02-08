<script>
import {
  Chart as ChartJS,
  Title,
  Tooltip,
  Legend,
  BarElement,
  CategoryScale,
  LinearScale,
} from "chart.js";
import { Bar } from "vue-chartjs";

ChartJS.register(
  CategoryScale,
  LinearScale,
  BarElement,
  Title,
  Tooltip,
  Legend
);

export default {
  components: {
    Bar,
  },
  data() {
    return {
      data: {
        labels: [
          "January",
          "February",
          "March",
          "April",
          "May",
          "June",
          "July",
          "August",
          "September",
        ],
        datasets: [
          {
            data: [20, 40, 60, 50, 30, 80, 30, 70, 30],
            barThickness: 6,
            backgroundColor: "#2563eb",
            hoverBackgroundColor: "#65a30d",
            barThickness: "30",
          },
        ],
      },
      options: {
        responsive: true,
      },
    };
  },
};
</script>
<template>
  <Bar :data="data" :options="options" />
</template>
