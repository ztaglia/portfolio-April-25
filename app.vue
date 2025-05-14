<template>
  <div>
    <!-- This component will render the selected layout (home.vue in this case) -->
    <!-- The current page content (from index.vue) will be injected into the layout's <slot /> -->
    <NuxtLayout>
      <!-- This component renders the current page -->
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>