---
title: Accueil
nav_order: 1
---

<style>
.justify { text-align: justify; }

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

.titre {
  font-weight: 600;
  font-size: 1.1rem;
  margin-bottom: 6px;
}
</style>

# 🌿 Yann GESHORS — Nature & Biodiversité

![Bannière]({{ "/assets/images/banniere.jpg" | relative_url }})

---

## 👤 Présentation

<div class="justify">

Naturaliste de terrain passionné par la biodiversité et les paysages du littoral méditerranéen, je consacre une grande partie de mon temps à observer, photographier et comprendre les milieux naturels.

Ce site est une vitrine personnelle : un espace pour partager des carnets de terrain, des images et une vision sensible de la nature, entre immersion, respect du vivant et transmission.

</div>

---

## 🌱 Ma démarche

<div class="vitrine">

<div class="carte">
<div class="titre">🔎 Observer</div>
Approche naturaliste basée sur l’écoute, la discrétion et l’attention aux détails du vivant.
</div>

<div class="carte">
<div class="titre">📸 Photographier</div>
La photographie comme outil de mémoire, d’émotion et de sensibilisation à la biodiversité.
</div>

<div class="carte">
<div class="titre">🌿 Transmettre</div>
Partager des connaissances et des ressentis pour reconnecter chacun à la nature.
</div>

</div>

---

## 🧭 Accès rapide

<div class="vitrine">

<div class="carte">
<div class="titre">🗒️ Carnet de terrain</div>
<a href="{{ "/carnet/" | relative_url }}">Explorer les observations</a>
</div>

<div class="carte">
<div class="titre">📸 Photos</div>
<a href="{{ "/photos/" | relative_url }}">Voir les images</a>
</div>

<div class="carte">
<div class="titre">🌱 Projets</div>
<a href="{{ "/projets/" | relative_url }}">Découvrir les projets</a>
</div>

<div class="carte">
<div class="titre">📬 Contact</div>
<a href="{{ "/contact/" | relative_url }}">Me contacter</a>
</div>

</div>
