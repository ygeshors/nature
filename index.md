---
title: Accueil
layout: default
nav_order: 1
---

<div class="cinema">

  <img class="cinema-banner" src="{{ '/assets/images/banner.jpg' | relative_url }}" alt="Bannière Yann Nature">

  <div class="filmstrip">
    <img src="{{ '/assets/images/strip-1.jpg' | relative_url }}" alt="Photo terrain 1">
    <img src="{{ '/assets/images/strip-2.jpg' | relative_url }}" alt="Photo terrain 2">
    <img src="{{ '/assets/images/strip-3.jpg' | relative_url }}" alt="Photo terrain 3">
    <img src="{{ '/assets/images/strip-4.jpg' | relative_url }}" alt="Photo terrain 4">
  </div>

  <div class="cinema-shell">
    <div class="cinema-card">

      <div class="cinema-logo">
        <img src="{{ '/assets/images/logo-yann-nature.png' | relative_url }}" alt="Logo Yann Nature">
      </div>

      <div class="cinema-text">
        <h1>Yann GESHORS — Nature &amp; Biodiversité</h1>

        <p class="cinema-sub">
          Naturaliste de terrain, passionné par la biodiversité et les paysages du littoral méditerranéen.
          Ici, je partage des carnets d’observation, de la photographie de terrain, des sorties et quelques projets liés à l’étude et à la protection du vivant.
        </p>

        <div class="cinema-cta">
          <a class="btn btn-dark" href="{{ '/photos/' | relative_url }}">Voir les photos</a>
          <a class="btn btn-light" href="{{ '/carnet/' | relative_url }}">Ouvrir le carnet</a>
          <a class="btn btn-green" href="{{ '/contact/' | relative_url }}">Me contacter</a>
        </div>
      </div>

    </div>
  </div>

</div>

<div class="page-content">

  <div class="section-title">🌿 Présentation</div>
  <p class="lead">
    Naturaliste de terrain, je documente le vivant par l’observation et la photographie, avec un attachement particulier au littoral méditerranéen.
    Sur ce site, je partage des sorties, des notes de terrain et des images prises sur le vif — une approche sobre, respectueuse, et tournée vers la compréhension des milieux.
  </p>

  <div class="section-title">🌱 Ma démarche</div>
  <div class="grid">
    <div class="card">
      <h3>🔎 Observer</h3>
      <p>Écoute, discrétion et attention aux indices du vivant (comportements, cycles, ambiances).</p>
    </div>
    <div class="card">
      <h3>📷 Photographier</h3>
      <p>Images prises sur le vif, pour documenter le terrain et transmettre une émotion juste.</p>
    </div>
    <div class="card">
      <h3>🌿 Transmettre</h3>
      <p>Rendre la nature lisible et accessible, sans la simplifier — par le récit et le partage.</p>
    </div>
  </div>

  <div class="section-title">🧭 Explorer</div>
  <div class="grid">
    <div class="card">
      <h3>🗒️ Carnet de terrain</h3>
      <p>Observations, indices, comportements, notes naturalistes.</p>
      <a href="{{ '/carnet/' | relative_url }}">Accéder →</a>
    </div>
    <div class="card">
      <h3>📸 Photographie</h3>
      <p>Galerie d’images terrain (faune, ambiances, milieux).</p>
      <a href="{{ '/photos/' | relative_url }}">Voir →</a>
    </div>
    <div class="card">
      <h3>🧩 Projets</h3>
      <p>Suivis naturalistes, axes de travail, retours d’expérience.</p>
      <a href="{{ '/projets/' | relative_url }}">Découvrir →</a>
    </div>
  </div>

  <div class="section-title">🌊 Terrains d’exploration</div>
  <div class="note">
    Littoral méditerranéen • Dunes • Lagunes • Zones humides • Avifaune • Ambiances sauvages.<br>
    Observation discrète, respect des distances et attention aux cycles saisonniers.
  </div>

</div>
