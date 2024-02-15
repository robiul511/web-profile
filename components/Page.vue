<template>
  <div class="bg-gray-100">
    <div class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8 flex flex-col h-screen justify-between ">
      <div>
        <Navbar />
        <slot />
      </div>
      <Footer />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style></style>
