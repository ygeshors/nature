---
title: Accueil
nav_order: 1
---

<style>
.justify { text-align: justify; }

.hero{
  display:grid;
  grid-template-columns: 1.25fr 1fr;
  gap:18px;
  align-items:center;
  margin: 10px 0 18px 0;
}

.hero img{
  width:100%;
  border-radius:16px;
  border:1px solid #e5e7eb;
  background:#fff;
}

.hero h1{ margin:0 0 6px 0; }
.hero .tagline{ font-size:1.05rem; opacity:.85; margin:0 0 12px 0; }

.badges{ display:flex; flex-wrap:wrap; gap:8px; margin: 10px 0 14px 0; }
.badge{
  padding:6px 10px;
  border:1px solid #e5e7eb;
  border-radius:999px;
  background:#fafafa;
  font-size:.9rem;
}

.cta{ display:flex; flex-wrap:wrap; gap:10px; margin-top:12px; }
.btn{
  display:inline-block;
  padding:10px 14px;
  border-radius:12px;
  border:1px solid #e5e7eb;
  background:#fff;
  text-decoration:none;
  font-weight:700;
}
.btn.primary{ background:#111827; color:#fff; border-color:#111827; }
.btn:hover{ text-decoration:none; transform: translateY(-1px); }

.vitrine{
  display:grid;
  grid-template-columns: repeat(auto-fit, minmax(220px,1fr));
  gap:18px;
  margin-top: 16px;
}

.carte{
  padding:18px;
  border-radius:14px;
  border:1px solid #e5e7eb;
  background:#fafafa;
  transition: transform .2s ease, box-shadow .2s ease;
}

.carte:hover{
  transform: translateY(-4px);
  box-shadow: 0 6px 18px rgba(0,0,0,0.08);
}

.titre{ font-weight:800; font-size:1.05rem; margin-bottom:6px; }

.sep{ margin: 18px 0; }
.small{ font-size:.95rem; opacity:.9; }

@media (max-width: 900px){
  .hero{ grid-template-columns: 1fr; }
}
</style>

<div class="hero">
  <div>
    <h1>🌿 Yann GESHORS — Nature & Biodiversité</h1>
    <p class="tagline">Photographie de terrain • Carnets naturalistes • Littoral méditerranéen</p>

    <div class="badges">
      <div class="badge">🔎 Observation discrète</div>
      <div class="badge">📸 Photo nature</div>
      <div class="badge">🌊 Littoral & zones humides</div>
      <div class="badge">🗒️ Carnet de terrain</div>
    </div>

    <div class="cta">
      <a class="btn primary" href="{{ "/photos/" | relative_url }}">Voir les photos</a>
      <a class="btn" href="{{ "/carnet/" | relative_url }}">Ouvrir le carnet</a>
      <a class="btn" href="{{ "/contact/" | relative_url }}">Me contacter</a>
    </div>
  </div>

  <div>
    <img src="{{ "/assets/images/banniere.jpg" | relative_url }}" alt="Bannière — Yann Geshors, Nature & Biodiversité">
  </div>
</div>

---

## 👤 Présentation

<div class="justify">

Naturaliste de terrain, je documente le vivant par l’observation et la photographie, avec un attachement particulier au littoral méditerranéen.  
Sur ce site, je partage des sorties, des notes de terrain et des images prises sur le vif — une approche sobre, respectueuse, et tournée vers la compréhension des milieux.

</div>

---

## 🌱 Ma démarche

<div class="vitrine">

<div class="carte">
  <div class="titre">🔎 Observer</div>
  <div class="small">Approche naturaliste basée sur l’écoute, la discrétion et l’attention aux détails du vivant.</div>
</div>

<div class="carte">
  <div class="titre">📸 Photographier</div>
  <div class="small">La photographie comme outil de mémoire, d’émotion et de sensibilisation à la biodiversité.</div>
</div>

<div class="carte">
  <div class="titre">🌿 Transmettre</div>
  <div class="small">Partager des connaissances et des ressentis pour reconnecter chacun à la nature.</div>
</div>

</div>

---

## 🧭 Ce que tu trouveras ici

<div class="vitrine">

<div class="carte">
  <div class="titre">🗒️ Carnet de terrain</div>
  Sorties, observations, comportements, indices, ambiances.
  <br><a href="{{ "/carnet/" | relative_url }}">Accéder au carnet →</a>
</div>

<div class="carte">
  <div class="titre">📸 Photographie nature</div>
  Images de terrain, sans mise en scène, pour raconter le vivant.
  <br><a href="{{ "/photos/" | relative_url }}">Voir la galerie →</a>
</div>

<div class="carte">
  <div class="titre">🌱 Projets</div>
  Axes, thématiques, suivi naturaliste, retours d’expérience.
  <br><a href="{{ "/projets/" | relative_url }}">Découvrir →</a>
</div>

</div>

---

## 🌊 Terrains d’exploration

<div class="justify">

- Littoral méditerranéen et dunes naturelles  
- Lagunes, roselières et zones humides  
- Avifaune et comportements naturels  
- Ambiances sauvages et photographie immersive

</div>

---

## 📌 Focus du moment

<div class="carte">
  <strong>En ce moment :</strong> sorties de terrain régulières (littoral / zones humides), alimentation du carnet et sélection photo au fil des observations.
  <br><span class="small">👉 Si tu veux me signaler une observation (espèce, dérangement, comportement), passe par la page contact.</span>
</div>

---

## 📬 Contact

<div class="justify">
Pour une question, une observation à partager, une collaboration photo ou un projet :  
<a href="{{ "/contact/" | relative_url }}"><strong>me contacter →</strong></a>
</div>
