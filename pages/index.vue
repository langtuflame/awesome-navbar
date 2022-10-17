<template>
  <div>
    <HorizontalCard/>
    <VerticalCard/>
    <CardSleketon/>
    <div class="flex items-center justify-center py-10">
      <SpinnerLoading />
    </div>
  </div>
</template>

<script>
import SpinnerLoading from '~/components/SpinnerLoading.vue';
export default {
    name: "IndexPage",
    components: { SpinnerLoading }
}
</script>
