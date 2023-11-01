<template>
    <div class="w-44 h-44">
        <Pie :data="chartData" :options="chartOptions" />
    </div>
</template>
<script setup>
import { Bar, Pie } from "vue-chartjs";
import { ref } from "vue"

const chartData = ref({
    //labels: ["20%"],
    datasets: [
        {
            backgroundColor: ["#caeced", "#04aeba"],
            data: [80, 20]
        }
    ]
})
const chartOptions = ref({
    responsive: true,
    maintainAspectRatio: false
})
</script>