# first-darhi
just trying a css animation

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    
    <title>welcome</title>
  </head>
  <body>
    <center><h1>welcome to the darhi web</h1></center>
    <br />
    <center><h3>please press the button</h3></center><br>
    <center><h3>if you don't press it you're gay </h3></center>
    <br /><br />
    <center><button>button</button></center>

    <style>
      h1{
        background-color: rgb(10, 98, 98);
      }
      
  
  button{
    background-color: red;
  position: relative;
  animation-name: example;
  animation-duration: 1s;
  animation-timing-function: linear;
  animation-delay: 1s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
}

@keyframes example {
  0%   {background-color:red; left:0px; top:0px;}
  25%  {background-color:yellow; left:200px; top:0px;}
  30%  {background-color:yellow; top:0px; right:400px;}
  40%  {background-color:yellow; top:400px; right:0px;}
  50%  {background-color:blue; left:200px; top:200px;}
  75%  {background-color:green; left:0px; top:200px;}
  85%  {background-color:green; left:0px; top:300px;}
  95%  {background-color:green; left:100px; top:200px;}
  100% {background-color:red; left:0px; top:0px;}
}
  
  
    </style>
  </body>
</html>
