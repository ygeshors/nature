---
layout: default
title: Accueil
nav_order: 1
---

<style>
/* ===== Yann Nature – CSS local (inratable) ===== */

.yn-wrap{max-width:980px;margin:0 auto;}
.yn-hero{position:relative;border-radius:16px;overflow:hidden;background:#111;box-shadow:0 8px 28px rgba(0,0,0,.12);}
.yn-hero img{display:block;width:100%;height:260px;object-fit:cover;}
@media (min-width: 900px){ .yn-hero img{height:320px;} }

.yn-actions{display:flex;gap:10px;flex-wrap:wrap;justify-content:center;margin:14px 0 22px;}
.yn-btn{
  display:inline-flex;align-items:center;gap:8px;
  padding:10px 14px;border-radius:999px;
  text-decoration:none !important;
  border:1px solid rgba(0,0,0,.08);
  background:#fff;
  box-shadow:0 2px 10px rgba(0,0,0,.06);
  font-weight:650;
}
.yn-btn:hover{transform:translateY(-1px);box-shadow:0 6px 16px rgba(0,0,0,.10);}
.yn-btn--primary{background:#2e8b57;color:#fff !important;border-color:#2e8b57;}

.yn-title{margin:14px 0 6px;font-size:34px;line-height:1.1;}
.yn-sub{margin:0 0 14px;opacity:.85;font-size:16px;}
.yn-hr{margin:22px 0;border:none;border-top:1px solid rgba(0,0,0,.08);}

.yn-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin:14px 0 6px;}
.yn-card{
  background:#fff;border:1px solid rgba(0,0,0,.08);
  border-radius:14px;padding:14px 14px 12px;
  box-shadow:0 2px 10px rgba(0,0,0,.05);
}
.yn-card h4{margin:0 0 6px;font-size:16px;}
.yn-card p{margin:0;opacity:.85}
.yn-card a{font-weight:650;text-decoration:none !important;}
.yn-badge{display:inline-flex;align-items:center;gap:8px;padding:8px 12px;border-radius:999px;background:#f4f7f5;border:1px solid rgba(0,0,0,.06);font-weight:650}
.yn-highlight{
  background:#ecfdf5;border:1px solid #b7e4c7;border-left:5px solid #2e8b57;
  border-radius:14px;padding:14px;opacity:.95
}
.yn-justify{ text-align:justify; }
</style>

<div class="yn-wrap">

  <!-- Bannière (SANS texte dessus) -->
  <div class="yn-hero">
    <img src="{{ site.baseurl }}/assets/images/banner.jpg" alt="Bannière Yann Nature">
  </div>

  <!-- Logo (sous la bannière, taille contrôlée) -->
  <p style="text-align:center; margin:16px 0 6px;">
    <img src="{{ site.baseurl }}/assets/images/logo-yann-nature.png"
         alt="Logo Yann Nature"
         style="width:140px; height:140px; object-fit:contain; border-radius:50%; background:#fff; box-shadow:0 10px 25px rgba(0,0,0,.12); padding:10px;">
  </p>

  <!-- Boutons -->
  <div class="yn-actions">
    <a class="yn-btn yn-btn--primary" href="{{ site.baseurl }}/photos/">📸 Voir les photos</a>
    <a class="yn-btn" href="{{ site.baseurl }}/carnet/">🗒️ Ouvrir le carnet</a>
    <a class="yn-btn" href="{{ site.baseurl }}/sorties/">🥾 Sorties</a>
    <a class="yn-btn" href="{{ site.baseurl }}/projets/">🌱 Projets</a>
    <a class="yn-btn" href="{{ site.baseurl }}/contact/">📬 Me contacter</a>
  </div>

  <h1 class="yn-title">Yann GESHORS — Nature &amp; Biodiversité</h1>
  <p class="yn-sub yn-justify">
    Naturaliste de terrain, attaché au littoral méditerranéen. Ici je partage des carnets d’observation, des sorties,
    de la photographie nature et quelques projets liés à l’étude et à la protection du vivant.
  </p>

  <hr class="yn-hr">

  <h2>🌿 Ma démarche</h2>
  <div class="yn-grid">
    <div class="yn-card">
      <h4>🔎 Observer</h4>
      <p>Écoute, discrétion, attention aux indices du vivant : traces, comportements, cycles saisonniers.</p>
    </div>
    <div class="yn-card">
      <h4>📷 Photographier</h4>
      <p>Images prises sur le vif, pour documenter le terrain et transmettre une émotion juste.</p>
    </div>
    <div class="yn-card">
      <h4>🌱 Transmettre</h4>
      <p>Rendre la nature lisible et accessible, sans la simplifier — par le récit et l’expérience.</p>
    </div>
  </div>

  <hr class="yn-hr">

  <h2>🧭 Explorer</h2>
  <div class="yn-grid">
    <div class="yn-card">
      <h4>🗒️ Carnet de terrain</h4>
      <p>Observations, comportements, indices, notes naturalistes.</p>
      <p style="margin-top:10px;"><a href="{{ site.baseurl }}/carnet/">Accéder →</a></p>
    </div>
    <div class="yn-card">
      <h4>📸 Photographie nature</h4>
      <p>Faune, ambiances, milieux — sans mise en scène.</p>
      <p style="margin-top:10px;"><a href="{{ site.baseurl }}/photos/">Voir →</a></p>
    </div>
    <div class="yn-card">
      <h4>🥾 Sorties</h4>
      <p>Balades, explorations, rencontres de terrain.</p>
      <p style="margin-top:10px;"><a href="{{ site.baseurl }}/sorties/">Découvrir →</a></p>
    </div>
    <div class="yn-card">
      <h4>🌱 Projets</h4>
      <p>Suivis naturalistes, thématiques, retours d’expérience.</p>
      <p style="margin-top:10px;"><a href="{{ site.baseurl }}/projets/">Découvrir →</a></p>
    </div>
  </div>

  <hr class="yn-hr">

  <h2>🌊 Terrains d’exploration</h2>
  <div class="yn-highlight yn-justify">
    Littoral méditerranéen • dunes • lagunes • zones humides • avifaune • ambiances sauvages.
    Observation discrète, respect des distances, attention aux pressions sur les milieux.
  </div>

</div>
