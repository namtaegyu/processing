void setup(){

  size(800,400);
  
  textSize(128);
  
}

int i, dir = 1, sp=1;

void draw(){

  fill(0,125,255);
  
  background(0,255,0);
  
  text("Graphics", i , 200);
  
  if(i>width) dir= -1;
  
  if(i<0) dir=1;
  
  i = i+dir*sp;
  
}

void keyPressed(){

  sp = key -'0';
  
}

