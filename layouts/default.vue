<template>
  <div>
    <header>
        <nav class="container mx-auto flex justify-between p-4">
            <NuxtLink to="/" class="font-bold">Victoria's Steak and Seafood</NuxtLink>
            <ul class="flex gap-4">
                <li><NuxtLink to="/" class="header-link">Home</NuxtLink></li>
                <li><NuxtLink to="/contact" class="header-link">Contact Us</NuxtLink></li>
                <li><NuxtLink to="/reservations" class="header-link">Reservations</NuxtLink></li>
            </ul>
        </nav>
    </header>

    <!-- output content here -->
    <div class="container mx-auto p-4">
        <slot />
    </div>
  </div>
</template>

<script setup>

</script>

<style scoped>
    .router-link-exact-active {
        color: #e3aa4f
    }
</style>