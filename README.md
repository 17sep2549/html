# html<!DOCTYPE html>
<html>
<body>

<canvas id="myCanvas" width="400" height="400" style="border:5px solid #000000;">
Your browser does not support the HTML canvas tag.</canvas>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
var n =5;
for (let i = 1; i < n; i++) {
  ctx.moveTo(i/n*(c.width),0);
  ctx.lineTo(i/n*(c.width),c.height);
 
  ctx.moveTo(0,i/n*(c.height));
  ctx.lineTo(c.width,i/n*(c.height),);
  ctx.stroke();
}


ctx.stroke();
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<canvas id="myCanvas" width="300" height="300" style="border:2px solid #d3d3d3;">
Your browser does not support the HTML canvas tag.</canvas>

<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");


ctx.moveTo(100,0);
ctx.lineTo(100,300);
ctx.stroke();

ctx.moveTo(200,0);
ctx.lineTo(200,300);
ctx.stroke();

ctx.moveTo(0,100);
ctx.lineTo(300,100);
ctx.stroke();


ctx.moveTo(0,200);
ctx.lineTo(300,200);
ctx.stroke();


</script>

</body>
</html>

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript For Loop</h2>

<p id="demo"></p>

<script>
let text = "";

for (let i = 1; i < 50; i++) {
  text += "The number is " + i + "<br>";
}

document.getElementById("demo").innerHTML = text;
</script>

</body>
</html>
