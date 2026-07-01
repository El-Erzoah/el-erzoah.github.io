---
layout: archive
title: "Media and Links"
permalink: /media/
author_profile: true
---



Below are selected moments from conferences, teaching, and research activities.

<div class="gallery">

  <figure>
    <img src="/images/BEER_Talks.jpg" onclick="openLightbox(this)">
    <figcaption>Conference Presentation</figcaption>
  </figure>

  <figure>
    <img src="/images/Photo.jpeg" onclick="openLightbox(this)">
    <figcaption>Teaching / Seminar Session</figcaption>
  </figure>

</div>

<!-- Lightbox -->
<div id="lightbox" onclick="closeLightbox()">
  <img id="lightbox-img">
</div>

<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.gallery img {
  width: 100%;
  border-radius: 10px;
  cursor: pointer;
  transition: transform 0.2s ease;
}

.gallery img:hover {
  transform: scale(1.03);
}

figcaption {
  text-align: center;
  font-size: 14px;
  margin-top: 6px;
  color: #555;
}

/* Lightbox */
#lightbox {
  position: fixed;
  display: none;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0,0,0,0.85);
  justify-content: center;
  align-items: center;
  z-index: 999;
}

#lightbox img {
  max-width: 90%;
  max-height: 90%;
  border-radius: 10px;
}
</style>

<script>
function openLightbox(img) {
  const box = document.getElementById("lightbox");
  const boxImg = document.getElementById("lightbox-img");
  box.style.display = "flex";
  boxImg.src = img.src;
}

function closeLightbox() {
  document.getElementById("lightbox").style.display = "none";
}
</script>


my file is named media.md
where should i make the changes

how will this be
