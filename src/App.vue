<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <div class="container">
    <header class="header">
      <h1 class="title">My <span class="highlight">Portfolio</span></h1>
      <p class="subtitle">Building aesthetic web experiences.</p>
    </header>

    <main class="content">
      <div class="card">
        <h2>About Me</h2>
        <p>Hi, I am a developer passionate about creating beautiful and functional websites compatible with modern standards.</p> 
      </div>

      <div class="card">
        <h2>Projects</h2>
        <p>Check out my latest work on GitHub.</p>
        <a href="https://github.com/gian7" target="_blank" class="cta-button">Visit GitHub</a>
      </div>
    </main>

    <footer class="footer">
      <p>© 2024 My Portfolio. Built with Vue 3.</p>
    </footer>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  gap: 4rem;
  align-items: center;
  animation: fadeIn 0.8s ease-out;
}

.header {
  margin-top: 2rem;
}

.title {
  font-weight: 800;
  letter-spacing: -0.05em;
  background: linear-gradient(to right, #ffffff, #a5b4fc);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  margin-bottom: 0.5rem;
}

.highlight {
  background: linear-gradient(to right, #6366f1, #818cf8);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}

.subtitle {
  font-size: 1.25rem;
  color: #94a3b8;
  font-weight: 300;
}

.content {
  display: grid;
  grid-template-columns: 1fr;
  gap: 2rem;
  width: 100%;
  max-width: 800px;
}

@media (min-width: 640px) {
  .content {
    grid-template-columns: repeat(2, 1fr);
  }
}

.card {
  padding: 2rem;
  border-radius: 16px;
  background: rgba(255, 255, 255, 0.03);
  border: 1px solid rgba(255, 255, 255, 0.05);
  backdrop-filter: blur(10px);
  transition: transform 0.3s ease, border-color 0.3s ease;
  text-align: left;
}

.card:hover {
  transform: translateY(-5px);
  border-color: rgba(99, 102, 241, 0.3);
}

.card h2 {
  font-size: 1.5rem;
  margin-bottom: 1rem;
  color: #e2e8f0;
}

.card p {
  color: #94a3b8;
  line-height: 1.6;
  margin-bottom: 1.5rem;
}

.cta-button {
  display: inline-block;
  padding: 0.75rem 1.5rem;
  background: linear-gradient(135deg, #6366f1, #4f46e5);
  color: white;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
  font-size: 0.95rem;
  box-shadow: 0 4px 6px -1px rgba(99, 102, 241, 0.2);
  transition: filter 0.2s ease, transform 0.2s ease;
}

.cta-button:hover {
  filter: brightness(1.1);
  transform: translateY(-1px);
}

.footer {
  margin-top: auto;
  padding: 2rem;
  color: #475569;
  font-size: 0.875rem;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}
</style>
