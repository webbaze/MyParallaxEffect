# MyParallaxEffect
  Первым делом подключаем библиотеку jquery. Как обычно, между тегами head:
  ```bash
  <script src="//ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
  ```
  
  Скачиваем и подключаем скрипт Parallax Effect.
  ```bash
  <script src="путьдофайла/parallax.min.js"></script>
  ```
  Теперь, давайте разберемся, что нужно прописать на html страничке, чтобы заработал наш параллакс эффект.
  
```html
<header class="head" data-parallax="scroll" data-image-src="путьдофайла/bg.png">
<h1>ВашТекст</h1>
</header>
```
   
That's all.
