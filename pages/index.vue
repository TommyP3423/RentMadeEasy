<template>
  <main style="max-width:980px;margin:40px auto;padding:0 20px;">
    <!-- Hero -->
    <section style="display:flex;flex-direction:column;gap:18px;align-items:flex-start;">
      <h1 style="font-size:40px;line-height:1.1;margin:0;">
        Renting, made easy.
      </h1>
      <p style="font-size:18px;color:#444;margin:0;">
        Join the early list for <strong>RentMadeEasy</strong> — smart tools for tenants & landlords,
        without the headache.
      </p>
    </section>

    <!-- Waitlist form (Netlify Forms) -->
    <section style="margin-top:28px;">
      <form name="waitlist"
            method="POST"
            data-netlify="true"
            netlify-honeypot="bot-field"
            action="/thanks"
            style="display:flex;gap:10px;flex-wrap:wrap;">
        <!-- required hidden field for Netlify -->
        <input type="hidden" name="form-name" value="waitlist" />
        <p style="display:none;">
          <label>Don’t fill this out: <input name="bot-field" /></label>
        </p>

        <input
          type="email"
          name="email"
          required
          placeholder="Enter your email"
          style="flex:1;min-width:240px;padding:12px 14px;border:1px solid #ddd;border-radius:8px;"
        />
        <button
          type="submit"
          style="padding:12px 18px;border:none;border-radius:8px;background:#0fa3b1;color:#fff;font-weight:700;">
          Join Waitlist
        </button>
      </form>

      <p style="margin-top:10px;color:#666;font-size:13px;">
        We’ll only email about launch updates. Unsubscribe anytime.
      </p>
    </section>

    <!-- Simple features blurb -->
    <section style="margin-top:40px;display:grid;gap:18px;">
      <h2 style="margin:0;">Why RentMadeEasy?</h2>
      <ul style="margin:0;padding-left:18px;line-height:1.7;color:#333;">
        <li>Fast, clear applications — no duplicate paperwork.</li>
        <li>Fair tenant screening & transparent criteria.</li>
        <li>Simple communication and status tracking for everyone.</li>
      </ul>
    </section>
  </main>
</template>
