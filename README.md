<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
    <style media="screen">
      body{
        background-color:red;
      }
      ul li{
        color:red
      }
    </style>


  </head>
  <body style="background-color:powderblue;">
    <h1>Robotics and Coding </h1>
      <!-- <button type="button" onclick="alert('Welcome to Hornsby Robot Coding Class')"> Click Me to see the message</button> -->


      <button type="button" name="button" onclick="bFunction()">
        Click Me to see the message
      </button>
      <script type="text/javascript">
        function bFunction(){
          alert("Welcome to Hornsby Robot Coding Class");
        }
      </script>

      <h2 style="color:red;"> What is Coding?</h2>

        If you want to change some properties of the contents between start tag
        and end tag, what can you add in the start tag?<br>

        <form name="question">
        <input type="radio" name="answer" value="nothing"> nothing<br>
        <input type="radio" name="answer" value="blank"> blank<br>
        <input type="radio" name="answer" value="attribute"> attribute<br>
        <button type="reset" name="button"> Reset</button>
        </form>

        <p id="test">Coding is a tool for mathematics. Through learning fun coding, kids will learn how mathematics is closely related to coding. It is also a tool that helps improve logical thinking skills, guiding kids to reach out to different areas successfully. Coding is demanded and required. At the same time, learning to code will advantage and benefit your kids in future.</p>

        <button onclick="document.getElementById('test').innerHTML='This paragraph was changed.'"> Let's change the paragraph above</button><br>

    
        <h2> Scratch</h2>
        Using Scratch Projects, kids improve:
        <ul>
          <li> <a href="#problemSolve"> Problem-solving (Debugging)</a></li>
          <li> <a href="#logical"> Logical and Critical thinking skills</li> </a>
          <li> <a href="#codingSimul"> Coding simulations of what happens in everyday life</li> </a>
        </ul>
        naturally while having the interests to learn and enjoy our programs.

        <h3> Problem-solving</h3>
        <div style="display:table;width:100%;height:600px;border:1px solid red;">
        <div id="problemSolve" style="display:table-cell;width:99%;height:600px;background-color:yellow;">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Aliquam ut porttitor leo a diam sollicitudin tempor. Pellentesque nec nam aliquam sem et tortor consequat id porta.
        </div>
        </div>

        <h3> Logical and Critical thinking skills</h3>
        <div style="display:table;width:100%;height:600px;border:1px solid blue;">
        <div id="logical" style="display:table-cell;width:99%;height:600px;background-color:grey;">
        rej ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Vitae suscipit tellus mauris a diam maecenas sed enim ut. Scelerisque fermentum dui faucibus in.
        </div>
        </div>

        <h3> Coding simulations of what happens in everyday life</h3>
        <div style="display:table;width:100%;height:600px;border:1px solid yellow;">
        <div id="codingSimul" style="display:table-cell;width:99%;height:600px;background-color:lightgreen;">
        gres ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Feugiat in fermentum posuere urna nec tincidunt praesent semper feugiat.
        </div>
        </div>

      <h3> This is practice for &ltul&gt &ltli&gt </h3>
      <h4> My hobby lists </h4>

      <ul>
      <li> soccer </li>
      <li> piano </li>
      <li> robot and coding </li>
      </ul>

  </body>
</html>
