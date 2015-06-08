# alche-tabcontainer

##Alchemist TabContainer

"alche-tabcontainer" is a polymer element that combine of "[paper-tabs](https://elements.polymer-project.org/elements/paper-tabs)" 
and "[iron-pages](https://elements.polymer-project.org/elements/iron-pages)" to switch between different views.

## Getting Started

### Installing with Bower

First you need `bower`, refer [bower.io](http://bower.io/) for Bower installation.

```sh
$ bower install --save alche-tabcontainer
```

### How to use

Since you are looking for custom polymer elements from other people, so I guess you already have some idea 
what's going on here. If not, please have a look at [polymer](https://www.polymer-project.org).

Put a link to alche-tabcontainer in your header, it should look something like this.

```sh
<link rel="import" href="<path-to-bower_components>/bower_components/alche-tabcontainer/alche-tabcontainer.html">
```

After that, you can start to use it on your page. Example:

```sh
<body>
  <alche-tabcontainer>
    <div title="Tab 1">One</div>
    <div title="Tab 2">Two</div>
    <div title="Tab 3">...</div>
    ...
    ...
  </alche-tabcontainer>
</body>
```

## API Reference

### Styling

| Custom Property | Description | Default |
|-----|-----|-----|
| --alche-tabcontainer-selection-bar-color | Color for the selection bar | #cccceb |
| --alche-tabcontainer-tab-ink | Ink color | #cccceb |
| --alche-tabcontainer-tabs | Mixin applied to the tabs | {} |
| --alche-tabcontainer-tab | Mixin applied to the tab | {} |
| --alche-tabcontainer-tab-content | Mixin applied to the tab content | {} |
| --alche-tabcontainer | Mixin applied to the tabcontainer | {} |
| --alche-tabcontainer-content | Mixin applied to the tabcontainer pages | {} |

### Properties

| Properties | Type | Description | Default |
|-----|-----|-----|-----|
| noBar | {Boolean} | If true, the bottom bar to indicate the selected tab will not be shown. | false |
| noink | {Boolean} | If true, ink ripple effect is disabled. | false |
| noSlide | {Boolean} | If true, the slide effect for the bottom bar is disabled. | false |
| scrollable | {Boolean} | If true, tabs are scrollable and the tab width is based on the label width. | false |
| selected | {String} | Gets or sets the selected view. | "0" |
