<template>
  <div
    class="grid place-items-center bg-gradient-to-l from-indigo-100 to-indigo-900 h-screen"
  >
    <div class="flex w-96 bg-white rounded-md shadow-xl m-3">
      <div class="w-1/3 bg-gray-300 rounded-l-md animate-pulse"></div>
      <div class="p-5 w-3/4">
        <div
          class="h-6 rounded-sm bg-gray-200 duration-75 animate-pulse mb-4"
        ></div>
        <div class="animate-pulse">
          <div class="h-1 mt-2 w-1/3 rounded-sm bg-gray-300"></div>
          <div class="h-1 mt-2 w-2/3 rounded-sm bg-gray-300"></div>
          <div class="h-1 mt-2 rounded-sm bg-gray-300"></div>
          <div class="h-1 mt-2 rounded-sm bg-gray-300"></div>
          <div class="h-1 mt-2 rounded-sm bg-gray-300"></div>
          <div class="h-2 rounded-sm bg-gray-300"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HorizontalCard',
}
</script>
