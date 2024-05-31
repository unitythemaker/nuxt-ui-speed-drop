<template>
  <div class="container p-4">
    <div class="mb-10 bg-gray-200 w-full flex gap-5">
      <UButton to="/">Home</UButton>
      <UButton to="/blog">Blog</UButton>
    </div>

    <slot />
  </div>
</template>
