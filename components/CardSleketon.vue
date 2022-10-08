<template>
  <div
    class="min-h-screen flex items-center justify-center bg-gradient-to-br from-gray-200 to-gray-400"
  >
    <!-- card -->
    <div class="w-3/4 bg-white rounded shadow-2xl rounded-lg">
      <!-- image -->
      <div
        class="h-32 bg-gray-200 rounded-tr-lg rounded-tl-lg animate-pulse"
      ></div>
      <div class="p-5">
        <!-- tile -->
        <div class="h-6 px-2 rounded-sm bg-gray-200 animate-pulse mb-4"></div>

        <!-- content link -->

        <!-- content notes -->
        <div class="h-4 rounded-sm bg-gray-200 animate-pulse mt-4 mb-4"></div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'CardSleketon',
}
</script>
