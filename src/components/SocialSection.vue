<template>
  <section>
    <div class="container">
      <div class="section-title"><span class="hero-tag">Connect With Me</span></div>
      <div class="social">
        <a v-for="link in socialLinks" :key="link.label" :href="link.href">
          {{ link.icon }} {{ link.label }}
        </a>
      </div>
    </div>
  </section>
</template>

<script setup>
const socialLinks = [
  { icon: '🐦', label: 'Twitter / X', href: 'https://x.com/tinln25249' },
  { icon: '👤', label: 'Facebook', href: 'https://facebook.com/【你的主页】' },
  { icon: '✉️', label: 'Email', href: 'https://mail.google.com/mail/?view=cm&fs=1&to=lvan6654321000@gmail.com' }
]
</script>
