# JavaScript
i am starting JavaScript tutorials

<!DOCTYPE html>
<html>
<body>

<h2>My First JavaScript</h2>

<button type="button"
onclick="document.getElementById('demo').innerHTML = Date()">
Click me to display Date and Time.</button>

<p id="demo"></p>
  
----------------------------------
  <h2>What Can JavaScript Do?</h2>

<p id="demo">JavaScript can change HTML content.</p>

<button type="button" onclick='document.getElementById("demo").innerHTML = "Hello JavaScript!"'>Click Me!</button>

---------------------------------
 
<h3>In this case JavaScript changes the value of the src (source) attribute of an image</h3> 
  
  <button onclick="document.getElementById('myImage').src='pic_bulbon.gif'">Turn on the light</button>

<img id="myImage" src="pic_bulboff.gif" style="width:100px">

<button onclick="document.getElementById('myImage').src='pic_bulboff.gif'">Turn off the light</button>
  
---------------------------------

  <h3>JavaScript Statements</h3>
  <p>JavaScript statements are seprated by semicolons.</p>
  
  <p id="demo1></p>
   
  <script>
         let a, b, c;
         a = 5;
         b = 7;
         c = a + b;
  documents.getElementById("demo1").innerHTML = c;
  </script>
  
--------------------------------------------------------
                              
 <h3>JavaScript Variables</h3>

<p>In this example, x is defined as a variable. Then, x is assigned the value of 6:</p>

<p id="demo"></p>

<script>
      let x;
      x = 6;
document.getElementById("demo").innerHTML = x;
</script>
                              
 ------------------------------------------------------
                              
 <h2>Assigning JavaScript Values</h2>

<p>In JavaScript the = operator is used to assign values to variables.</p>

<p id="demo"></p>

<script>
let x, y;
x = 5;
y = 6;
document.getElementById("demo").innerHTML = x + y;
</script>
                            
 ------------------------------------------------------
                             
 <h3>The window.print() Method</h3>
                              
 <p>Click the button to print current page</p>
 
 <button onlick="window.print()">Print this page</button>
                                
------------------------------------------------------------
<h3>JavaScript Statements</h3>
<p>JavaScript code block are written between { and } </p>
                                
 <button type="button onlick="myFunction()">Click Me! </button>
  
  <p id="demo1"></p>
  <p id="demo2"></p>
  
  <script>
    function myFunction() {
    document.getElementById("demo1").innerHTML = "Hello Ranjan";
    document.getElementById("demo2").innerHTML = "How are You?";
    }
  </script>
                              
</body>
</html>
