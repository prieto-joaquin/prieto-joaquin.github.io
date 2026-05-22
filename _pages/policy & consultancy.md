---
layout: archive
title: "Policy"
permalink: /policy/
author_profile: true
redirect_from:
  - /policy-consultancy/
---

<style>
.tabnav{display:flex;flex-wrap:wrap;gap:8px;margin:0 0 1.5em;padding:0;}
.tabnav button{font:inherit;font-size:16px;cursor:pointer;background:#fff;border:1px solid #ddd;border-radius:6px;padding:7px 14px;color:#494e52;line-height:1.2;box-shadow:none;}
.tabnav button:hover{background:#f2f3f3;}
.tabnav button[aria-selected="true"]{border-color:#52adc8;background:#52adc8;color:#fff;}
.tabpane[hidden]{display:none;}
.tabpane li{margin-bottom:.6em;}
.tabpane h3{margin:.25em 0 .5em;font-size:1.15em;}
</style>
<div class="tabnav" role="tablist" aria-label="Policy sections">
<button type="button" role="tab" data-tab="policybrief" aria-selected="true">Policy Briefs</button>
<button type="button" role="tab" data-tab="technical" aria-selected="false">Technical Reports</button>
<button type="button" role="tab" data-tab="projects" aria-selected="false">Projects</button>
</div>
<div class="tabpane" data-panel="policybrief" role="tabpanel">
<ul>
<li>Mesa del Trabajo del Futuro. (2025). <strong>Chile tiene futuro desde sus territorios: Oportunidades frente a los cambios en el mundo laboral</strong>. Policy Brief, Proyecta Chile 2050. (In Spanish). <a href="https://cfstorage.sfo3.cdn.digitaloceanspaces.com/pch2050/docs/trabajo-del-futuro.pdf" target="_blank"> Download </a></li>
<li>Prieto, J. (2025). <strong>Vulnerabilidad a la pobreza en Chile: hacia una medición oficial y políticas preventivas</strong>. En Matus, T. & Urquiza, A. (eds.), <em>El tiempo lento de Chile</em>. Publicaciones Universidad de Chile. (In Spanish).</li>
<li>Maurizio, R., & Prieto, J. (2022). <strong>Poverty and the phenomenon of the working poor</strong>. En Labor Review 2022. Lima: OIT: Oficina Regional para LAC. (In Spanish). <a href="https://mexico.un.org/sites/default/files/2023-02/panorama_laboral_Am%C3%A9ricaLatinayelCaribe_2022_OIT.pdf" target="_blank"> Download </a></li>
<li>Maldonado, L., Prieto, J. and Lay, S. (2016). <strong>The dynamics of poverty in Chile during the period 2006-2009</strong>. Agenda theme series Nº 87, <em>Centro UC de Políticas Públicas</em>. (In Spanish). <a href="https://politicaspublicas.uc.cl/wp-content//uploads/2016/08/N%C2%B0-87-Din%C3%A1micas-de-la-pobreza-en-Chile.pdf" target="_blank"> Download</a></li>
</ul>
</div>
<div class="tabpane" data-panel="projects" role="tabpanel" hidden>
<h3>Data infrastructure</h3>
<ul>
<li>2012  PI, <strong>Origin-Destination Survey</strong> (18,000 households). Financed by the <em>Transport Secretary from Transport Ministry</em>.</li>
<li>2012  PI, <strong>Cadastre of Slums Households</strong> (30,000 households). Financed by the <em>Ministry of Housing and Urban Development</em>.</li>
<li>2011  PI, <strong>Households Financial Panel Survey</strong> (4,000 households). Financed by the <em>Chilean Central Bank</em>.</li>
<li>2011  PI, <strong>Homeless People Cadastre</strong> (12,500 individuals). Financed by the <em>Ministry of Social Development</em>.</li>
<li>2010  PI, <strong>National Narcotics Research</strong> (17,000 individuals). Financed by the <em>National Council for the Control of Narcotics</em> (CONACE).</li>
<li>2010  PI, <strong>National Socioeconomic Characterization Panel Survey (CASEN) Post Earthquake</strong> (22,000 households). Financed by the <em>Ministry of Social Development</em>.</li>
<li>2009  PI, <strong>National Socioeconomic Characterization Survey (CASEN)</strong> (74,300 households). Financed by the <em>Ministry of Social Development</em>.</li>
<li>2009  PI, <strong>National survey of Employment, Health and Quality of Life of Chilean Workers</strong> (9,720 workers). Financed by the <em>Health Ministry</em>.</li>
<li>2009  PI, <strong>Panel CASEN Survey 2006-2007-2008-2009</strong> (7,000 households / 23,000 individuals). Financed by the <em>Ministry of Social Development</em>.</li>
<li>2009  PI, <strong>Panel Survey of Microenterprises</strong> (3,000 households). Financed by the <em>Ministry of Economy</em>.</li>
<li>2009  PI, <strong>Housing Panel Survey</strong> (first wave) - (5,100 housing). Financed by the <em>Ministry of Housing and Urban Development</em>.</li>
<li>2009  PI, <strong>Health National Survey</strong> (5,058 individuals). Financed by the <em>Health Ministry</em>.</li>
</ul>
</div>
<div class="tabpane" data-panel="technical" role="tabpanel" hidden>
<ul>
<li>Prieto, J (2015), <strong>A Practical Handbook to Using Data in the Longitudinal Social Protection Survey (LSPS)</strong>, <em>Social Security Observatory of Latin America and the Caribbean, Inter-American Development Bank</em>. <a href="/files/2015-Prieto-IDB.pdf" target="_blank"> Download </a></li>
<li>Prieto, J., Madrigal, L., Gallegos, F. y Bravo, E. (2015), <strong>Methodological Recommendations for the Longitudinal Social Protection Survey (LSPS)</strong>, <em>Social Security Observatory of Latin America and the Caribbean, Inter-American Development Bank</em>. <a href="/files/2015-Prieto_et_al-IDB.pdf" target="_blank"> Download </a></li>
<li>Paredes, R., Prieto J., & Zubizarreta J. (2006). <strong>Attrition in Longitudinal Data and Income Mobility in Chile</strong>. Mimeo. <em>Observatorio Social, Universidad Alberto Hurtado</em>. <a href="/files/2006-Paredes et al-Mimeo_OSUAH.pdf" target="_blank"> Download </a></li>
</ul>
</div>
<script>
(function(){
  var tabs=[].slice.call(document.querySelectorAll('.tabnav button'));
  var panels=[].slice.call(document.querySelectorAll('.tabpane'));
  var names=tabs.map(function(t){return t.getAttribute('data-tab');});
  function activate(name){
    if(names.indexOf(name)===-1){name='policybrief';}
    tabs.forEach(function(t){t.setAttribute('aria-selected', t.getAttribute('data-tab')===name?'true':'false');});
    panels.forEach(function(p){p.hidden=(p.getAttribute('data-panel')!==name);});
  }
  tabs.forEach(function(t){t.addEventListener('click',function(){var n=t.getAttribute('data-tab');activate(n);if(window.history&&history.replaceState){history.replaceState(null,'','#'+n);}});});
  activate((window.location.hash||'').replace('#',''));
})();
</script>
