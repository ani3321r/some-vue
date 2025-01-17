<script setup>
import topicData from '@/topics.json';
</script>

<template>
  <section class="bg-blue-50 px-4 py10">
    <div class="container-xl lg:container m-auto">
      <h2 class="text-3xl font-bold text-green-500 mb-6 text-center">
        Browse Topics
      </h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div v-for="topic in topicData" :key="topic.id">
          {{ topic.title }}
        </div>
      </div>
    </div>
  </section>
</template>