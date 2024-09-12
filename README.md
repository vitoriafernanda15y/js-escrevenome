# js-escrevenomefunction setup() {
  createCanvas(500, 400);
  background("rgb(110,223,36)");
}

function draw() {
  stroke("blue");
  fill("rgb(187,255,0)");

  // console.log(mouseIsPressed)

  if (mouseIsPressed) {
    rect(mouseX, mouseY, 20, 35);
  }
}