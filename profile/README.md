# 🚖 Mini Delivery 🚖
### 자율주행 자동차를 활용한 배달 서비스
<br><br>

### 프로젝트 목적
기존의 배달 서비스 시스템의 단점을 보완하기 위해, <br>
본 프로젝트에서는 UGV(무인지상차량) 에서 영감을 받아 이를 구현하기 위해 자율주행이 가능한 Raspberry Pi 자동차를 활용했다. <br>
프로젝트의 흐름은 다음과 같다. 먼저, 소비자 어플에서 배달 주문이 접수되면, 서버는 해당 데이터를 데이터베이스에 저장한다. <br>
이후, 판매자 어플에서 실시간으로 DB의 배달 정보를 확 인하여 서버로부터 데이터를 받아온다. <br>
주문 접수 후, 조리가 완료되면 Raspberry Pi 자동차 가 배달을 시작한다. <br>
Raspberry Pi 자동차는 전면부에 장착된 카메라를 통해 실시간으로 전 방 상황을 송출한다. <br>
차량은 정해진 라인을 따라 자율주행하며, 신호등의 정지 및 출발 신호 를 인지할 수 있다. <br>
만약 차량이 사람과의 충돌 위험을 감지하면 즉시 멈춰 사고를 방지한다. <br>
<br><br>

## 프로젝트 구조도
![구조도](https://github.com/user-attachments/assets/e944ba6e-40e5-4836-92d5-bb315baade40)
<br><br>

## API 명세서
![공경진 api 명세서](https://github.com/user-attachments/assets/ab47ee31-7b99-487e-b349-3699b65a0bf1)
<br><br><br>

## 주요 적용 기술
- Kotlin을 이용한 소비자 및 업체측 배달 서비스 어플 제작<br>
- Springboot 프레임워크를 활용해 만든 서버로 데이터 전달 및 저장<br>
- JPA(Java Persistence API)를 이용하여 객체지향적 데이터베이스 작업 수행<br>
- Raspberry 4B를 활용한 센서 데이터 처리 및 차량 모터 제어<br>
- Raspberry picamera 모듈을 이용한 실시간 송출 화면 제작<br>
- 스레드를 활욜한 멀티태스킹 및 CPU 자원관리<br>
- opencv, opencvdnn을 이용한 객체 인식 및 주행 경로 추적<br>
<br><br>

## 기술 스택
🔴 FE : Android Studio / Kotlin<br><br>
🟠 BE : Spring Boot / Java<br><br>
🟡 AI : OpenCV / Flask / Raspberry pi<br><br>
🟢 Design : Figma<br><br>
🔵 Collab Tool : Github<br><br>
🟣 Communication : Discord<br><br>
