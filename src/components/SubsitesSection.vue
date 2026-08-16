<template>
  <section id="subsites">
    <div class="container">
      <div class="section-title"><span class="hero-tag">My Sub-sites</span></div>
      <div class="portal">
        <a v-for="site in portals" :key="site.label" :href="site.href">
          <div class="portal-label">{{ site.label }}</div>
          <h3>{{ site.title }}</h3>
          <p>{{ site.desc }}</p>
          <span class="arrow">Go to {{ site.title.toLowerCase() }}. →</span>
        </a>
      </div>
    </div>
  </section>
</template>

<script setup>
const portals = [
  {
    label: 'BUSINESS',
    title: 'Business',
    desc: 'E-commerce operations, store management, and business growth.',
    href: 'https://shop.【你的域名】.com'
  },
  {
    label: 'EDUCATION',
    title: 'Education',
    desc: 'Articles, insights, and practical learning resources.',
    href: 'https://blog.【你的域名】.com'
  },
  {
    label: 'SKILL',
    title: 'Skill',
    desc: 'E-commerce tools, AI applications, and productivity resources.',
    href: 'https://tools.【你的域名】.com'
  },
  {
    label: 'WORKFLOW',
    title: 'Workflow',
    desc: 'Process systems, study notes, and organized knowledge.',
    href: 'https://notes.【你的域名】.com'
  }
]
</script>
