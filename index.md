---
title: Accueil
nav_order: 1
---

<style>
.justify { text-align: justify; }

.hero {
  display: grid;
  grid-template-columns: 1.2fr 1fr;
  gap: 18px;
  align-items: center;
  margin: 10px 0 18px 0;
}

.hero img {
  width: 100%;
  border-radius: 16px;
  border: 1px solid #e5e7eb;
  background: #fff;
}

.hero h1 { margin: 0 0 6px 0; }
.hero .tagline { font-size: 1.05rem; opacity: .85; margin: 0 0 12px 0; }
.badges { display:flex; flex-wrap:wrap; gap:8px; margin: 10px 0 14px 0; }
.badge { padding:6px 10px; border:1px solid #e5e7eb; border-radius:999px; background:#fafafa; font-size:.9rem; }
.cta { display:flex; flex-wrap:wrap; gap:10px; margin-top: 12px; }
.btn {
  display:inline-block;
  padding:10px 14px;
  border-radius: 12px;
  border:1px solid #e5e7eb;
  background:#fff;
  text-decoration:none;
  font-weight:600;
}
.btn.primary { background:#111827; color:#fff; border-color:#111827; }
.btn:hover { text-decoration:none; transform: translateY(-1px); }

.vitrine {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px,1fr));
  gap: 18px;
  margin-top: 20px;
}
.carte {
  padding: 18px;
  border-radius: 14px;
  border: 1px solid #e5e7eb;
  background: #fafafa;
  transition: transform .2s ease, box-shadow .2s ease;
}
.carte:hover {
  transform: translateY(-4px);
  box-shadow: 0 6px 18px rgba(0,0,0,0.08);
}
.titre { font-weight: 700; font-size: 1.05rem; margin-bottom: 6px; }
@media (max-width: 900px){ .hero{ grid-template-columns:1fr; } }
</style>

<div class="hero">
  <div>
    <h1>🌿 Yann GESHORS — Nature & Biodiversité</h1>
    <p class="tagline">Photographie de terrain • Carnets naturalistes • Littoral méditerranéen</p>

    <div class="badges">
      <div class="badge">🔎 Observation</div>
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
