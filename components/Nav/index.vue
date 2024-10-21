<template>
  <header>
    <nav>
      <ul>
        <NuxtLink to="/">
          <IconsHome />
        </NuxtLink>
        <NuxtLink to="/about">
          <IconsInfo />
        </NuxtLink>
        <NuxtLink to="/profile">
          <IconsAccount />
        </NuxtLink>
      </ul>
    </nav>
  </header>
</template>

<style>
  nav ul {
    display: flex;
    justify-content: space-around;
  }
</style>