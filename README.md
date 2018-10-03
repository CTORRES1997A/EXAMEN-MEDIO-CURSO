# EXAMEN-MEDIO-CURSO
ANEXO LOS FORMATOS DEL EXAMEN

int u=50;
int t=150;
int y=250;


void setup () {
  size (300,300); 
}
  void draw ()
{
    u= u+1; 
    y= y-1;
background(255);
fill(30,45,70);
//ellipse(xcord,ycord,size,size)
ellipse (u,u,100,100);
ellipse (y,u,100,100);
ellipse (u,y,100,100);
ellipse (y,y,100,100);
}
int x=0;
int y=100;
int z=200;
void setup() {
size(200,200);
}
void draw ()
{
x=x+1;
z= z-1;
background (255);
line (y,x,100,100);
line (z,z,100,100); //inferior derecha
line(x,z,100,100);  //inferior izquierda

}


int x=0;
int click=0;
void setup() {
  size(200,200);
  frameRate(5);
}
void draw()
{
background(255);
fill(255,255,255);
rect(20,20,160,160);
if (mousePressed){
  x=x+1;
}
if (x==1){
fill(255,0,0);
rect(20,20,160,160);}
if (x==2){
fill(0,255,0);
rect(20,20,160,160);
}
if (x==3){
fill(0,0,255);
rect(20,20,160,160);
}
if (x==4){
x=1;}
fill(255);
ellipse(100,100,100,100);
}
int x=0;
int click=0;
void setup() {
  size(200,200);
  frameRate(5);
}
void draw()
{
background(255);
fill(255,255,255);
rect(20,20,160,160);
if (mousePressed){
  x=x+1;
}
if (x==1){
fill(255,0,0);
rect(20,20,160,160);}
if (x==2){
fill(0,255,0);
rect(20,20,160,160);
}
if (x==3){
fill(0,0,255);
rect(20,20,160,160);
}
if (x==4){
x=1;}
fill(255);
ellipse(100,100,100,100);
}

int x=0;
int click=0;
void setup() {
  size(200,200);
  frameRate(5);
}
void draw()
{
background(255);
fill(255,255,255);
rect(20,20,160,160);
if (mousePressed){
  x=x+1;
}
if (x==1){
fill(255,0,0);
rect(20,20,160,160);}
if (x==2){
fill(0,255,0);
rect(20,20,160,160);
}
if (x==3){
fill(0,0,255);
rect(20,20,160,160);
}
if (x==4){
x=1;}
fill(255);
ellipse(100,100,100,100);
}

float x=0;
void setup() {
size(160,220);
  fill(45, 87, 44);
rect(65, 50, 30, 100);}
void draw(){


  if(mousePressed){
 x=random(0,4);
 println(x);}
 if (x<1){
verde();
 }
  if (x>2 && x<3){
rojo();
 }
  if (x>3){
amarillo();
 }

}
void rojo(){
  fill(255,0,0);
ellipse(80, 70, 20, 20);
fill(50, 30, 0);
ellipse(80, 100, 20, 20);
fill(0, 50, 0);
ellipse(80, 130, 20, 20);
}
void verde(){
fill(50,0,0);
ellipse(80, 70, 20, 20);
fill(50,30, 0);
ellipse(80, 100, 20, 20);
fill(0,255, 0);
ellipse(80, 130, 20, 20);}
void amarillo(){
  fill(50,0,0);
ellipse(80, 70, 20, 20);
fill(255, 200, 0);
ellipse(80, 100, 20, 20);
fill(0, 50, 0);
ellipse(80, 130, 20, 20);
}



