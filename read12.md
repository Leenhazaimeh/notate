# Chart.js, Canvas

EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS:
chart type :
1. bar charts
2. line charts
3. pie charts





at first download Chart.js.....then Copy the Chart.min.js out ... and into the directory  worke in... Then create a new html page and import the script.... then create a canvas element in our HTML....to the body `<canvas id="buyers" width="600" height="400"></canvas>`.....and add this to the foot of your body element:`<script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
</script>`now we can create our data,



##  pie chart :
 First,..`<canvas id="countries" width="600" height="400"></canvas>` the canves elemant ,now I can added my data .


 # Creating a Chart: 
  script tag with the canves id :
   ```<canvas id="myChart" width="400" height="400"></canvas>```
```<script></script>```

in side the script tag you have to add the data .
use  getContext(),mithode to obtain rendering 

 how to draw on the canvas ?
 to draw rectangles : fillRect(x, y, width, height),strokeRect(x, y, width, height),clearRect(x, y, width, height), all thes funcion used to draw rectangels.
  to draw paths : beginPath(),Path methods,closePath(),stroke(),fill()
  Drawing a triangle:

  .........

  function draw() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    ctx.beginPath();
    ctx.moveTo(75, 50);
    ctx.lineTo(100, 75);
    ctx.lineTo(100, 25);
    ctx.fill();
  }
}



..........



Drawing text :by two methods :
fillText(text, x, y [, maxWidth])
strokeText(text, x, y [, maxWidth])

