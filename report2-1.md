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

소감 : 이번 프로세싱 시간에는 text 배너를 생성한 뒤, 좌우로 왔다갔다하며, 키보드 숫자를 눌렀을 시에
속도를 조절할 수 있는 과제를 해보았습니다. 이 프로세싱을 처음 하였지만 교수님께서 인터넷 강의 시간에
잘 알려주시고 카페에 정보들이 많아 잘 따라 갈 수 있는 거 같습니다.  감사합니다. 수업 열심히 따라가
겠습니다. 컴퓨터공학과 화이팅! 그래픽스 화이팅!
