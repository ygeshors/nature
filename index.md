---
layout: default
title: Accueil
nav_order: 1
---

<section class="yn-hero">

  <!-- Bannière pleine largeur -->
  <div class="yn-full">
    <img
      class="yn-banner"
      src="{{ '/assets/images/banner.jpg' | relative_url }}"
      alt="Bannière Yann Nature"
      loading="eager"
    />
  </div>

  <!-- 4 photos (strip) pleine largeur -->
  <div class="yn-full yn-strip-wrap">
    <div class="yn-strip">
      <img src="{{ '/assets/images/strip-1.jpg' | relative_url }}" alt="Photo 1 — Yann Nature" loading="lazy" />
      <img src="{{ '/assets/images/strip-2.jpg' | relative_url }}" alt="Photo 2 — Yann Nature" loading="lazy" />
      <img src="{{ '/assets/images/strip-3.jpg' | relative_url }}" alt="Photo 3 — Yann Nature" loading="lazy" />
      <img src="{{ '/assets/images/strip-4.jpg' | relative_url }}" alt="Photo 4 — Yann Nature" loading="lazy" />
    </div>
  </div>

  <!-- Carte de présentation (centrée, PAS sur la bannière) -->
  <div class="yn-content">
    <div class="yn-card">
      <div class="yn-logo">
        <img
          src="{{ '/assets/images/logo-yann-nature.png' | relative_url }}"
          alt="Logo Yann Nature"
          loading="lazy"
        />
      </div>

      <div class="yn-card-text">
        <h1>Yann GESHORS — Nature &amp; Biodiversité</h1>
        <p class="yn-sub">
          Naturaliste de terrain, passionné par la biodiversité et les paysages du littoral méditerranéen.
          Ici, je partage des carnets d’observation, de la photographie de terrain, des sorties et quelques projets
          liés à l’étude et à la protection du vivant.
        </p>

        <div class="yn-cta">
          <a class="yn-btn yn-btn-dark" href="{{ '/photos/' | relative_url }}">Voir les photos</a>
          <a class="yn-btn yn-btn-light" href="{{ '/carnet/' | relative_url }}">Ouvrir le carnet</a>
          <a class="yn-btn yn-btn-green" href="{{ '/contact/' | relative_url }}">Me contacter</a>
        </div>
      </div>
    </div>
  </div>
</section>

<div class="yn-content">
  <section class="yn-section">
    <h2>Présentation</h2>
    <p class="yn-lead">
      Naturaliste de terrain, je documente le vivant par l’observation et la photographie, avec un attachement
      particulier au littoral méditerranéen. Sur ce site, je partage des sorties, des notes de terrain et des images
      prises sur le vif — une approche sobre, respectueuse, et tournée vers la compréhension des milieux.
    </p>
  </section>

  <section class="yn-section">
    <h2>Ma démarche</h2>
    <div class="yn-grid">
      <article class="yn-mini">
        <h3>🔎 Observer</h3>
        <p>Écoute, discrétion et attention aux indices du vivant (comportements, cycles, milieux).</p>
      </article>
      <article class="yn-mini">
        <h3>📷 Photographier</h3>
        <p>Images prises sur le vif, pour documenter le terrain et transmettre une émotion juste.</p>
      </article>
      <article class="yn-mini">
        <h3>🌿 Transmettre</h3>
        <p>Rendre la nature lisible et accessible, sans la simplifier — par le récit et le partage.</p>
      </article>
    </div>
  </section>

  <section class="yn-section">
    <h2>Explorer</h2>
    <div class="yn-grid">
      <article class="yn-cardlink">
        <h3>🗒️ Carnet de terrain</h3>
        <p>Observations, indices, comportements, notes naturalistes.</p>
        <a href="{{ '/carnet/' | relative_url }}">Accéder →</a>
      </article>

      <article class="yn-cardlink">
        <h3>📸 Photographie</h3>
        <p>Galerie d’images terrain (faune, ambiances, milieux).</p>
        <a href="{{ '/photos/' | relative_url }}">Voir →</a>
      </article>

      <article class="yn-cardlink">
        <h3>🧩 Projets</h3>
        <p>Suivis naturalistes, méthodes, axes de travail, retours d’expérience.</p>
        <a href="{{ '/projets/' | relative_url }}">Découvrir →</a>
      </article>
    </div>

    <div class="yn-note">
      🌊 Littoral méditerranéen • Dunes • Lagunes • Zones humides • Avifaune — observation discrète,
      respect des distances et attention aux cycles naturels.
    </div>
  </section>
</div>
