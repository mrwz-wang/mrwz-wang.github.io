---
title: Gallery
date: 2026-03-25 19:29:56
---

# 图片画廊

<div class="gallery-container">
  <img src="http://tcg9rb9ht.hn-bkt.clouddn.com/img/gallery img/依然.png" alt="依然" class="gallery-item">
  <img src="http://tcg9rb9ht.hn-bkt.clouddn.com/img/gallery img/合照-1.jpg" alt="合照-1" class="gallery-item">
  <img src="http://tcg9rb9ht.hn-bkt.clouddn.com/img/gallery img/合照.jpg" alt="合照" class="gallery-item">
  <img src="http://tcg9rb9ht.hn-bkt.clouddn.com/img/gallery img/周依然.png" alt="周依然" class="gallery-item">
  <img src="http://tcg9rb9ht.hn-bkt.clouddn.com/img/gallery img/巴太.png" alt="巴太" class="gallery-item">
  <img src="http://tcg9rb9ht.hn-bkt.clouddn.com/img/gallery img/我的阿勒泰.png" alt="我的阿勒泰" class="gallery-item">
  <img src="http://tcg9rb9ht.hn-bkt.clouddn.com/img/gallery img/树.png" alt="树" class="gallery-item">
</div>

<style>
.gallery-container {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
  margin: 30px 0;
  justify-content: center;
}
.gallery-item {
  flex: 1 1 300px;
  max-width: 300px;
  height: auto;
  border-radius: 8px;
  cursor: pointer;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}
.gallery-item:hover {
  transform: scale(1.05);
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
}
@media (max-width: 768px) {
  .gallery-item {
    flex: 1 1 45%;
    max-width: 45%;
  }
}
@media (max-width: 480px) {
  .gallery-item {
    flex: 1 1 100%;
    max-width: 100%;
  }
}
</style>