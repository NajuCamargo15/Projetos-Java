function setup() {
  createCanvas(600, 600);
  background("black");
}

function draw() {
    
    stroke("white") 
    fill("purple") 
    
  //console.log (mouseIsPressed);

  if (mouseIsPressed) {
  rect(mouseX, mouseY, 20, 35); /* 0, 0 em cima e esq,dir e p baixo  */ 
}
}
    
