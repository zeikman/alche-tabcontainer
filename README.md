# alche-tabcontainer

##Alchemist TabContainer

"alche-tabcontainer" is a polymer element that combine of "paper-tabs" and "iron-pages" to perform 
"[dijit/layout/TabContainer](https://dojotoolkit.org/reference-guide/1.10/dijit/layout/TabContainer.html)"
likes behavior from dojotoolkit.

## Getting Started

### Install with bower

First you need bower, [see their site](http://bower.io) for details

```sh
$ bower install --save alche-tabcontainer
```

### How to use

Put a link to alche-tabcontainer in your header, it should look something like

```sh
<link rel="import" href="<path-to-bower_components>/bower_components/alche-tabcontainer/alche-tabcontainer.html">
```

Now that you have imported it, you can get to using it on your page

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

#### Running Unit Test