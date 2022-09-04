# CSS Masonry Layout

index.html

```html
<div class="masonry">
  <img src="..." alt="..." class="masonry-item">
  <img src="..." alt="..." class="masonry-item">
  <img src="..." alt="..." class="masonry-item">
  ...
</div>
```

style.css

```css
.masonry {
  display: flex;
  flex-wrap: wrap;
}

.masonry-item {
  height: 200px;
  flex-grow: 1; /* use this for masonry layout */
}
```
