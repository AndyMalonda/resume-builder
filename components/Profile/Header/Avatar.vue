<script setup>

const profile = ref({
  avatar: 'https://avatars.githubusercontent.com/u/3053486?v=4',
});

</script>

<template>
  <div class="avatar">
    <img :src= "profile.avatar" alt="avatar" />
  </div>
</template>