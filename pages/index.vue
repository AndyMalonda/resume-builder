<script setup>
    const { sayHello } = useUtils()
    sayHello()

</script>
<template>
  <div>
    <Nav />
    <h1>Home</h1>
    <p>This is the home page</p>
  </div>
</template>