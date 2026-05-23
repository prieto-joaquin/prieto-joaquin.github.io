---
layout: archive
title: "Outreach"
permalink: /outreach/
author_profile: true
---

<style>
.tabnav{display:flex;flex-wrap:wrap;gap:8px;margin:0 0 1.5em;padding:0;}
.tabnav button{font:inherit;font-size:16px;cursor:pointer;background:#fff;border:1px solid #ddd;border-radius:6px;padding:7px 14px;color:#494e52;line-height:1.2;box-shadow:none;}
.tabnav button:hover{background:#f2f3f3;}
.tabnav button[aria-selected="true"]{border-color:#52adc8;background:#52adc8;color:#fff;}
.tabpane[hidden]{display:none;}
.tabpane ul{margin:0;padding-left:1.25em;}
.tabpane li{margin-bottom:.7em;}
.out-act{font-size:.8em;border:1px solid #ccc;border-radius:5px;padding:1px 9px;color:#52adc8;text-decoration:none;white-space:nowrap;margin-left:5px;}
.out-act:hover{border-color:#52adc8;background:#52adc8;color:#fff;}
</style>
<div class="tabnav" role="tablist" aria-label="Outreach sections">
<button type="button" role="tab" data-tab="columns" aria-selected="true">Op-Eds</button>
<button type="button" role="tab" data-tab="interviews" aria-selected="false">Interviews</button>
<button type="button" role="tab" data-tab="podcast" aria-selected="false">Podcast</button>
</div>
<div class="tabpane" data-panel="columns" role="tabpanel">
<ul>
<li><strong>CASEN 2024: el diagnóstico apresurado sobre pobreza y subsidios</strong> (with Dante Contreras). <em>El País</em>, 17 January 2026. <a class="out-act" href="https://elpais.com/chile/2026-01-17/casen-2024-el-diagnostico-apresurado-sobre-pobreza-y-subsidios.html" target="_blank" rel="noopener">Link</a> <a class="out-act" href="/files/columnas/2026.01.17-Pobreza_CASEN_2024-El%20Pais.pdf" target="_blank" rel="noopener">PDF</a></li>
<li><strong>Resultados CASEN 2024: pobreza severa y desventajas acumuladas</strong> (with Dante Contreras). <em>La Tercera</em>, 9 January 2026. <a class="out-act" href="https://www.latercera.com/opinion/noticia/resultados-casen-2024-pobreza-severa-y-desventajas-acumuladas/" target="_blank" rel="noopener">Link</a> <a class="out-act" href="/files/columnas/2026.01.09-Pobreza_CASEN_2024-La%20Tercera.pdf" target="_blank" rel="noopener">PDF</a></li>
<li><strong>Más allá del ingreso: Desigualdad multidimensional en Chile</strong> (with Dante Contreras). <em>La Tercera</em>, 30 December 2025. <a class="out-act" href="https://www.latercera.com/opinion/noticia/mas-alla-del-ingreso-desigualdad-multidimensional-en-chile/" target="_blank" rel="noopener">Link</a> <a class="out-act" href="/files/columnas/2025.12.30-Desigualdad%20Multidimensional-La%20Tercera.pdf" target="_blank" rel="noopener">PDF</a></li>
<li><strong>Pobreza multidimensional en Chile: una década y sus lecciones</strong> (with Dante Contreras). <em>La Tercera</em>, 3 December 2025. <a class="out-act" href="https://www.latercera.com/opinion/noticia/pobreza-multidimensional-en-chile-una-decada-y-sus-lecciones/" target="_blank" rel="noopener">Link</a> <a class="out-act" href="/files/columnas/2025.12.03-Pobreza%20Multidimensional-La%20Tercera.pdf" target="_blank" rel="noopener">PDF</a></li>
<li><strong>Pobreza en Chile: un nuevo estándar</strong> (with Dante Contreras). <em>La Tercera</em>, 20 November 2025. <a class="out-act" href="https://www.latercera.com/opinion/noticia/pobreza-en-chile-un-nuevo-estandar/" target="_blank" rel="noopener">Link</a> <a class="out-act" href="/files/columnas/2025.11.20-Pobreza%20en%20Chile-La%20Tercera.pdf" target="_blank" rel="noopener">PDF</a></li></ul>
</div>
<div class="tabpane" data-panel="interviews" role="tabpanel" hidden>
<ul>
<li><strong>"Donde hubo pactos duraderos que coordinaron política económica y política social, hubo reducción de desigualdad"</strong>. <em>Facultad de Gobierno, Universidad de Chile</em>, April 2026. <a class="out-act" href="https://gobierno.uchile.cl/noticias/239557/joaquin-prieto-donde-hubo-pactos-duraderos-que-coordinaron" target="_blank" rel="noopener">Link</a></li></ul>
</div>
<div class="tabpane" data-panel="podcast" role="tabpanel" hidden>
<ul>
<li><strong>Voces de la Facultad de Gobierno: Investigación en Acción</strong> — Episode 11. Conversation with Joaquín Prieto on economic insecurity: what it means, how it is measured in Chile, and its political and social impacts. <em>Facultad de Gobierno, Universidad de Chile</em> &middot; March 2026 &middot; 27 min. <a class="out-act" href="https://open.spotify.com/episode/3GVAoeOuC4JCGTkjTj4QaS" target="_blank" rel="noopener">Spotify</a></li></ul>
</div>
<script>
(function(){
  var tabs=[].slice.call(document.querySelectorAll('.tabnav button'));
  var panels=[].slice.call(document.querySelectorAll('.tabpane'));
  var names=tabs.map(function(t){return t.getAttribute('data-tab');});
  function activate(name){
    if(names.indexOf(name)===-1){name='columns';}
    tabs.forEach(function(t){t.setAttribute('aria-selected', t.getAttribute('data-tab')===name?'true':'false');});
    panels.forEach(function(p){p.hidden=(p.getAttribute('data-panel')!==name);});
  }
  tabs.forEach(function(t){t.addEventListener('click',function(){var n=t.getAttribute('data-tab');activate(n);if(window.history&&history.replaceState){history.replaceState(null,'','#'+n);}});});
  activate((window.location.hash||'').replace('#',''));
})();
</script>
