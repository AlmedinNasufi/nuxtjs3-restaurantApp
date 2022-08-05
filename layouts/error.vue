<template>
  <div>
    <div class="container">
      <slot name="header" />
      <div>
        <img
          src="https://www.iconpacks.net/icons/2/free-sad-face-icon-2691-thumb.png"
          alt=""
        />
      </div>
      <slot name="redirectEl" />
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
