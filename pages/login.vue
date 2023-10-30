<template>
  <div class="prose w-full max-w-2xl h-9">
    <h1>Log in to {{ title }}</h1>
    <button class="bg-blue text-white font-bold py-2 rounded">
      Login in with Github
    </button>
  </div>
</template>
<script setup>
const { title } = useCourse();
</script>
