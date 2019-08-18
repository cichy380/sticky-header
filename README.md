# Sticky header
Pin a flexible-height header to the top of the viewport in desktop browsers above the scrollable content.

<img src="https://i.ibb.co/pnf28MR/sticky-header.png" width="645" height="320" alt="">

#### CSS
```css
html,
body {
  height: 100%;
  margin: 0;
}
.wrapper {
  height: 100%;
  display: flex;
  flex-direction: column;
}
.content {
  flex: 1;
  overflow: auto;
}
```

#### HTML
```html
<!doctype html>
<html><!-- 100% height -->
    <head>
        <!-- ... -->
    </head>
    <body><!-- 100% height -->
        <div class="wrapper">
            <header>Sticky Header</header>
            <main class="content">
                Content with Lorem ipsum dolor...
            </main>
        </div>
    <body>
</html>
```
Live preview: https://jsfiddle.net/cichy380/aq95g38k/
