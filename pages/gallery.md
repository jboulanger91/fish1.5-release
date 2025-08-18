--- 
layout: page
title : Exploring the Dataset 
permalink: /gallery/
position: 3
---

#### Click through for Neuroglancer views.
<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(2, 1fr); /* Exactly 2 columns on desktop */
  gap: 2rem;
  margin-top: 2rem;
  justify-items: center;
  padding: 2rem 1rem;
  background-color: #f9f9f9; /* subtle background */
  border-radius: 12px;
}

.card {
  max-width: 550px;
  border-radius: 10px;
  overflow: hidden;
  background-color: white;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  text-align: center;
  text-decoration: none;
}

.card:hover {
  transform: translateY(-6px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.15);
}

.card img {
  width: 100%;
  height: auto;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
  display: block;
}

.card-body {
  padding: 1.2rem 1rem;
}

.card-title {
  font-weight: 700;
  font-size: 1.2rem;
  margin-bottom: 0.5rem;
  color: #111;
}

.card-text {
  font-size: 0.95rem;
  color: #555;
  line-height: 1.4;
}

/* Optional: Responsive layout for smaller screens */
@media (max-width: 768px) {
  .gallery {
    grid-template-columns: 1fr;
  }
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