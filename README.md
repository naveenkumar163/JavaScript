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
                              
 <h3>Assigning JavaScript Values</h3>

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
  
  -----------------------------------------
  <h3>the <b>let</b> keywords creates Variables</h3>
  
  <p id="demo"></p>
  
  <script>
  let x, y;
    x = 5 + 6;
    y = x * 5;
    
    document.getElementById("deno").innerHTML = y;
  </script>  
 ---------------------------------------------------------
  <h3>JavaScript Const</h3>
  <p>Declaring a constant array does NOT make the elements unchangeble:</p>
  
  <p id="demo"></p>

  <script>
  // Create an Array:
  const cars = ["Saab", "Volvo", "BMW"];

  // Change an element:
  cars[0] = "Toyota";

  // Add an element:
  cars.push("Audi");

  // Display the Array:
  document.getElementById("demo").innerHTML = cars;
    </script>
  
---------------------------------------------------------
  <h3>JavaScript Arithmetic</h3>
  
  <p>A typical arithmetic operation takes two numbers (or expressions) and produces a new number.</p>
  
  <p id="demo"></p>
  
  <script>
    let a = 3;
    let x = (100 + 50)* a;
    
    document.getElementById("demo").innerHTML = x;
    
  </script>
--------------------------------------------------------------
  
 <h3>Math.pow()</h3>

  <p id="demo"></p>

  <script>
  let x = 5;
  document.getElementById("demo").innerHTML = Math.pow(x,2);
  </script>
  
------------------------------------------------------------
  
 <h3>JavaScript Assignments</h3>
 <h4>The *= Operator</h4>

 <p id="demo"></p>

 <script>
 let x = 10;
 x += 5;
 document.getElementById("demo").innerHTML = x;
 </script>
------------------------------------------------------------
  <h2>JavaScript Strings</h2>

  <p>You can use quotes inside a string, as long as they don't match the quotes surrounding the string:</p>

  <p id="demo"></p>

  <script>
  let answer1 = "It's alright";
  let answer2 = "He is called 'Johnny'";
  let answer3 = 'He is called "Johnny"';

  document.getElementById("demo").innerHTML =
  answer1 + "<br>" + 
  answer2 + "<br>" + 
  answer3;
  </script>
  
</body>
</html>
