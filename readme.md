# Doppio

Doppio is a small utility pack of styles to help with building MVPs. It has been designed to be
dropped into a project and that is all that is needed. The styles *mostly* apply to raw HTML
elements but additional CSS classes are also provided if they might be needed.

Minimal grey scale styles are primarily used with an optional accent color for links, buttons
and similar.

### Dependencies

* Dart-Sass

### Usage

* Clone the project
* Compile using *Dart-Sass*
* Add to page using a <link> tag
* Basic HTML elements should now have styles applied to them
* Done


### Styles
Doppio provides predefined styles for all raw HTML elements but extra classes are also provided.

#### Buttons

```
<div class="btn-dark"></div>
<div class="btn-light"></div>
<div class="btn-accent"></div>
```

#### Forms

```
<form class="form-inline"></form>
```

#### Grid

```
<div class="grid"></div> // 3 column max grid using CSS Grid
<div class="grid-2"></div> // 2 column max grid using CSS Grid
<div class="grid-4"></div> // 4 column max grid using CSS Grid
```

#### Tables

```
<table class="align-center"></table>
<table class="align-justify"></table>
<table class="align-right"></table>
```

#### Text

```
<div class="text-dark"></div>
<div class="text-light"></div>
<div class="text-accent"></div>
<div class="text-bold"></div>
<div class="text-italic"></div>
<div class="text-underline"></div>
```

#### Anchors

```
<a class="block"></a> // Make the anchor element behave as a block element
```
