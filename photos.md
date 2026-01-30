---
layout: default
title: Photos
permalink: /photos/
---

# Photography

欢迎来到我的摄影作品展示页面。

---

<div class="photo-gallery">
  {% for image in site.static_files %}
    {% if image.path contains 'assets/images/photos' %}
      <div class="photo-item">
        <a href="{{ image.path }}" data-lightbox="gallery">
          <img src="{{ image.path }}" alt="{{ image.name }}">
        </a>
      </div>
    {% endif %}
  {% endfor %}
</div>

<style>
.photo-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
  gap: 20px;
  padding: 20px 0;
}

.photo-item {
  overflow: hidden;
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.photo-item:hover {
  transform: scale(1.05);
}

.photo-item img {
  width: 100%;
  height: 250px;
  object-fit: cover;
  display: block;
}
</style>

---

## 使用说明

将你的摄影作品放在 `assets/images/photos/` 目录下，它们会自动显示在这个页面。

支持的格式：`.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`
