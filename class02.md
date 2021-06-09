# Reading: Basics of HTML, CSS & JS


## Cheat Sheets
 
 - Tags are set inside brackets <> and </>

| Headers      | Description |
| ----------- | ----------- |
| h1 | Main Header |
| h2 | Level 2 Header |
| h3 | Level 3 Header |
| h4 | Level 4 Header |
| h5 | Level 5 Header |
| h6 | Level 6 Header |

<hr/>

| Text Formatting | Description |
| --------------- | ----------- |
| b | Bold |
| i | italics |
| sup | superscript |
| sub | subscript |
| strong | Boldens |
| em | italics |

<hr/>

| Varying elements | Description |
| ------------ | ----------- |
| abbr | used to specify the full term of an abbreviation |
| cite | used when referencing books *note should not be used for persons name |
| dfn | used when an explanation is needed for unfamiliar terminology |
| address | will contain the information for the author of a page *may contain physical address but not necessary |
| ins | will show content that got inserted |
| del | will show content that got deleted |
| s | will indicate information that is no longer relevant |


## Visual Editors and Code Views
  
  - Resemble word processors but allow you to control the presentation.

## Code Views
 - Shows the code created by visual editors

## Blockquotes
 - These are used to annotate longer quotes.

<hr/>

## CSS

CSS is insterted in 3 fashions:
    * External CSS
    * Internal CSS
    * Inline CSS

    -External CSS
        * Can change the presenetation of an entire website by utilizing a separate file.
        * Each HTML page must have a reference inserted. This is defined with <link>.
            Example:<link rel="cssstylesheet" href="style.css">

        * Can be written in any text editor. ### Must be saved with .css extension.
        * Shouldn't contain HTML tags.

    -Internal CSS
        * May be used if you'd only like to style one singular HTML page.
        * Defined with the <style> element. (Placed in side head section.)
            Example: <head>
                     <style>
                     h1 {color: wierd'
                     }
                     </style>
                     </head>

    -Inline CSS
        * Used to apply styling for singular elements within an HTML doc.
        * Also defined by using 'style'.
            Example: <p style="text-align:center;">

Cascading Order:
    - So what if there is more than one specified 'style' for HTML elements? It will 'cascade' into a new style sheet following the rules below. Top to bottom it will generate:

        *Inline style
        *External and internal style sheets 
        *Browser default
<hr/>

## JavaScript

## JavaScript Variables
    
    Variables = Containers for Storing Data Values
    Example:
        - var r = 20;
        - var x = 15;
        - var u = 17
        - so on and so forth.
    This will read as:
        - variable r will store the value of 20
        - variable x will store the value of 15
        - variable u will store the value of 17
        -etc.
 

    By using the keyword var, we are able to make computations similar to that of algebra
    Example: (without the word let)
        let: var cost1 = 16;
        let: var cost2 = 200;
        let: var total = cost1 + cost2;      
 

        This should compute out to be 216
 

        Notice that the variables cost1 and cost2 have different names. In order for this to execute your variabels will require unique names. Those are known as identifiers.
         - cost1 is and identifier same as cost 2
 

## Assignment Operators
    Assignment operators are identified by an (=) symbol.
    *NOTE: THIS DOES NOT MEAN EQUAL. Think of it more of as a replacement.
        Example:
             x = 34 + x
             This will read out as the value of 34 + x will be assigned to  x
             This means the value of x will increase by increments of 34

Operators and Loops
Loops
Loops offer quick and easy ways to repetitively do something.
Kinds of loop statments:
    - for
    - do
    - while
    - labeled
    - break
    - continue
    - for... in
    - for... of

for Statement - this will loop repetitively until a specific condition gives a false return.
    Example:
        - for ([initialExpression]; [conditionExpression]; [incrementExpression])
            statement
do...while Statement - same as above repeats until specific  condition evaluates to false.
    Example:
        - do
            statement
        while (condition);
while Statement - executes statements as long as specified condition evaluates to true. If condition returns false it will stop.
    Example:
        - let n = 0;
          let x = 0;
          while (n < 3) {
            n++;
            x += n;
        }