--- 
layout: page
title : Exploring the Dataset 
permalink: /gallery/
position: 2
---

### Click through for Neuroglancer views.

<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(2, 1fr);  /* Exactly 2 columns */
  gap: 2rem;
  margin-top: 2rem;
  justify-items: center;
}

.card {
  max-width: 600px;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
  background-color: white;
  transition: transform 0.2s ease;
  text-align: center;
  text-decoration: none;
}

.card:hover {
  transform: translateY(-4px);
}

.card img {
  width: 100%;
  display: block;
}

.card-body {
  padding: 1rem;
}

.card-title {
  font-weight: bold;
  font-size: 1.1rem;
  margin-bottom: 0.25rem;
  color: #222;
}

.card-text {
  font-size: 0.95rem;
  color: #666;
}
</style>

<div class="gallery">
  <a class="card" href="https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/4784619693015040" target="_blank">
    <img src="{{ 'assets/img/smi-cmi-mon-imi.png' | relative_url }}" alt="Integrator neurons">
    <div class="card-body">
      <div class="card-title">Integrator and Motion onset neurons </div>
      <div class="card-text">From Boulanger-Weill et al., 2025</div>
    </div>
  </a>

  <a class="card" href="https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/6690669807534080" target="_blank">
    <img src="{{ 'assets/img/rs.png' | relative_url }}" alt="Motor command neurons">
    <div class="card-body">
      <div class="card-title">Reticulospinal neurons</div>
      <div class="card-text">From Boulanger-Weill et al., 2025</div>
    </div>
  </a>

  <a class="card" href="https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/5782310145228800" target="_blank">
    <img src="{{ 'assets/img/glia.png' | relative_url }}" alt="Motor command neurons">
    <div class="card-body">
      <div class="card-title">Glia in the Optic tectum</div>
      <div class="card-text">Reconstructed by Jay Savaliya @ U. Regina</div>
    </div>
  </a>

  <a class="card" href="https://spelunker.cave-explorer.org/#!middleauth+https://global.daf-apis.com/nglstate/api/v1/6668149414952960" target="_blank">
    <img src="{{ 'assets/img/rgcs.png' | relative_url }}" alt="Raphe neurons">
    <div class="card-body">
      <div class="card-title">Retinal ganglion cells projecting to the Optic tectum</div>
      <div class="card-text">From Putti et al., 2025 - Reconstructed by Jay Savaliya @ U. Regina</div>
    </div>
  </a>
</div>