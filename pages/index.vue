<template>
  <div>
    <HorizontalCard/>
    <VerticalCard/>
    <CardSleketon/>
    <div class="flex items-center py-10 justify-center">
      <ContinuousLoading />
    </div>
  </div>
</template>

<script>
export default {
    name: "IndexPage"
}
</script>
