# \<butter-github-star\> [![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/JCrestel/butter-github-star)

### This web-component shows the number of stars of a Github repository. 

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="../butter-github-star/butter-github-star.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<butter-github-star user="JCrestel" repository="butter-github-star"></butter-github-star>
```

## Installation
Install the component using [Bower](https://bower.io/)

```$ bower install butter-github-star --save```

## Usage
* Import Web Components's polyfill (if needed):
```html
<script src="../webcomponentsjs/webcomponents.min.js"></script>
```
* Import the component:
```html
<link rel="import" href="../butter-github-star/butter-github-star.html">
```
* Use the component:
```html
<butter-github-star user="JCrestel" repository="butter-github-star"></butter-github-star>
```
### Attributes
Attribute | Type | Mandatory | Description
----------|:----:|:---------:|-------------
`user` | *String* | Yes | User on Github
`repository` | *String* | Yes | Repository of the user

### Styling
`<butter-github-star>` provides the following custom properties for styling:

Custom property | Description | Default
----------------|-------------|----------
`--butter-icon-color` | Color of the star | `--iron-icon-fill-color`
`--iron-icon-fill-color` | Color of the star if `--butter-icon-color` not defined | black
`--butter-background-color` | Background color of left part | #e6ebf1
`--butter-border-color` | Border color | rgba(27,31,35,0.35)
`--butter-font-familly` | Font familly | 'Roboto', 'Noto', sans-serif


## Contributing
1. Fork it!
2. Create your feature branch: ```git checkout -b my-new-feature```
3. Commit your changes: ```git commit -m 'Add some feature'```
4. Push to the branch: ```git push origin my-new-feature```
5. Submit a pull request :D

## License
[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0)