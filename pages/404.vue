<template>
  <div>
    <div class="container">
      <NuxtLayout name="error">
        <template #header>
          <h1>404 - Page Not Found</h1>
        </template>
        
        <template #redirectEl>
          <a href="/">Go back</a>
        </template>
      </NuxtLayout>
    </div>
  </div>
</template>
<style>
.container {
  margin-top: 5rem;
  text-align: center;
}
img {
  width: 10rem;
}
</style>
