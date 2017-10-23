[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/supachailllpay/photo-gallery)

# \<photo-gallery\>

A photo gallery element based on Polymer

## Example

<!--
```
<custom-element-demo>
  <template>
    <script src='../webcomponentsjs/webcomponents-lite.js'></script>
    <link rel='import' href='photo-gallery.html'>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<photo-gallery height='120'>
  <div class='item' data-url='https://images.unsplash.com/photo-1500487003906-9baadc8d610d?auto=compress,format&fit=crop&w=334&h=&q=80&aspect-ratio=0.67'></div>
  <div class='item' data-url='https://images.unsplash.com/photo-1483653085484-eb63c9f02547?auto=compress,format&fit=crop&w=750&h=&q=80&aspect-ratio=1.50'></div>
  <div class='item' data-url='https://images.unsplash.com/photo-1499958919714-e10d2741a387?auto=compress,format&fit=crop&w=334&h=&q=80&aspect-ratio=0.67'></div>
  <div class='item' data-url='https://images.unsplash.com/photo-1503263892381-7f7fd5e5ec15?auto=compress,format&fit=crop&w=376&h=&q=80&aspect-ratio=0.75'></div>
  <div class='item' data-url='https://images.unsplash.com/photo-1429554429301-1c7d5ae2d42e?auto=compress,format&fit=crop&w=750&h=&q=80&aspect-ratio=1.50'></div>
  <div class='item' data-url='https://images.unsplash.com/photo-1501422955948-a75c84b11ecf?auto=compress,format&fit=crop&w=752&h=&q=80&aspect-ratio=1.50'></div>
  <div class='item' data-url='https://images.unsplash.com/photo-1455796653466-32048b2b780e?auto=compress,format&fit=crop&w=749&h=&q=80&aspect-ratio=1.50'></div>
  <div class='item' data-url='https://images.unsplash.com/photo-1463414689943-2aca18b2242b?auto=compress,format&fit=crop&w=750&h=&q=80&aspect-ratio=1.78'></div>
  <div class='item' data-url='https://images.unsplash.com/photo-1428976365951-b70e0fa5c551?auto=compress,format&fit=crop&w=750&h=&q=80&aspect-ratio=1.50'></div>
  <div class='item' data-url='https://images.unsplash.com/photo-1500284306430-8f3cad668bb2?auto=compress,format&fit=crop&w=750&h=&q=80&aspect-ratio=1.50'></div>
</photo-gallery>
```

## Installation

```shell
$ bower install --save supachailllpay/photo-gallery
```

## Properties

* `height` (number) - The height (px) of each item, default is `240`

* `selected` (number) - The index of current item, default is `-1`

## Methods

* `open()` - Enter to full screen, event target must be descendant of item

* `close()` - Exit from full screen

## License

[MIT](http://opensource.org/licenses/MIT)
