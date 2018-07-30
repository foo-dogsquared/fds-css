# fds-css-lib
My first attempt to create a CSS library. Also it will serve to make creating layouts for my apps to be a lot easier.

For now, this will be a lightweight CSS library that utilizes CSS grid through simple declarations of classes in each element. Although there is only one grid and the rest are... something else, I guess.

See the demo in [here](https://foo-dogsquared.github.io/fds-css).

## Documentation
This is made using SCSS for an easier time constructing this stylesheet as it gets a little more complex later on.

Anyways, there is one main way on how to utilize this library so far and that is through the `<body>` tag. For this to (mostly) work, declare the `plain-grid-layout` class to the previously mentioned element. This will now enable the grid. Now there are mainly three componenets that makes up the usual layout: the `<header>`, `<main>`, `<footer>`, and the wrappers that is contained within each of them.

For an easier demonstration, here's the boilerplate in order to get the library to be fully working:
```html
    <body id="plain-grid-layout">
        <header><div class="wrapper header">Lorem, ipsum.</div></header>
        <main><div class="wrapper main">
            <div>Element 1</div>
            <div>Element 2</div>
            <div>Element 3</div>
        </div></main>
        <footer><div class="wrapper footer">Lorem ipsum dolor sit.</div></footer>
    </body>
```

The header and footer over there are already have `flex` as the display value so you might want to go place your sublayouts according to individual containers.

Well, if you are familiar with Jekyll, you might notice that the stylesheet is *pretty much* inspired from the [default stylesheet of the default theme](http://jekyll.github.io/minima/) albeit with a few tweaks, obviously.

You can expand this little layout library as much as you want as long as you credit me (I'm speaking as if anybody will be interested in this, lol).

### Different layouts
Yeah, there is different choices on layouts now even though most (or all) or them are still in development. You can see each 
layout (except for the unsure ones) in the demo page.