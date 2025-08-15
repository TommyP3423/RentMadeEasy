<template>
  <div>
    <!-- Header -->
    <header style="display:flex; align-items:center; justify-content:space-between; padding:12px 16px; border-bottom:1px solid #eee;">
      <!-- Logo -->
      <div style="display:flex; align-items:center; gap:10px;">
        <img src="/Logo.png" alt="RentMadeEasy logo" style="height:40px;" />
        <span style="font-size:20px; font-weight:600;">RentMadeEasy</span>
      </div>

      <!-- Navigation -->
      <nav style="display:flex; gap:16px;">
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/about">About</NuxtLink>
        <NuxtLink to="/contact">Contact</NuxtLink>
        <NuxtLink to="/login">Login</NuxtLink>
      </nav>
    </header>

    <!-- Page content goes here -->
    <main style="padding:24px;">
      <NuxtPage />
    </main>
  </div>
</template>

<script setup>
// no script needed right now
</script>

<style>
/* add shared layout styles later if you like */
</style>
