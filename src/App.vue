<script setup>
</script>

<template>
  <div class="portfolio">
    <!-- Header -->
    <header class="mb-12 animate-fade-in">
      <nav class="flex-between mb-8">
        <span style="font-weight: 800; font-size: 1.25rem;">Gian7</span>
        <div class="nav-links">
          <a href="#about" class="nav-link mr-4">Tentang</a>
          <a href="#projects" class="nav-link mr-4">Jejak Digital</a>
          <a href="https://github.com/gian7" target="_blank" class="nav-link">GitHub ↗</a>
        </div>
      </nav>
      
      <h1>Wahyu Ivdal Saputra</h1>
      <p class="intro">
        <strong>Hardware Enthusiast & Web Developer.</strong><br>
        Menjembatani dunia fisik mikrokontroller dengan antarmuka digital modern.
      </p>
      
      <div class="mt-6 flex-gap">
        <a href="https://github.com/gian7" target="_blank" class="btn">
          <svg height="20" viewBox="0 0 16 16" version="1.1" width="20" aria-hidden="true" style="opacity: 0.8;">
            <path fill="currentColor" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path>
          </svg>
          <span>GitHub</span>
        </a>
        <a href="https://linkedin.com/in/gian7" target="_blank" class="btn">
          <svg height="20" viewBox="0 0 24 24" width="20" aria-hidden="true" style="opacity: 0.8; fill: currentColor;">
            <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
          </svg>
          <span>LinkedIn</span>
        </a>
      </div>
    </header>

    <hr class="divider animate-fade-in delay-1"/>

    <!-- About -->
    <section id="about" class="animate-fade-in delay-1">
      <h2>Tentang</h2>
      <div class="card">
        <p>
          Perjalanan saya bermula pada tahun 2015, merakit logika dengan <strong>Arduino</strong> dan <strong>ESP32</strong> untuk memahami prinsip kerja IoT.
        </p>
        <p style="margin-bottom: 0;">
          Kini, saya membawa presisi hardware tersebut ke pengembangan web modern dengan <strong>Vue 3</strong>. Saya fokus menciptakan antarmuka yang responsif, cepat, dan estetik.
        </p>
      </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="animate-fade-in delay-2">
      <h2>Tech Stack</h2>
      <div class="grid-cols-2">
        <div class="card">
          <h3>Hardware & IoT</h3>
          <p class="muted-text mb-4">Foundation 2015 - Sekarang</p>
          <div>
            <span class="tag">Arduino</span>
            <span class="tag">ESP32</span>
            <span class="tag">C++</span>
            <span class="tag">MicroPython</span>
            <span class="tag">Raspberry Pi</span>
          </div>
        </div>
        <div class="card">
          <h3>Modern Web</h3>
          <p class="muted-text mb-4">Current Focus</p>
          <div>
            <span class="tag">Vue 3</span>
            <span class="tag">Vite</span>
            <span class="tag">JavaScript (ES6+)</span>
            <span class="tag">HTML5/CSS3</span>
            <span class="tag">Tailwind/Rest API</span>
          </div>
        </div>
      </div>
    </section>

     <!-- Projects / Experience -->
     <section id="projects" class="animate-fade-in delay-3">
      <h2>Pengalaman & Proyek</h2>
      <div class="grid-cols-2">
        <!-- Project 1 -->
        <div class="card">
          <h3>Smart Parking System</h3>
          <p class="muted-text">CV. Andalan Lintas Utama</p>
          <p>
            Mengembangkan sistem pembacaan palang parkir menggunakan Raspberry Pi, terintegrasi dengan server Laravel via API.
          </p>
          <div class="mt-4">
             <span class="tag">Raspberry Pi</span>
             <span class="tag">Python</span>
             <span class="tag">API Integration</span>
          </div>
        </div>

        <!-- Project 2 -->
        <div class="card">
          <h3>Early Warning System</h3>
          <p class="muted-text">CV. Andalan Lintas Utama</p>
          <p>
            Programmer radio Motorola untuk sistem peringatan dini bencana alam (Tsunami). Integrasi hardware komunikasi kritis.
          </p>
          <div class="mt-4">
             <span class="tag">Motorola Radio</span>
             <span class="tag">Embedded System</span>
          </div>
        </div>
      </div>
    </section>

    <footer class="mt-16 animate-fade-in delay-3">
      <div class="flex-between">
        <p class="muted-text">© 2025 Wahyu Ivdal Saputra</p>
        <p class="muted-text" style="font-size: 0.85rem;">Built with Vue 3 & Vite</p>
      </div>
    </footer>
  </div>
</template>

<style scoped>
.mb-4 { margin-bottom: 1rem; }
.mb-8 { margin-bottom: 2rem; }
.mb-12 { margin-bottom: 4rem; }
.mt-4 { margin-top: 1rem; }
.mt-6 { margin-top: 1.5rem; }
.mt-16 { margin-top: 5rem; }
.mr-4 { margin-right: 1.5rem; }

.flex-gap {
  display: flex;
  gap: 1rem;
}

.intro {
  font-size: 1.25rem;
  line-height: 1.6;
  color: #374151;
  max-width: 650px;
}
</style>
