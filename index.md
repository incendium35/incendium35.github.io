
 <html>
 <head>
   <title>燎熒 Incendium</title>
   <link rel="icon" type="image/ico" sizes="64x64" href="favicon.ico">

   <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/0.6.1/p5.js"></script>
   <script>

   var canvas;

function setup() {
canvas = createCanvas(window.innerWidth, window.innerHeight);
}

function draw() {
background(51);
fill(255);
ellipse(width/2,height/2,100,100);
}

window.onresize = function() {
var w = window.innerWidth;
var h = window.innerHeight;  
canvas.size(w,h);
width = w;
height = h;
};


   </script>
 </head>
 </html>
