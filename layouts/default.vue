<template>
  <div>
    <!-- Header -->
    <header style="display:flex; align-items:center; justify-content:space-between; padding:10px;">
      <!-- Logo -->
      <div style="display:flex; align-items:center;">
        <img src="/Logo.png" alt="RentMadeEasy" style="height:40px; margin-right:10px;">
        <span style="font-size:20px; font-weight:bold;">RentMadeEasy</span>
      </div>

      <!-- Navigation -->
      <nav style="display:flex; gap:15px;">
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/about">About</NuxtLink>
        <NuxtLink to="/contact">Contact</NuxtLink>
        <NuxtLink to="/login">Login</NuxtLink>
      </nav>
    </header>

    <!-- Page Content -->
    <NuxtPage />
  </div>
</template>
