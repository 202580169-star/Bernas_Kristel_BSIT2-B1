
function setup() {
  createCanvas(600, 400);
  background(0, 100, 180);

  drawFish(150, 120, 1, color(255, 150, 50));
  drawFish(350, 200, 1.3, color(255, 100, 150));
  drawFish(470, 100, 0.8, color(255, 220, 50));

  drawBubble(100, 250);
  drawBubble(280, 300);
  drawBubble(520, 250);

  drawSeaweed(60, 410);
  drawSeaweed(130, 410);
  drawSeaweed(430, 410);

  drawSand();
}

function draw() {
  
}

// Draws a fish using its position, size, and color
function drawFish(x, y, size, fishColor) {
  push();
  translate(x, y);
  scale(size);

  noStroke();
  fill(fishColor);
  ellipse(0, 0, 60, 35);
  triangle(-25, 0, -45, -15, -45, 15);

  fill(255);
  ellipse(18, -5, 9, 9);
  fill(0);
  ellipse(20, -5, 4, 4);

  pop();
}

// Draws a bubble 
function drawBubble(x, y) {
  noFill();
  stroke(200, 240, 255);
  strokeWeight(2);
  ellipse(x, y, 15, 15);
  noStroke();
}

// Draws seaweed 
function drawSeaweed(x, y) {
  let leafHeight = 100;

  stroke(30, 180, 80);
  strokeWeight(7);
  line(x, y, x - 10, y - leafHeight);
  line(x - 10, y - leafHeight, x + 10, y - leafHeight - 40);
  line(x, y - 50, x - 20, y - 70);
  noStroke();
}

// Draws the ocean floor
function drawSand() {
  let sandColor = color(220, 190, 120);

  noStroke();
  fill(sandColor);
  rect(0, 370, width, 30);

  fill(190, 160, 100);
  ellipse(100, 375, 30, 8);
  ellipse(300, 385, 40, 8);
  ellipse(480, 378, 35, 8);

  return sandColor;
}
