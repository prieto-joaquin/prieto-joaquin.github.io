---
layout: archive
title: "Contacto"
permalink: /es/contact/
author_profile: true
lang: es
lang_alt: /contact/
---

{% include lang-toggle.html %}

<style>
.cf-intro{margin:0 0 1.4em;line-height:1.6;}
.cf-form{max-width:640px;}
.cf-form label{display:block;font-size:1rem;color:#3f4448;margin:0 0 .35em;}
.cf-row{margin-bottom:1.1em;}
.cf-form input,.cf-form textarea{width:100%;box-sizing:border-box;font:inherit;font-size:1rem;color:#333;padding:.6em .7em;border:1px solid #cfd3d6;border-radius:6px;background:#fff;line-height:1.4;}
.cf-form input.cf-narrow{max-width:340px;}
.cf-form input:focus,.cf-form textarea:focus{outline:none;border-color:#52adc8;box-shadow:0 0 0 2px rgba(82,173,200,.18);}
.cf-form textarea{min-height:150px;resize:vertical;}
.cf-send{font:inherit;font-size:.85rem;font-weight:bold;letter-spacing:.6px;text-transform:uppercase;cursor:pointer;color:#fff;background:#52adc8;border:none;border-radius:6px;padding:.7em 1.6em;}
.cf-send:hover{background:#3f97b1;}
</style>

<p class="cf-intro">Si quieres ponerte en contacto, no dudes en escribirme.<br>Haré lo posible por responder a la brevedad.</p>

<form class="cf-form" action="https://formsubmit.co/9a8ca6b4732a3e51e59d8059592f7e50" method="POST">
  <input type="hidden" name="_subject" value="Nuevo mensaje desde tu sitio web">
  <input type="hidden" name="_captcha" value="false">
  <input type="hidden" name="_template" value="table">
  <input type="text" name="_honey" style="display:none">
  <div class="cf-row">
    <label for="cf-name">Nombre</label>
    <input id="cf-name" class="cf-narrow" type="text" name="name" required>
  </div>
  <div class="cf-row">
    <label for="cf-email">Tu correo</label>
    <input id="cf-email" class="cf-narrow" type="email" name="email" required>
  </div>
  <div class="cf-row">
    <label for="cf-message">Mensaje</label>
    <textarea id="cf-message" name="message" required></textarea>
  </div>
  <button class="cf-send" type="submit">Enviar</button>
</form>
