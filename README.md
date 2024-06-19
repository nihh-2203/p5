function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
}function setup() {
  createCanvas(400, 400);
  background("white");
}

function draw() {
}
function draw() {
  circle(200,200,50);
}
function draw() {
  fill("red");
  circle(200,200,50);
}<p xmlns:cc="http://creativecommons.org/ns#" >Este trabalho está licenciado sob <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/?ref= selector-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-ND 4.0<img style="height:22px!important;margin-left:3px ;alinhamento vertical:fundo do texto;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical -align:texto inferior;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical -align:texto inferior;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical -align:texto inferior;" src="https://mirrors.creativecommons.org/presskit/icons/nd.svg?ref=chooser-v1" alt=""></a></p>

let cor;

function setup() {
  createCanvas(400, 400);
  background("white");
}
function setup() {
  createCanvas(400, 400);
  background("white");
  cor = "blue";
}
function draw() {
  fill(cor);
  circle(200,200,50);
}
function setup() {
  createCanvas(400, 400);
  background("white");
  cor = color(0, 255, 0);
}
random(0, 255);
function setup() {
  createCanvas(400, 400);
  background("white");
  cor = color(random(0, 255), 0, 0);
}
function setup() {
  createCanvas(400, 400);
  background("white");
  cor = color(random(0, 255), random(0, 255), random(0, 255));
}
function setup() {
  createCanvas(400, 400);
  background("white");
  cor = color(random(0, 255), random(0, 255), random(0, 255));
  posicaoHorizontal = 200;
  posicaoVertical = 200;
}
function draw() {
  
  fill(cor);
  circle(posicaoHorizontal, posicaoVertical, 50);
}
if(mouseX < posicaoHorizontal) {
    posicaoHorizontal = posicaoHorizontal - 1;
}
function draw() {
  
  fill(cor);
  circle(posicaoHorizontal, posicaoVertical, 50);
  
  if(mouseX < posicaoHorizontal) {
    posicaoHorizontal = posicaoHorizontal - 1;
  }
  
  if(mouseX > posicaoHorizontal) {
    posicaoHorizontal = posicaoHorizontal + 1;
  }
}
if(mouseX < posicaoHorizontal) {
    posicaoHorizontal--;
}
  
if(mouseX > posicaoHorizontal) {
    posicaoHorizontal++;
}
if(mouseY < posicaoVertical) {
    posicaoVertical--;
}
  
if(mouseY > posicaoVertical) {
    posicaoVertical++;
}
function draw() {
  
  fill(cor);
  circle(posicaoHorizontal, posicaoVertical, 50);
  
  if(mouseX < posicaoHorizontal) {
    posicaoHorizontal--;
  }
  
  if(mouseX > posicaoHorizontal) {
    posicaoHorizontal++;
  }
  
  if(mouseY < posicaoVertical) {
    posicaoVertical--;
  }
  
  if(mouseY > posicaoVertical) {
    posicaoVertical++;
  }
  
}
function setup() {
  createCanvas(400, 400);
  background(color(100, 0 , 0));
  cor = color(random(0, 255), random(0, 255), random(0, 255));
  posicaoHorizontal = 200;
  posicaoVertical = 200;
}
if(mouseIsPressed){
    
}
if(mouseIsPressed){
    cor = color(random(0, 255), random(0, 255), random(0, 255));
}
if(mouseIsPressed){
    cor = color(random(0, 255), random(0, 255), random(0, 255), random(0, 100));
}
