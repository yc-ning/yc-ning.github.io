---
layout: page
title: Yu-Chien Ning - Biography
description: >
  A brief biography of Dr. Yu-Chien Ning, assistant professor in statistics at  
  Texas A&M University in College Station, TX, United States. 
heading: Biography
nav-title: Biography
permalink: /bio/
order: 2
---
Dr. Yu-Chien Bo Ning is an assistant professor in the Department of Statistics at Texas A&M University. His research focuses on developing trustworthy Bayesian machine learning methods for data science, supported by three pillars of research:
<div class="research-dropdowns-row">
  <div class="dd-block">
    <button class="dd-toggle" data-target="panel-theory">
      <span>Theoretical foundations</span>
      <span class="chevron">+</span>
    </button>
    <div id="panel-theory" class="dd-panel">
      <span class="dd-item">High-dimensional</span>
      <span class="dd-item">Nonparametric</span>
      <span class="dd-item">Deconvolution/measurement error</span>
      <span class="dd-item">Survival models</span>
      <span class="dd-item">GP/deep GP (theory)</span>
      <span class="dd-item">Multiscale analysis</span>
      <span class="dd-item">Uncertainty quantification</span>
    </div>
  </div>
  <div class="dd-block">
    <button class="dd-toggle" data-target="panel-algo">
      <span>ML algorithms</span>
      <span class="chevron">+</span>
    </button>
    <div id="panel-algo" class="dd-panel">
      <span class="dd-item">Sampling methods</span>
      <span class="dd-item">Variational inference</span>
      <span class="dd-item">Bayesian optimization</span>
      <span class="dd-item">GP-based algorithms</span>
    </div>
  </div>
  <div class="dd-block">
    <button class="dd-toggle" data-target="panel-ds">
      <span>Data science</span>
      <span class="chevron">+</span>
    </button>
    <div id="panel-ds" class="dd-panel dd-panel-right">
      <span class="dd-item">Astronomy</span>
      <span class="dd-item">Epidemiology</span>
      <span class="dd-item">Economics</span>
      <span class="dd-item">Electronic health records</span>
      <span class="dd-item">Genomics</span>
    </div>
  </div>
</div>
Previously, he held positions at Harvard HSPH (Research Associate), UC Davis (Visiting AP), Sorbonne Université in Paris (FSMP Postdoctoral Fellowship), and Yale (Postdoc). He obtained a Ph.D. in Statistics at North Carolina State University.
<style>
.research-dropdowns-row {
  display: flex;
  gap: 10px;
  margin: 2px 0 1.2em 0;
  font-family: inherit;
}
.dd-block {
  flex: 1;
  position: relative;
}
.dd-toggle {
  width: 100%;
  background: #ffffff;
  color: #000000;
  border: 1px solid #000000;
  border-radius: 6px;
  padding: 5px 8px;
  font-family: inherit;
  font-size: inherit;
  font-weight: inherit;
  cursor: pointer;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 4px;
}
.dd-toggle:hover {
  background: #f2f2f2;
}
.chevron {
  font-size: inherit;
  line-height: 1;
  transition: transform 0.2s ease;
  flex-shrink: 0;
}
.dd-toggle.open .chevron {
  transform: rotate(45deg);
}
.dd-panel {
  display: none;
  position: absolute;
  top: 100%;
  left: 0;
  width: 220px;
  background: #ffffff;
  border: 1px solid #000000;
  border-radius: 0 0 6px 6px;
  padding: 6px 0;
  z-index: 1000;
}
.dd-panel-right {
  left: auto;
  right: 0;
}
.dd-panel.open {
  display: block;
}
.dd-panel .dd-item {
  color: #000000;
  background: #ffffff;
  padding: 5px 16px;
  display: block;
  font-family: inherit;
  font-size: inherit;
  font-weight: inherit;
}
</style>
<script>
document.querySelectorAll('.dd-toggle').forEach(function (btn) {
  btn.addEventListener('click', function () {
    var panel = document.getElementById(btn.dataset.target);
    btn.classList.toggle('open');
    panel.classList.toggle('open');
  });
});
</script>
