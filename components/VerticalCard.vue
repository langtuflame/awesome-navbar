<template>
  <div
    class="grid place-items-center bg-gradient-to-l from-indigo-100 to-indigo-900 h-screen"
  >
    <div class="w-80 bg-white rounded-md shadow-xl m-3">
      <div class="h-44 bg-gray-300 rounded-t-md animate-pulse"></div>
      <div class="p-5">
        <div
          class="h-6 rounded-sm bg-gray-200 duration-75 animate-pulse mb-4"
        ></div>
        <div class="animate-pulse">
          <div class="h-1 mt-2 w-1/2 rounded-sm bg-gray-300"></div>
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
  name: 'VerticalCard',
}
</script>
