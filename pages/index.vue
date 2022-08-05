<template>
  <div>
    <Html :lang="dynamic > 50 ? 'en-GB' : 'en-US'">
      <Head>
        <Title>Restorantly</Title>
        <Meta name="description" content="My page is cool" />
        <!-- <Link
          rel="preload"
          href="https://www.iconpacks.net/icons/2/free-sad-face-icon-2691-thumb.png"
          as="script"
        /> -->
        <Link
          rel="icon"
          href="https://www.iconpacks.net/icons/2/free-sad-face-icon-2691-thumb.png"
          type="image/gif"
          sizes="16x16"
        />
      </Head>
    </Html>
    <div class="container">
      <h1>Welcome to Restaurantyl</h1>
      <!-- <a href="/restaurants">Go To Restaurantly</a> -->
      <NuxtLink to="/restaurants">Go To Restaurantly</NuxtLink>
    </div>
  </div>
</template>
<style>
.container {
  margin-top: 5rem;
  text-align: center;
}
</style>
