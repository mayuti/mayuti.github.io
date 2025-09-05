<style>
/* 🌑 Dark Tech Palette */
body {
  background: #0d1117;
  color: #e6edf3;
  font-family: "Ubuntu", "Segoe UI", Roboto, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
}

/* Hero section */
header {
  text-align: center;
  padding: 100px 20px;
  background: linear-gradient(135deg, #0d1117, #161b22);
}
header h1 {
  font-size: 3.5rem;
  margin: 0;
  color: #58a6ff; /* la luz en la oscuridad */
  letter-spacing: 2px;
  font-family: "Ubuntu", sans-serif;
}
header p {
  font-size: 1.3rem;
  margin: 15px 0 0;
  color: #e6edf3;
}

/* Sections */
section {
  max-width: 900px;
  margin: 60px auto;
  padding: 0 20px;
}
section h2 {
  color: #58a6ff;
  margin-bottom: 20px;
  text-align: center;
}
section p {
  text-align: justify;
}

/* Use cases */
.columns {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  gap: 20px;
  margin-top: 20px;
}
.card {
  flex: 1 1 250px;
  background: #161b22;
  padding: 20px;
  border-radius: 8px;
  text-align: center;
  border: 1px solid #30363d;
}
.card h3 {
  color: #58a6ff;
}

/* Contact */
.contact {
  text-align: center;
  margin: 40px 0;
}
.contact a {
  color: #58a6ff;
  font-weight: bold;
  text-decoration: none;
}
.contact a:hover {
  text-decoration: underline;
}

/* Footer */
footer {
  text-align: center;
  padding: 30px;
  font-size: 0.9rem;
  border-top: 1px solid #30363d;
  color: #8b949e;
  margin-top: 60px;
}
</style>

<header>
  <h1>ITUYAM</h1>
  <p>IT Unified Automation Management</p>
  <p><em>Gestión Unificada de Inteligencia y Automatización en IT</em></p>
</header>

<section id="about">
  <h2>🌐 About ITUYAM</h2>

  🇪🇸 Español  
  ITUYAM surge de la idea de **Inteligencia y Automatización Unificada en IT**.  
  Nuestro enfoque integra la capacidad de analizar, correlacionar y automatizar procesos dentro de una misma plataforma, generando confianza técnica y eficiencia operativa.  

  🇬🇧 English  
  ITUYAM stands for **IT Unified Automation Management**.  
  Our approach brings together intelligence, correlation, and automation into a single framework, delivering technical reliability and operational efficiency.
</section>

<section>
  <h2>⚡ Use Cases</h2>
  <div class="columns">
    <div class="card">
      <h3>⚙️ Automatización IT</h3>
      <p>Integración de flujos, procesos y orquestación.</p>
    </div>
    <div class="card">
      <h3>📊 Análisis y Correlación</h3>
      <p>Métricas y eventos en un marco unificado.</p>
    </div>
    <div class="card">
      <h3>🔗 Sistemas Embebidos / IoT</h3>
      <p>Conexión con dispositivos inteligentes.</p>
    </div>
  </div>
</section>

<section class="contact">
  <h2>📬 Contact</h2>
  <p>¿Querés más información o ponerte en contacto con nosotros?</p>
  <p>✉️ <a href="mailto:contact@ituyam.com">contact@ituyam.com</a></p>
</section>

<footer>
  © 2025 ITUYAM | Technical Reliability & Automation
</footer>
