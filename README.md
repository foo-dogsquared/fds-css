# fds-css-lib
My first attempt to create a CSS library. Also it will serve to make creating layouts for my apps to be a lot easier.

For now, this will be a lightweight CSS library that utilizes CSS grid through simple declarations of classes in each element. Although there is only one grid and the rest are... something else, I guess.

See the demo in [here](https://foo-dogsquared.github.io/fds-css).

## Documentation
This is made using SCSS for an easier time constructing this stylesheet as it gets a little more complex later on.

Anyways, there is one main way on how to utilize this library so far and that is through the `<body>` tag. For this to (mostly) work, declare the `plain-grid-layout` class to the previously mentioned element. This will now enable the grid. Now there are mainly three componenets that makes up the usual layout: the `<header>`, `<main>`, `<footer>`, and the wrappers that is contained within each of them.

For an easier demonstration, this is how the plain boilerplate in order to get the library to be fully working:
```html
    <body class="plain-grid-layout">
        <header><div class="wrapper header">Lorem, ipsum.</div></header>
        <main><div class="wrapper main">
            <div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat fugit saepe id accusantium dolor, sunt adipisci inventore illum ratione quas.</div>
            <div>Explicabo sint animi id quo similique quasi rem alias, tenetur possimus debitis impedit, vero architecto ab doloribus, beatae quas voluptatum!</div>
            <div>Velit ut eius impedit eum! Libero minima nisi excepturi quo, blanditiis expedita itaque aspernatur adipisci voluptates assumenda ex quos at.</div>
        </div></main>
        <footer><div class="wrapper footer">Lorem ipsum dolor sit.</div></footer>
        <script src="main.js"></script>
    </body>
```