CASCADING STYLE SHEETS
Rainbow

<h2 style="color: purple;"> Anaconda</h2> 
           
  
  It can also be written as this in a seperate class
           <style>
  h2 {
    color: blue;
  }
</style>
           
           once it is written like this ,the text color of any attribute can be made to change
           
           <style>
  .red-text {
    color: red;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

font size
<style>
  
h1 {
  font-size: 30px;
}
  </style>
  
  font family
  
  <style>
  h1{
       font-family: monospace;
  }
  </style>
  
  note: Never forget your semicolon in the end.
  
  import google fonts👀
  
  Google fonts  is a from a library of web fonts that can be imported into your CSS by the fonts URL
  by pasting the link to the font desired at the top
  of your code block ,that is, before the style class
  you can noew import the font family into your style class
  
  <link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
  <style>
  h2{
  font-family:Lobster;
  }
  
  Degrade fonts
  
  When a font is not available on your browser, it can be degraded to a generic and more common font 
  e.g monospace, sans-serif, sans.
  the command is as follows
  
  p {
  font-family: Helvetica, sans-serif;
}
  
  
  
  
  
  
  
  
  
  
  
  
  </style>
