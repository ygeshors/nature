---
title: Accueil
layout: default
nav_order: 1
---

<style>
/* --- HERO IMMERSIF --- */
.hero-wrap{
  position: relative;
  border-radius: 18px;
  overflow: hidden;
  border: 1px solid #e5e7eb;
  margin: 10px 0 26px 0;
  background:#111;
}

.hero-img{
  width: 100%;
  height: 360px;
  object-fit: cover;
  display:block;
  filter: saturate(1.05) contrast(1.05);
}

.hero-overlay{
  position:absolute;
  inset:0;
  background: linear-gradient(90deg, rgba(0,0,0,.78) 0%, rgba(0,0,0,.42) 55%, rgba(0,0,0,.18) 100%);
}

.hero-content{
  position:absolute;
  inset:0;
  padding: 26px;
  display:flex;
  flex-direction:column;
  justify-content:flex-end;
  gap: 12px;
  color: #fff;
  max-width: 980px;
}

.hero-title{
  margin:0;
  font-weight:800;
  letter-spacing: .2px;
  line-height: 1.15;
}

.hero-sub{
  margin:0;
  opacity:.92;
  font-size: 1.05rem;
}

.hero-badges{
  display:flex;
  flex-wrap:wrap;
  gap:8px;
  margin-top:4px;
}

.hero-badge{
  display:inline-flex;
  align-items:center;
  gap:6px;
  padding: 6px 10px;
  border-radius: 999px;
  border: 1px solid rgba(255,255,255,.20);
  background: rgba(255,255,255,.10);
  backdrop-filter: blur(6px);
  font-size: .9rem;
  opacity: .98;
}

.hero-cta{
  display:flex;
  flex-wrap:wrap;
  gap:10px;
  margin-top: 6px;
}

.btn{
  display:inline-block;
  padding: 10px 14px;
  border-radius: 12px;
  text-decoration:none !important;
  font-weight: 800;
  border: 1px solid rgba(255,255,255,.18);
  background: rgba(255,255,255,.10);
  color:#fff !important;
  backdrop-filter: blur(6px);
  transition: transform .18s ease, box-shadow .18s ease, background .18s ease;
}

.btn:hover{
  transform: translateY(-2px);
  background: rgba(255,255,255,.16);
  box-shadow: 0 10px 22px rgba(0,0,0,.18);
}

.btn.primary{
  background: #ffffff;
  color:#111827 !important;
  border-color:#fff;
}

.btn.primary:hover{
  background:#f3f4f6;
}

/* --- SECTIONS --- */
.justify{ text-align: justify; }

.section{
  margin: 30px 0;
}

.section h2{
  margin-bottom: 10px;
}

/* --- CARTES --- */
.grid{
  display:grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 16px;
  margin-top: 14px;
}

.card{
  border: 1px solid #e5e7eb;
  border-radius: 16px;
  padding: 18px;
  background: #ffffff;
  transition: transform .20s ease, box-shadow .20s ease;
}

.card:hover{
  transform: translateY(-4px);
  box-shadow: 0 12px 26px rgba(0,0,0,.08);
}

.card .kicker{
  font-size: .92rem;
  opacity: .78;
  margin-bottom: 6px;
}

.card .title{
  font-weight: 900;
  margin: 0 0 8px 0;
  font-size: 1.05rem;
}

.card a{
  font-weight: 800;
  text-decoration: none;
}

.note{
  border-left: 4px solid #16a34a;
  background: #f0fdf4;
  padding: 14px 16px;
  border-radius: 14px;
}

/* Responsive */
@media (max-width: 900px){
  .hero-img{ height: 420px; }
  .hero-overlay{ background: linear-gradient(0deg, rgba(0,0,0,.78) 0%, rgba(0,0,0,.40) 60%, rgba(0,0,0,.18) 100%); }
  .hero-content{ padding: 22px; }
}
</style>

<div class="hero-wrap">
  <img class="hero-img" src="{{ "/assets/images/banniere.jpg" | relative_url }}" alt="Yann Geshors — Nature & Biodiversité">
  <div class="hero-overlay"></div>

  <div class="hero-content">
    <h1 class="hero-title">🌿 Yann GESHORS — Nature & Biodiversité</h1>
    <p class="hero-sub">Photographie de terrain • Carnets naturalistes • Littoral méditerranéen</p>

    <div class="hero-badges">
      <span class="hero-badge">🔎 Observation</span>
      <span class="hero-badge">📸 Photo nature</span>
      <span class="hero-badge">🌊 Littoral & zones humides</span>
      <span class="hero-badge">🗒️ Carnet de terrain</span>
    </div>

    <div class="hero-cta">
      <a class="btn primary" href="{{ "/photos/" | relative_url }}">Voir les photos</a>
      <a class="btn" href="{{ "/carnet/" | relative_url }}">Ouvrir le carnet</a>
      <a class="btn" href="{{ "/contact/" | relative_url }}">Me contacter</a>
    </div>
  </div>
</div>

<div class="section">
## 👤 Présentation

<div class="justify">
Naturaliste de terrain, je documente le vivant par l’observation et la photographie, avec un attachement particulier au littoral méditerranéen.  
Sur ce site, je partage des sorties, des notes de terrain et des images prises sur le vif — une approche sobre, respectueuse, et tournée vers la compréhension des milieux.
</div>
</div>

<div class="section">
## 🌱 Ma démarche

<div class="grid">

<div class="card">
<div class="kicker">Approche</div>
<div class="title">🔎 Observer</div>
Écoute, discrétion, attention aux détails : indices, comportements, ambiances.
</div>

<div class="card">
<div class="kicker">Outil</div>
<div class="title">📸 Photographier</div>
La photo comme mémoire du terrain et vecteur de sensibilisation.
</div>

<div class="card">
<div class="kicker">Partage</div>
<div class="title">🌿 Transmettre</div>
Rendre la nature lisible et accessible, sans la simplifier.
</div>

</div>
</div>

<div class="section">
## 🧭 Explorer

<div class="grid">

<div class="card">
<div class="kicker">Carnets & observations</div>
<div class="title">🗒️ Carnet de terrain</div>
Sorties, comportements, indices, notes naturalistes.
<br><a href="{{ "/carnet/" | relative_url }}">Accéder →</a>
</div>

<div class="card">
<div class="kicker">Galerie</div>
<div class="title">📸 Photographie nature</div>
Images de terrain, sans mise en scène.
<br><a href="{{ "/photos/" | relative_url }}">Voir →</a>
</div>

<div class="card">
<div class="kicker">Suivis / axes</div>
<div class="title">🌱 Projets</div>
Thématiques, méthodes, retours d’expérience.
<br><a href="{{ "/projets/" | relative_url }}">Découvrir →</a>
</div>

<div class="card">
<div class="kicker">Échange</div>
<div class="title">📬 Contact</div>
Collaboration, observation, question.
<br><a href="{{ "/contact/" | relative_url }}">Me contacter →</a>
</div>

</div>
</div>

<div class="section">
## 🌊 Terrains d’exploration

<div class="note">
<strong>Littoral méditerranéen • Dunes • Lagunes • Zones humides • Avifaune • Ambiances sauvages</strong><br>
Observation discrète, respect des distances, attention aux cycles saisonniers et aux pressions sur les milieux.
</div>
</div>

<div class="section">
## 📌 Focus du moment

<div class="card">
<strong>En ce moment :</strong> sorties régulières (littoral / zones humides), alimentation du carnet et sélection photo au fil des observations.  
<br><span style="opacity:.85;">👉 Pour un signalement (espèce, dérangement, comportement), passe par la page contact.</span>
</div>
</div>
