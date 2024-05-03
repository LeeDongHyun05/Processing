```
//함수를 호출한다 function call
//주석 처리 : 프로세싱이 무시하고 건너뛰게 됩니다.

// 창의 크기 설정
size(300,200);

// red,green,blue
background(200); //배경색을 설정하는 명령어

//point(x,y) // 점을 그리는 명령어
point(150,100);
point(151,100);
point(152,100);
point(153,100);
point(154,100);

//line(x1,y1,x2,y2); // 선을 그리는 명령어
line(0,0,300,200);
line(300,0,0,200);

//rect(x,y,w,h); // 사각형을 그리는 명령어
rectMode(CENTER);
strokeWeight(4); // 점과 선의 두께를 변경하는 명령어
stroke(0,0,255); // 점과 선의 색을 설정하는 명령어 noStroke() 선의 색을 없애는 명령어 (이 명령어를 사용하면 점과 선을 그릴 수 없음
rect(150,100,50,50);


//ellipse(x,y,w,h); // 원을 그리는 명령어
//ellipseMode(CORNER);
strokeWeight(5);
stroke(0); 
noFill(); // filㅣ() 도형의 배경색을 설정하는 명령어 noFill() 도형의 배경색을 없애는 명령어
ellipse(150,100,120,120);

//text(글자,x,y); // 글자를 표시하는 명령어
//textSize(크기) // 글자 크기를 변경하는 명령어
//textFont(폰트) 글꼴을 변경하는 명령어 PFont형 변수
//createFont(폰트,크기) 글꼴을 생성하는 명령어
textSize(30);
text("Hello",200,100);

PFont font = createFont("NanumGothic",30);
textFont(font);

text("Hello",200,150);

//image(그림,x,y,w,h) 그림을 표시하는 명령어 Plamge형 변수
//loadimage(그림) 그림 파일을 불러오는 명령어
PImage img = loadImage("ball.jpg");
image(img,5,10,200,100);
```
