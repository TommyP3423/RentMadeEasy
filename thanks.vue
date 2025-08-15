<!-- pages/index.vue -->
<template>
  <main style="max-width:980px;margin:24px auto;">
    <h1 style="font-size:40px;margin:0 0 12px;">Renting, made easy.</h1>
    <p>Join the early list without the headache.</p>

    <form action="/thanks" method="POST" name="waitlist" data-netlify="true" style="margin-top:24px;">
      <input type="email" name="email" placeholder="you@example.com" required
             style="padding:10px;border:1px solid #ccc;border-radius:6px;width:280px;">
      <button type="submit" style="padding:10px 14px;border-radius:6px;margin-left:8px;">
        Join waitlist
      </button>
    </form>
  </main>
</template>
