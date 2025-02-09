<script setup>
import {ref} from 'vue'

</script>


<template>
  <div class="container">
    <h1>Countdown Timer</h1>
    <input type="number" placeholder="Enter seconds" min="1" max="60" v-model.number="timeInput"/>

    <button>Start</button>
    <button>Stop</button>

    <h2 class="timerDisplay">00:00</h2>

  </div>


</template>
