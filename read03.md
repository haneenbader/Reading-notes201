# Read: 03 - HTML Lists, CSS Boxes, JS Control Flow

_**Html book : Chapter 3: “Lists”**_
**What is the type of list in html ?**
 1. Ordered lists :each item in the list is
numbered
<ol>
<li> item of list </li>
<li> item of list </li>
<li> item of list </li>
<li> item of list </li>
</ol>

2. Unordered lists : begin with a bullet point
<ul>
<li> item of list </li>
<li> item of list </li>
<li> item of list </li>
<li> item of list </li>
</ul>

 3. Definition lists :  list to definitions set of  terms 
<dl>
<dt>This is used to contain the term being defined (the definition term).</dt>
<dd>This is used to contain the definition </dd>
</dl>

 **how we use the nested list  ?**
 by put a second list inside an element to create a sublist 

_**Html book : Chapter 13: “Boxes”**_
_Controlling size of boxes_
Box diminution :
width, height: To set your own dimensions for a box Limiting Width
min-width: property specifies the smallest size a box can be displayed at when the browser window is narrow 
max-width:  property indicates the maximum width a box can stretch to when the browser window is wide.
Limiting Height : min and max height : to limit the height of box 
Overflowing Content  (overflow )  if the content contained within a box is larger than the box itself. , it have tow value :
1. hidden : hides any extra content
2. scroll : adds a scrollbar to the box

_Border, Margin & Padding_ 
Border  :The border separates the edge of one box from another
Margin  : to create a gap between the borders of two adjacent boxes.
Padding : space between the border of a box and any content contained within it.

*Why we use The padding and margin properties  ?*
helpful in adding space between various items on the page.
**Border** 
* border-width : in pixels or using one of the following values: thin ,medium ,thick
* border-style : This property can take the following values: solid , dotted , dashed ,double , groove , ridge , inset , outset , screen hidden / none .
* border-color
* Shorthand border: The border property allows you to specify the width, style and color of a border in one property (and the values should be coded in that specific order).


**Padding** : specify how much space should appear between the content of an element and its border.
**Margin** : controls the gap between boxes

_example for Border, Margin & Padding  :_

p {
    width: 200px; 
    border: 2px solid #0088dd; 
    padding: 10px;
   }
p.example {
    margin: 20px;
  }


_**js book : Chapter 2: “Basic JavaScript Instructions”**_
ARRAYS An array is a special type of variable. It doesn't just store one value; it stores a list of values.
We can Update the  item in the array , Get the element with an id of colors and Replace with item from the array 


_**js book : Chapter 4: “switch statements”**_
* switch statements allow you to compare a value against possible outcomes (and also provides a default option if none match).
switch (value){
    case (): 
    code;
    break;
    default : 
    code ;
}
* Data types can be coerced from one type to another.
* All values evaluate to either truthy or falsy. 
* There are three types of loop: for, while, and do ... while. Each repeats a set of statements



