<script setup>
import Card from './Card.vue';
</script>

<template>
  <section class="py-4">
      <div class="container-xl lg:container m-auto">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-4 p-4 rounded-lg">
          <Card bg="bg-red-100">
            <h2 class="text-2xl font-bold">For Developers</h2>
            <p class="mt-2 mb-4">
              Want to upskill??
            </p>
            <a
            href="#"
              class="inline-block bg-black text-white rounded-lg px-4 py-2 hover:bg-gray-700"
            >
              Start Today
            </a>
          </Card>
          <Card bg="bg-cyan-100">
            <h2 class="text-2xl font-bold">For Students</h2>
            <p class="mt-2 mb-4">
              Eager to learn a new framework?
            </p>
            <a
            href="#"
              class="inline-block bg-green-500 text-white rounded-lg px-4 py-2 hover:bg-green-600"
            >
              Let's Go
            </a>
          </Card>
        </div>
      </div>
    </section>
</template>