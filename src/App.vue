<template>
  <div class="portfolio">
    <header>
      <h1>Narzullo | FrontEnd Engineer</h1>
      <p class="subtitle">Vue.js Developer & Thermal Power Engineer</p>
    </header>

    <section class="about">
      <h2>About Me</h2>
      <p>
        I am passionate about creating user-friendly, interactive, and modern web applications. 
        My analytical background in engineering provides me with a systematic approach to finding 
        optimal solutions to complex problems.
      </p>
      <div class="badge">🚀 Quick Learner: 0:27s record</div>
    </section>

    <section class="skills">
      <h2>Skills</h2>
      <ul>
        <li>Vue.js & TypeScript</li>
        <li>JavaScript (ES6+)</li>
        <li>CSS Grid & Flexbox</li>
        <li>Responsive Web Design</li>
      </ul>
    </section>
    <section class="card">
        <h2>My Projects</h2>
        <div class="projects-list">
          <div class="project-card">
            <h3>Narzullo Portfolio</h3>
            <p>Vue.js va TypeScript yordamida yaratilgan shaxsiy brend sayti.</p>
            <span class="tech-stack">Vue 3 | Vite | CSS Grid</span>
          </div>
          <div class="project-card">
            <h3>Thermal Systems Analysis</h3>
            <p>Energetika tizimlarini tahlil qilish uchun muhandislik hisob-kitoblari moduli.</p>
            <span class="tech-stack">JavaScript | Calculations</span>
          </div>
        </div>
      </section>
      <section class="card contact">
        <h2>Contact Me</h2>
        <p>I am always open to new professional connections and interesting projects!</p>
        <div class="contact-links">
          <a href="https://www.linkedin.com/in/YOUR_LINKEDIN_ID" target="_blank" class="btn">LinkedIn Profile</a>
          <a href="mailto:alixonovnarzulloxon@example.com" class="btn secondary">Email Me</a>
        </div>
      </section>
  </div>
</template>

<style scoped>
.portfolio {
  font-family: 'Inter', sans-serif;
  max-width: 800px;
  margin: 0 auto;
  padding: 40px 20px;
  color: #f8fafc;
  background-color: #0f172a;
  min-height: 100vh;
}
header { text-align: center; border-bottom: 1px solid #42b883; padding-bottom: 20px; }
h1 { color: #42b883; }
.subtitle { font-style: italic; color: #94a3b8; }
section { margin-top: 40px; }
h2 { color: #42b883; border-left: 4px solid #42b883; padding-left: 10px; }
.badge { display: inline-block; background: #1e293b; padding: 10px 20px; border-radius: 8px; margin-top: 10px; border: 1px solid #42b883; }
ul { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
.projects-list { display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin-top: 15px; }
.project-card { background: #0f172a; padding: 20px; border-radius: 8px; border: 1px dashed #42b883; }
.project-card h3 { color: #42b883; margin-top: 0; }
.tech-stack { display: block; margin-top: 10px; font-size: 0.8rem; color: #94a3b8; font-weight: bold; }
.contact { text-align: center; }
.contact-links { display: flex; justify-content: center; gap: 20px; margin-top: 20px; }
.btn { 
  background-color: #42b883; 
  color: #0f172a; 
  padding: 12px 25px; 
  border-radius: 8px; 
  text-decoration: none; 
  font-weight: bold; 
  transition: 0.3s;
}
.btn.secondary { background-color: transparent; border: 2px solid #42b883; color: #42b883; }
.btn:hover { opacity: 0.8; transform: translateY(-2px); }
</style>