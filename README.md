# Entypo Stylus

Provides pre-defined classes and functions for displaying icons using the
[Entypo][] font-face.


## Installing

    $ npm install entypo-stylus


## Using

To use, just import the library and define the path to your fonts in your
stylus stylesheets.

```css
@import "entypo-stylus"

entypo-define('Entypo', '/path/to/entypo', 'entypo')
entypo-define('Entypo Social', '/path/to/entypo-social', 'entypo-social')
```

And use the classes in your HTML (the icon will be added as a `::before`
pseudo-element):

```html
<li class="entypo-pencil">Edit</li>
```

To see the names for the characters, see the [Entypo Charmap][].

[Entypo]: http://www.entypo.com/
[Entypo Charmap]: http://www.entypo.com/characters/
