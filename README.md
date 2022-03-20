# HTML
Anchor

<a href = "..." target = "_blank "> </a>
the target attribute makes it so that the link opens in a new tab

An in-link makes use od the id attribute
To create an internal link, you assign a link's href attribute to a hash symbol # plus the value of the id attribute for the element that you want to internally link to, usually further down the page. You then need to add the same id attribute to the element you are linking to. An id is an attribute that uniquely describes an element.

Below is an example of an internal anchor link and its target element:

<a href="#contacts-header">Contacts</a>
...
<h2 id="contacts-header">Contacts</h2>
onve the in link is click, in the same page where the contacts are you will be taken
no need for the traditional scrolling


Replace the href attribute value with a #, also known as a hash symbol, to create a dead link.
href = "#"

turn an image into a link
Place the existing image element within an a (anchor) element.
<a href="#"><img src="  " alt="  "></a>\

Unordered list
<ul>
  <li> </li>
  <li> </li>
  </ul>
  where this appears in bulleted point
  
  Ordered list
  <ol>
  <li> </li>
  <li> </li>
  </ol>
  where this has a numbering system
  
  input attribute
  <input type = "text">
  
  Y'know that invinsible but visible text inside a text box that you can write on top of, 
  its the place holder
  <input type = "text" placeholder = "write your name here">
  
  
  And Action!
  The action attribute will allow your buttons in your form work i think
  <form action = "https://www.freecatphotoapp.com/submit-cat-photo">
  <input>
  </form>
  
  That big red button😡😡😡!!!
   <form action = "https://www.freecatphotoapp.com/submit-cat-photo">
  <input>
  <button type="submit">submit</button>
  </form>
  
  The radio buttons
  <form>
   <label for="indoor">
    <input id="indoor" type="radio" name="indoor-outdoor">indoor
     </label>

     <label for="outdoor">
     <input id="outdoor" type="radio" name="indoor-outdoor">outdoor
       </label>
  </form>
  
  Checkboxes🐱
   <form>
   <label for="cute">
    <input id="cute" type="checkbox" name="feauture">cute
     </label>

     <label for="demon">
     <input id="demon" type="checkbox" name="feauture">demon
       </label>
  </form>
  
  Value
  it helps identify the option chosen
   <form>
   <label for="indoor">
    <input id="indoor" type="radio" value="indoor" name="indoor-outdoor">indoor
     </label>

     <label for="outdoor">
     <input id="outdoor" value="outdoor" type="radio" name="indoor-outdoor">outdoor
       </label>
  </form>
 
  Checked by default😤
  <form>
  <input type="radio" name="test-name" checked>
  </form>
  
  DIVA😎
  The div element, also known as a division element, is a general purpose container for other elements.
  
  DOCTYPE
  <!DOCTYPE HTML> - HTML5
  <!DOCTYPE> - HTML
  
