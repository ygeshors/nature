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

.form{
  margin-top:14px;
  border:1px solid #e5e7eb;
  border-radius:16px;
  padding:20px;
  background:#ffffff;
}

label{
  display:block;
  font-weight:800;
  margin:14px 0 6px;
}

input, textarea{
  width:100%;
  border:1px solid #e5e7eb;
  border-radius:12px;
  padding:12px;
  font-size:1rem;
  font-family:inherit;
}

textarea{
  min-height:150px;
}

button{
  margin-top:16px;
  padding:12px 18px;
  border-radius:14px;
  border:1px solid #e5e7eb;
  background:#111827;
  color:#fff;
  font-weight:900;
  cursor:pointer;
}

button:hover{
  background:#0b1220;
}

.small{
  opacity:.75;
  margin-bottom:8px;
}

</style>

<div class="wrap">

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

<button type="submit">Envoyer le message</button>

</form>

</div>
</div>
