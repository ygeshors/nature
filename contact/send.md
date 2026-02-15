---
title: Envoyer un message
layout: default
nav_exclude: true
---

<style>

.wrap{
  max-width:820px;
  margin:auto;
}

/* BOUTON RETOUR */
.back{
  display:inline-block;
  margin-bottom:14px;
  text-decoration:none !important;
  font-weight:700;
  opacity:.8;
}

.back:hover{
  opacity:1;
}

/* FORMULAIRE */
.form{
  margin-top:14px;
  border:1px solid #e5e7eb;
  border-radius:18px;
  padding:22px;
  background:linear-gradient(180deg,#ffffff,#f8fafc);
  box-shadow:0 10px 24px rgba(0,0,0,.05);
}

label{
  display:block;
  font-weight:800;
  margin:14px 0 6px;
}

input, textarea{
  width:100%;
  border:1px solid #e5e7eb;
  border-radius:14px;
  padding:12px;
  font-size:1rem;
  font-family:inherit;
}

textarea{
  min-height:150px;
}

button{
  margin-top:18px;
  padding:14px 20px;
  border-radius:16px;
  border:1px solid #e5e7eb;
  background:#14532d;
  color:#fff;
  font-weight:900;
  cursor:pointer;
  transition:.2s;
}

button:hover{
  background:#064e3b;
  transform:translateY(-2px);
}

.small{
  opacity:.75;
  margin-bottom:8px;
}

</style>

<div class="wrap">

<a class="back" href="{{ "/" | relative_url }}">← Retour à l’accueil</a>

# ✉️ Envoyer un message

<div class="small">
Question, collaboration photo ou signalement naturaliste.
</div>

<div class="form">

<form action="https://formspree.io/f/meelgnda" method="POST">

<label>Nom</label>
<input type="text" name="name" required>

<label>Email (pour te répondre)</label>
<input type="email" name="email" required>

<label>Message</label>
<textarea name="message" required></textarea>

<button type="submit">🌿 Envoyer le message</button>

</form>

</div>

<br>

<a class="back" href="{{ "/" | relative_url }}">← Retour à l’accueil</a>

</div>
