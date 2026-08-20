<div align="center">

<!-- HERO SECTION WITH ANIMATED SVG -->
<svg width="100%" height="200" viewBox="0 0 1000 200" xmlns="http://www.w3.org/2000/svg" style="background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); border-radius: 12px; margin-bottom: 20px;">
  <defs>
    <style>
      @keyframes floatIn { 
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
      }
      @keyframes glow {
        0%, 100% { filter: drop-shadow(0 0 8px #0ea5e9); }
        50% { filter: drop-shadow(0 0 16px #06b6d4); }
      }
      @keyframes slideText {
        from { opacity: 0; transform: translateX(-20px); }
        to { opacity: 1; transform: translateX(0); }
      }
      .hero-title { font: bold 48px 'Courier New', monospace; fill: #e0f2fe; animation: floatIn 0.8s ease-out; }
      .hero-subtitle { font: 18px 'Courier New', monospace; fill: #7dd3fc; animation: slideText 1s ease-out 0.3s backwards; }
      .hero-accent { font: 16px 'Courier New', monospace; fill: #06b6d4; animation: slideText 1s ease-out 0.6s backwards; letter-spacing: 2px; }
      .glow-element { animation: glow 3s ease-in-out infinite; }
    </style>
  </defs>
  
  <!-- Background grid -->
  <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
    <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#1e293b" stroke-width="0.5"/>
  </pattern>
  <rect width="1000" height="200" fill="url(#grid)" opacity="0.2"/>
  
  <!-- Content -->
  <g>
    <!-- Left accent -->
    <rect x="20" y="40" width="4" height="120" fill="#0ea5e9" opacity="0.6"/>
    
    <!-- Main text -->
    <text x="50" y="80" class="hero-title">> RAPHAEL</text>
    <text x="50" y="115" class="hero-subtitle">// Builder • Developer • Automation Engineer</text>
    <text x="50" y="145" class="hero-accent">>>> Self-directed • Always Learning • Always Building</text>
    
    <!-- Right accent elements -->
    <circle cx="900" cy="50" r="25" fill="none" stroke="#06b6d4" stroke-width="2" opacity="0.4" class="glow-element"/>
    <circle cx="920" cy="100" r="15" fill="none" stroke="#0ea5e9" stroke-width="2" opacity="0.3" class="glow-element" style="animation-delay: 0.5s"/>
  </g>
</svg>

---

### 🎯 Quem Sou Eu?

**Builder autodirigido** apaixonado por criar soluções inteligentes e interfaces inovadoras. Atualmente trabalhando como **Responsável por Backlogs no Aeroporto GRU**, desenvolvendo automação crítica que impacta operações reais.

<table>
<tr>
<td width="50%">

#### 💼 Experiência
- Automação de processos em Python/Bash
- Desenvolvedor full-stack (Web + Mobile)
- Mentoria técnica e liderança

</td>
<td width="50%">

#### 🎓 Formação
- Técnico em Desenvolvimento de Sistemas (cursando)
- Inglês Avançado + Espanhol Básico
- Treinamento Militar (Elite Chacal)

</td>
</tr>
</table>

---

## 🚀 Projetos em Destaque

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 30px 0;">

### 🤖 J.A.R.V.I.S
**Personal Automation Ecosystem**

```
Status: Em evolução
Arquitetura: Microserviços descentralizados
```

✅ Bot WhatsApp + IA  
✅ Dashboard HUD (Cyan-on-Black)  
✅ Voice Commander (Web Speech API)  
✅ Integração Remote Desktop  
✅ Protocolo M.A.C (Multi-Access Control)  

[→ Ver Projeto](#)

---

### 📈 Bot Trading Multi-Plataforma
**Análise Técnica Automática**

```
Plataformas: Exnova & IQ Option
Ativos: 5 operações simultâneas
```

📊 Análise técnica em tempo real  
💱 Detecção de padrões  
🔄 Gerenciamento de risco avançado  
📧 Relatórios automáticos  

[→ Ver Projeto](#)

---

### 📧 Automação Email GRU
**Solução Crítica Aeroportuária**

```
Escopo: Aeroporto Internacional
Impacto: Processamento de massa
```

🗂️ Gerenciamento de backlogs  
📊 Relatórios automáticos  
⚙️ Integração com sistemas legados  
💼 Zero downtime  

[→ Ver Projeto](#)

---

### 🔍 Script Busca Vagas
**Automação de Oportunidades**

```
Foco: Remoto/Guarulhos-SP
Tipo: Dev de Sistemas
```

🤖 Web scraping inteligente  
📍 Filtros geográficos  
💡 Notificações em tempo real  

[→ Ver Projeto](#)

</div>

---

## 🛠️ Tech Stack

<svg width="100%" height="280" viewBox="0 0 1000 280" xmlns="http://www.w3.org/2000/svg" style="background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); border-radius: 12px; margin: 20px 0;">
  <defs>
    <style>
      .tech-card { animation: floatIn 0.8s ease-out backwards; }
      .tech-card:nth-child(1) { animation-delay: 0.1s; }
      .tech-card:nth-child(2) { animation-delay: 0.2s; }
      .tech-card:nth-child(3) { animation-delay: 0.3s; }
      .tech-card:nth-child(4) { animation-delay: 0.4s; }
      .tech-card:nth-child(5) { animation-delay: 0.5s; }
      .tech-title { font: bold 14px 'Courier New', monospace; fill: #0ea5e9; }
      .tech-item { font: 12px 'Courier New', monospace; fill: #cbd5e1; }
      .tech-border { stroke: #0ea5e9; stroke-width: 2; fill: none; opacity: 0.3; }
    </style>
  </defs>

  <!-- Grid -->
  <pattern id="tech-grid" width="40" height="40" patternUnits="userSpaceOnUse">
    <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#1e293b" stroke-width="0.5"/>
  </pattern>
  <rect width="1000" height="280" fill="url(#tech-grid)" opacity="0.2"/>

  <!-- Languages -->
  <g class="tech-card">
    <rect x="20" y="20" width="180" height="120" rx="8" class="tech-border"/>
    <text x="40" y="45" class="tech-title">► Languages</text>
    <text x="40" y="70" class="tech-item">• Python (Primary)</text>
    <text x="40" y="90" class="tech-item">• JavaScript/Node.js</text>
    <text x="40" y="110" class="tech-item">• Bash/Shell Script</text>
    <text x="40" y="130" class="tech-item">• HTML/CSS</text>
  </g>

  <!-- Frameworks -->
  <g class="tech-card">
    <rect x="220" y="20" width="180" height="120" rx="8" class="tech-border"/>
    <text x="240" y="45" class="tech-title">► Frameworks</text>
    <text x="240" y="70" class="tech-item">• Express.js</text>
    <text x="240" y="90" class="tech-item">• Next.js</text>
    <text x="240" y="110" class="tech-item">• Flask</text>
    <text x="240" y="130" class="tech-item">• React</text>
  </g>

  <!-- Databases -->
  <g class="tech-card">
    <rect x="420" y="20" width="180" height="120" rx="8" class="tech-border"/>
    <text x="440" y="45" class="tech-title">► Databases</text>
    <text x="440" y="70" class="tech-item">• MongoDB</text>
    <text x="440" y="90" class="tech-item">• Firebase</text>
    <text x="440" y="110" class="tech-item">• PostgreSQL</text>
    <text x="440" y="130" class="tech-item">• Redis</text>
  </g>

  <!-- Tools -->
  <g class="tech-card">
    <rect x="620" y="20" width="180" height="120" rx="8" class="tech-border"/>
    <text x="640" y="45" class="tech-title">► Tools</text>
    <text x="640" y="70" class="tech-item">• Git/GitHub/GitLab</text>
    <text x="640" y="90" class="tech-item">• Docker</text>
    <text x="640" y="110" class="tech-item">• Linux (Arch/Ubuntu)</text>
    <text x="640" y="130" class="tech-item">• VS Code</text>
  </g>

  <!-- Platforms -->
  <g class="tech-card">
    <rect x="820" y="20" width="160" height="120" rx="8" class="tech-border"/>
    <text x="840" y="45" class="tech-title">► Platforms</text>
    <text x="840" y="70" class="tech-item">• Android (Termux)</text>
    <text x="840" y="90" class="tech-item">• Windows/Linux</text>
    <text x="840" y="110" class="tech-item">• Web (Full-stack)</text>
    <text x="840" y="130" class="tech-item">• Mobile</text>
  </g>

  <!-- Bottom row - Special Skills -->
  <g class="tech-card" style="animation-delay: 0.6s">
    <rect x="20" y="160" width="960" height="100" rx="8" class="tech-border"/>
    <text x="40" y="185" class="tech-title">► Specialized Skills</text>
    <text x="40" y="210" class="tech-item">🤖 AI/Machine Learning  •  ⚙️ Automação & Scripting  •  🔐 Segurança  •  🏗️ Arquitetura</text>
    <text x="40" y="235" class="tech-item">📊 Data Analysis  •  🎯 Problem Solving  •  👥 Mentoria  •  🚀 DevOps Basics</text>
  </g>
</svg>

---

## 📊 Dashboard

<div style="display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px; margin: 30px 0;">

<div style="background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); border: 1px solid #0ea5e9; border-radius: 8px; padding: 20px; text-align: center;">

### 8+
**Projetos**

Iniciados em 2026

</div>

<div style="background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); border: 1px solid #06b6d4; border-radius: 8px; padding: 20px; text-align: center;">

### 5
**Linguagens**

Python, JS, Bash, HTML, CSS

</div>

<div style="background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); border: 1px solid #0ea5e9; border-radius: 8px; padding: 20px; text-align: center;">

### 3+
**Anos de Experiência**

Desenvolvimento contínuo

</div>

<div style="background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%); border: 1px solid #06b6d4; border-radius: 8px; padding: 20px; text-align: center;">

### ∞
**Paixão**

Por Criar Soluções

</div>

</div>

---

## 🎯 Roadmap 2026+

```
Q1 2026  ◆ Consolidar full-stack development
Q2 2026  ◆ Expandir JARVIS com IA/ML avançado
Q3 2026  ◆ Experiência de mercado tech
Q4 2026  ◆ Preparação para ADS (faculdade)

2027     ◆ Produtos SaaS escaláveis
2027     ◆ Comunidade tech local
2027+    ◆ IA integrada nos projetos
```

---

## 🌐 Conecte-se Comigo

<div align="center">

[![Portfolio](https://img.shields.io/badge/🌐%20Portfolio-HAZURE222.COM-0ea5e9?style=for-the-badge&labelColor=0f172a)](https://hazure222.com)
[![LinkedIn](https://img.shields.io/badge/💼%20LinkedIn-RAPHAELDIAS-0A66C2?style=for-the-badge&labelColor=0f172a)](https://linkedin.com/in/raphaeldias)
[![Instagram](https://img.shields.io/badge/📸%20Instagram-036DONASCIMENTO-E4405F?style=for-the-badge&labelColor=0f172a)](https://instagram.com/036donascimento)
[![GitHub](https://img.shields.io/badge/💻%20GitHub-HAZURE222-181717?style=for-the-badge&labelColor=0f172a)](https://github.com/hazure222)

</div>

---

## 💡 Filosofia

> **"A melhor forma de prever o futuro é criá-lo."**

Tecnologia é um meio, não um fim. Meu objetivo é ser um **builder versátil** que entende não apenas o **COMO** fazer, mas o **POR QUÊ** fazer.

---

<div align="center">

### 🔥 **ALWAYS BUILDING • ALWAYS EVOLVING** 🔥

```
┌─ Status: DEVELOPING ─────────────────┐
│                                      │
│  "One step closer to the future"    │
│                                      │
│  Made with 💻 and ☕ by Raphael      │
└──────────────────────────────────────┘
```

Se você quer criar algo **incrível**, vamos conversar! 🚀

**Last Updated:** 2026-08-20  
**Version:** 2.0 (Modern Edition)

</div>
