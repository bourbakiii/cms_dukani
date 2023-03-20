<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>


<script setup>
  useHead({
    title: "Конструктор",
    link: [
      {
        href: "https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css",
        rel: "stylesheet",
        integrity: "sha384-gH2yIJqKdNHPEq0n4Mqa/HGKIhSkIHeL5AyhkYV8i59U5AR6csBvApHHNl/vI1Bx",
        crossorigin: "anonymous"
      }
    ],
    script: [
      {
        src: "https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js",
        integrity: "sha384-A3rJD856KowSb7dwlZdYEkO39Gagi7vIsF0jrRAoQmDKKtQBHUuLZ9AsSv4jD4Xa",
        crossorigin: "anonymous"
      }
    ]
  })
</script>

<style lang="scss">
.page-enter-active,
.page-leave-active {
  transition: all 0.3s;
}

.page-enter-from,
.page-leave-to {
  opacity: 0;
  filter: blur(4px);
}
</style>