<template>
  <section id="whatido">
    <div class="container">
      <div class="section-title"><span class="hero-tag">What I Do</span></div>
    </div>
    <div class="marquee-wrap">
      <div class="marquee-fade marquee-fade-left"></div>
      <div class="marquee-fade marquee-fade-right"></div>
      <div class="marquee">
        <div class="marquee-track">
          <div v-for="(item, i) in marqueeRow1" :key="`r1-${i}`" class="marquee-item">
            <span class="mi-tag">{{ item.tag }}</span>
            <h3>{{ item.title }}</h3>
            <p>{{ item.desc }}</p>
          </div>
          <div v-for="(item, i) in marqueeRow1" :key="`r1-d-${i}`" class="marquee-item">
            <span class="mi-tag">{{ item.tag }}</span>
            <h3>{{ item.title }}</h3>
            <p>{{ item.desc }}</p>
          </div>
        </div>
      </div>
      <div class="marquee marquee-reverse">
        <div class="marquee-track">
          <div v-for="(item, i) in marqueeRow2" :key="`r2-${i}`" class="marquee-item">
            <span class="mi-tag">{{ item.tag }}</span>
            <h3>{{ item.title }}</h3>
            <p>{{ item.desc }}</p>
          </div>
          <div v-for="(item, i) in marqueeRow2" :key="`r2-d-${i}`" class="marquee-item">
            <span class="mi-tag">{{ item.tag }}</span>
            <h3>{{ item.title }}</h3>
            <p>{{ item.desc }}</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
const marqueeRow1 = [
  { tag: '01', title: 'E-commerce Operations', desc: 'Store Operations & Growth Strategy' },
  { tag: '02', title: 'Content Marketing', desc: 'Brand Content & Social Media' },
  { tag: '03', title: 'Supply Chain', desc: 'Product Selection & Supply Chain' },
  { tag: '04', title: 'Cross-border Commerce', desc: 'Connecting Global Market Opportunities' },
  { tag: '05', title: 'Live Commerce', desc: 'Live Streaming & Conversion' },
  { tag: '06', title: 'Private Domain Traffic', desc: 'Retention & Repurchase Growth' },
  { tag: '07', title: 'Data Analytics', desc: 'Data-Driven Business Decisions' },
  { tag: '08', title: 'Brand Building', desc: 'Building Brands from Zero' }
]

const marqueeRow2 = [
  { tag: '09', title: 'AI Applications', desc: 'AI-Powered E-commerce Efficiency' },
  { tag: '10', title: 'Short Video Marketing', desc: 'Content Seeding & Traffic Growth' },
  { tag: '11', title: 'Community Operations', desc: 'Community Growth & Engagement' },
  { tag: '12', title: 'Product Selection', desc: 'Trend Discovery & Testing' },
  { tag: '13', title: 'Ad Optimization', desc: 'ROI Maximization Strategy' },
  { tag: '14', title: 'User Growth', desc: 'Acquisition & Retention Balance' },
  { tag: '15', title: 'Business Models', desc: 'Innovative Business Models' },
  { tag: '16', title: 'Entrepreneurship', desc: 'Practical Insights & Reflections' }
]
</script>
