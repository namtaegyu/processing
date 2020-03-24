PFont f;

void setup(){

  size(800,300);
  
  textSize(72);
  
  f = createFont("굴림",64);
  
  textFont(f);
  
}

int i, dir=1,sp = 1;

void draw(){

  fill(255,100,100);
  
  background(255);
  
  text("안동대 컴공 사랑합니다.",80,i);
  
  if(i>height) i=0;
  
  i=i+dir*sp;
  
}

void keyPressed(){

  sp = key-'0';
  
}
