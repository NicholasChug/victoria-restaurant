<template>
  <div>
    <header>
        <nav>
            <NuxtLink to="/" class="header-link">Home</NuxtLink>
            <NuxtLink to="/contact" class="header-link">Contact Us</NuxtLink>
            <NuxtLink to="/reservations" class="header-link">Reservations</NuxtLink>
        </nav>
    </header>

    <!-- output content here -->
    <div>
        <slot />
    </div>
  </div>
</template>

<script setup>

</script>

<style>
    body {
        background-color: #152c53;
    }

    .header-link {
        text-decoration: none;
        color: white;
    }
</style>