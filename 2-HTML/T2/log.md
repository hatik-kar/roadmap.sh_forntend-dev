
# [Learn HTML](https://web.dev/learn/html)

## Overview

* HTML documents are basically a tree of nodes, including HTML elements and text nodes. HTML elements provide the semantics and formatting for documents.

* **Non-replaced elements**: The paragraph, header, and lists marked up in the earlier section are all non-replaced. Non-replaced elements have opening and (sometimes optional) closing tags that surround them and may include text and other tags as sub-elements. These enclosing tags can turn a phrase or image into a hyperlink, can make a sentence into a header, can give emphasis to words, and so on.

* **Replaced and void elements**: Replaced elements are replaced by objects, be it a graphical user interface (UI) widget in the case of most form controls, or a raster or scalable image file in the case of most images. Being replaced by objects, each comes with a default appearance. Depending on the type of object and the browser, the applicable styles are limited. For example, most browsers enable limited styling of UI widgets and related pseudo-elements. In the case of raster images, height, width, clipping, and filtering are easily done with CSS, but not much else. On the other hand, scalable vector graphics, using a markup language based on XML similar to HTML are fully scalable (unless they contain raster images). They are also fully styleable. Note that the ability to style an embedded SVG from the CSS linked to the HTML file that embeds it depends on how the SVG is set up.

In this example, the two replaced elements \<img> and \<input> are replaced by non-text content: an image and a graphical user interface object, respectively.

``` HTML
<input type="range">
<img src=""switch.src" alt="light switch">  
```

* Void elements are all self-closing elements and are represented by one tag. This means there is no such thing as a closing tag for a void element. Optionally, you can include a slash at the end of the tag.

``` HTML
<input type="range"/>
<img src=""switch.src" alt="light switch"/>  
```

* Void elements include \<br>, \<col>, \<embed>, \<hr>, \<img>, \<input>, \<link>, \<meta>, \<source>, \<track>, and \<wbr>, among others. Most void elements are replaced; but again, not all, as we saw with base, link, param, and meta.

### Attributes

``` HTML
src: location
alt: provides alternative text describing the contents
ismap: boolean, doesn't require a value
```

### Apprearence

```HTML
<h1-6></h1-6>
<strong></strong>
<em></em>

```
