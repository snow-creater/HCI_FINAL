# Draw your own mask! (Leapmotion, Unity) 
![Demo Image](/image/0.png)

## Members
김예빈, 김예안, 류태동, 정슬기

## Abstract
이 프로젝트는 Leap Motion으로 자신만의 마스크를 3차원 공간에서 디자인하는 과정을 통해 사용자가 공익 캠페인에 자연스럽게 참여하게 해줍니다.

## Background 
코로나가 전세계에 퍼지면서 비말을 통해 번지는 바이러스의 특성상 공공장소에서 마스크를 쓰고 사람들이 많이 모이는 곳에 최대한 가지 않는 것은 당연한 것이 되었습니다. 그렇기 때문에 사람들은 통신 기술을 통해서만 소통을 하고 코로나 블루같은 우울증에 시달리기도 하였습니다. 그런 상황이기에 저희는 VR 기술을 이용해 집안에만 있는 것에 지친 사람들에게 새로운 자극도 주고 코로나가 창궐하는 시대에 마스크를 착용하는 것이 얼마나 중요한지 다시 한번 느끼게 하는 프로젝트를 계획하였습니다.

## Goal 
Leap Motion을 통해 3차원 공간에서 자신의 손을 이용하는 흥미로운 경험을 준다
자신만의 마스크를 디자인할 수 있다
사회적 문제들에 대해 사람들이 쉽게 접근할 수 있도록 진입 장벽을 낮춘다
직접 참여할 수 있는 캠페인을 만든다

## Main Contents (2명)
1. Hand Interaction   
![Drawing Picture](/image/1.png)   

      
립모션의 모션인식 기능 중에 pinch, spread palm, finger touch를 주로 사용합니다. pinch는 엄지 손가락과 집게 손가락을 오므리는 동작으로 그림을 그리는 기능을 위해 사용됩니다. pinch상태일 때는 손가락 끝에서 펜이 나오고, spread palm 상태일 때는 멈춥니다. finger touch는 한 손가락으로 터치하는 동작으로 버튼을 누를 때 사용됩니다.


2.Scene Interaction 

* Home Scene   
![Home](/image/2.png)   
간략한 프로그램의 설명이 적혀 있는 main scene입니다.
 (start 버튼 -> drawing scene으로 이동) 


* Drawing Scene   
![Drawing](/image/3.png)   
나만의 마스크를 디자인하는 drawing scene입니다.
(home 버튼 -> home scene으로 이동
 gallery 버튼 -> gallery scene으로 이동 
share 버튼 -> 공유할지 묻는 팝업창
save 버튼 -> 저장할지 묻는 팝업창 
print -> 프린트 할지 묻는 팝업창 -> 퀴즈)  

* Gallery Scene   
![Gallery](/image/4.png)   
디자인 한 마스크가 저장되어 갤러리처럼 볼 수 있는 gallery scene입니다.
(home 버튼 -> home scene) 

* Quiz Scene   
![Quiz](/image/5.png)   
디자인 한 마스크를 프린트하기 전에 퀴즈를 풀 게 하는 quiz scene입니다.

2. Button Interaction   
![Button Interaction](/image/6.png)   
앞서 설명한 scene interaction과 관련해서 button과 scene의 관계를 그림으로 나타냈습니다.


## Step by step instructions
1.  실행 파일 다운로드 https://github.com/snow-creater/HCI
3.  립모션 다운로드 및 연결 https://developer.leapmotion.com/sdk-leap-motion-controller
4.  실행 파일 실행

## Results
데모 영상 
순서: 홈-스타트-그리기-홈-갤러리-쉐어-세이브-프린트-퀴즈-홈
소스코드!!

## Conclusion 
결론

## References
레퍼런스
오픈소스, 논문, 기능들
 

