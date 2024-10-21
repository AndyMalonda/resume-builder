<script setup>
    const route = useRoute()
    console.log(route.params.id)

</script>

<template>
    <div>
        <Profile/>
        Profile page for user with ID {{ $route.params.id }}
    </div>
</template>