---
title: Accueil
layout: default
nav_order: 1
---

<style>

/* ===== POLICE BARLOW ===== */
@import url('https://fonts.googleapis.com/css2?family=Barlow:wght@300;400;500;600;700;800&display=swap');

body{
  font-family:'Barlow', sans-serif !important;
}

/* ===== HERO PHOTO PURE ===== */
.hero-wrap{
  border-radius:18px;
  overflow:hidden;
  border:1px solid #e5e7eb;
  margin:12px 0 24px 0;
}

.hero-img{
  width:100%;
  height:340px;
  object-fit:cover;
  display:block;
  filter:saturate(1.05) contrast(1.05);
}

/* ===== STRIP PHOTO SIGNATURE ===== */
.strip{
  display:grid;
  grid-template-columns:2fr 1fr 1fr 2fr;
  gap:10px;
  margin: 8px 0 32px 0;
}

.strip img{
  width:100%;
  height:140px;
  object-fit:cover;
  border-radius:16px;
  border:1px solid #e5e7eb;
  transition:transform .25s ease, box-shadow .25s ease;
}

.strip img:hover{
  transform:scale(1.03);
  box-shadow:0 14px 28px rgba(0,0,0,.12);
}

/* ===== SECTIONS ===== */
.section{
  margin:28px 0;
}

.section-title{
  font-size:1.45rem;
  font-weight:800;
  margin-bottom:12px;
}

.justify{
  text-align:justify;
}

/* ===== CARTES ===== */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
  gap:16px;
  margin-top:12px;
}

.card{
  border:1px solid #e5e7eb;
  border-radius:16px;
  padding:18px;
  background:#fff;
  transition:transform .2s ease, box-shadow .2s ease;
}

.card:hover{
  transform:translateY(-4px);
  box-shadow:0 12px 26px rgba(0,0,0,.08);
}

.card-title{
  font-weight:900;
  margin-bottom:8px;
}

.note{
  border-left:4px solid #16a34a;
  background:#f0fdf4;
  padding:14px 16px;
  border-radius:14px;
}

/* ===== RESPONSIVE ===== */
@media (max-width:900px){
  .hero-img{ height:420px; }
  .strip{ grid-template-columns:repeat(2,1fr); }
}

@media (max-width:520px){
  .strip{ grid-template-columns:1fr; }
}

</style>

<!-- HERO PHOTO -->
<div class="hero-wrap">
  <img class="hero-img" src="{{ "/assets/images/banniere.jpg" | relative_url }}">
</div>

<!-- SIGNATURE PHOTO YANN NATURE -->
<div class="strip">
  <img src="{{ "/assets/images/strip-1.jpg" | relative_url }}">
  <img src="{{ "/assets/images/strip-2.jpg" | relative_url }}">
  <img src="{{ "/assets/images/strip-3.jpg" | relative_url }}">
  <img src="{{ "/assets/images/strip-4.jpg" | relative_url }}">
</div>

<div class="section">
<div class="section-title">👤 Présentation</div>

<div class="justify">
Naturaliste de terrain passionné par la biodiversité et les paysages du littoral méditerranéen, je consacre une grande partie de mon temps à observer, photographier et comprendre les milieux naturels.  
Ce site est une vitrine personnelle : un espace pour partager des carnets de terrain, des images et une vision sensible de la nature, entre immersion, respect du vivant et transmission.
</div>
</div>

<div class="section">
<div class="section-title">🌱 Ma démarche</div>

<div class="grid">

<div class="card">
<div class="card-title">🔎 Observer</div>
Approche naturaliste basée sur l’écoute, la discrétion et l’attention aux détails du vivant.
</div>

<div class="card">
<div class="card-title">📸 Photographier</div>
La photographie comme outil de mémoire, d’émotion et de sensibilisation à la biodiversité.
</div>

<div class="card">
<div class="card-title">🌿 Transmettre</div>
Partager des connaissances et des ressentis pour reconnecter chacun à la nature.
</div>

</div>
</div>

<div class="section">
<div class="section-title">🧭 Explorer</div>

<div class="grid">

<div class="card">
<div class="card-title">🗒️ Carnet de terrain</div>
Sorties, observations, comportements, indices et ambiances.
<br><a href="{{ "/carnet/" | relative_url }}">Accéder →</a>
</div>

<div class="card">
<div class="card-title">📸 Photographie nature</div>
Images prises sur le vif, sans mise en scène.
<br><a href="{{ "/photos/" | relative_url }}">Voir →</a>
</div>

<div class="card">
<div class="card-title">🌱 Projets</div>
Suivis naturalistes, axes de travail et retours d’expérience.
<br><a href="{{ "/projets/" | relative_url }}">Découvrir →</a>
</div>

<div class="card">
<div class="card-title">📬 Contact</div>
Question, collaboration ou signalement.
<br><a href="{{ "/contact/" | relative_url }}">Me contacter →</a>
</div>

</div>
</div>

<div class="section">
<div class="section-title">🌊 Terrains d’exploration</div>

<div class="note">
Littoral méditerranéen • Dunes • Lagunes • Zones humides • Avifaune • Ambiances sauvages.  
Observation discrète, respect des distances et attention aux cycles saisonniers.
</div>
</div>
