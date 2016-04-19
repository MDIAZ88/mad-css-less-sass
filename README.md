#CSS-LESS-SASS

####CSS

###### Selectors

* **Universal Selector**

>The universal selector works selecting all elements on a page. Every HTML
page is built on content placed within HTML tags. Each set of tags represents
an element on the page.

  <dl>
      <dd>* {</dd>
      <dd> color: green;</dd>
      <dd> font-size: 20px;</dd>
      <dd> line-height: 25px;</dd>
      <dd>}</dd>
  </dl>


* **Element type Selector**

>this selector must match one or more HTML elements of the same name.

  <dl>
      <dd>p {</dd>
      <dd> font-size: 20px;</dd>
      <dd>}</dd>
  </dl>

* **ID Selector**

>This selector matches any HTML element that has an ID attribute with the same
 value as that of the selector.

  <dl>
      <dd>#container {</dd>
      <dd> width: 960px;</dd>
      <dd>  margin: 0 auto;</dd>
      <dd>}</dd>
  </dl>

* **Class Selector**

>The class selector also matches all elements on the page that have their class
attribute set to the same value as the class.

  <dl>
      <dd>.box {</dd>
      <dd> padding: 20px;</dd>
      <dd> margin: 10px;</dd>
      <dd> width: 240px;</dd>
      <dd>}</dd>
  </dl>

* **Descendant Combinator**

>The descendant selector or, more accurately, the descendant
combinator lets you combine two or more selectors so you can be more
specific in your selection method.
This declaration block will apply to all elements that have a class of box that
 are inside an element with an ID of container.

  <dl>
      <dd>#container .box {</dd>
      <dd> padding: 20px;</dd>
      <dd>}</dd>
  </dl>

* **Child Combinator**

  <dl>
      <dd>#container > .box {</dd>
      <dd> float: left;</dd>
      <dd>}</dd>
  </dl>

* **General Sibling Combinator**

  <dl>
      <dd>h2 ~ p {</dd>
      <dd> margin-bottom: 20px;</dd>
      <dd>}</dd>
  </dl>

* **Adjacent Sibling Combinator**

  <dl>
      <dd>p + p {</dd>
      <dd> margin-bottom: 20px;</dd>
      <dd>}</dd>
  </dl>

* **Attribute Selector**

  <dl>
      <dd>input[type] {</dd>
      <dd> width: 200px;</dd>
      <dd>}</dd>
  </dl>

* **Pseudo-class**

  <dl>
      <dd>a:hover {</dd>
      <dd> color: red;</dd>
      <dd>}</dd>
  </dl>

* **Pseudo-element**

  <dl>
      <dd>.container:before {</dd>
      <dd> width: 200px;</dd>
      <dd>}</dd>
  </dl>
