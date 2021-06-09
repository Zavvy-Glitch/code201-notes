# HTML Lists, CSS Boxes, JS Control Flow

## HTML Lists

- Types:
  - ordered
  - unordered

### Ordered Lists
 * Created by using the ol element
 * Subsequent list items are annotated with the <.li> <./li> tags. (without the period)
 
### Unordered Lists
 * Created by using the ul element
 * Same as ordered lists subsequent listed items will be annotated with the <.li> tags.

### Definition Lists
 * Created with the dl elemeent
 * Inside the element you'll see either dt or dd elements.
* dt for the term to be defined
* dd will contain the entire defintion

### Nested Lists
 * a list within a list
    - such as this
      - it will be a continuation of a new list.

### Boxes

* each element inside an HTML document will be contained within its own box.
  * these boxes can be resized and shifted
  * can have borders
  * margins and padding can be expanded or minimized
  * can be shown or hidden

### Dimensions

By default a box will be sized according to the size of the contents inside.

<u>Usage</u>
  
  <b>(width / height)</b>
  
  Example in HTML:

  <.div>
    <.p>Something Something Something <./p>
    <./div>


 <b> Example in CSS : </b>
  
  div {

    height: 9999px
    width: 9999px
  }

