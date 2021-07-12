# 🌈 Rainbow 
"공부 시간 기록의 자동화"를 목적으로 진행한 프로젝트입니다.


## ⚽️ 기술적 접근, 목표

- 필요 목적 외 핸드폰 사용 방지: [Network](https://github.com/sea1hee/Rainbow/tree/main/RPi)  
  - 의미없는 핸드폰 사용을 감지할 네트워크 패킷 캡처
  - 라즈베리파이를 이용해 네트워크 접속 패킷, 게임 중 발생하는 패킷 감지

- 사용자 착석여부 판단, 다양한 알림 활용: [RPi](https://github.com/sea1hee/Rainbow/tree/main/RPi)  
  - 사용자 근처의 물리적 데이터 수집을 위한 라즈베리파이
  - 사용자의 착석 여부를 확인할 수 있는 초음파 센서
  - 사용자에게 알림을 줄 수 있는 Buzzer 센서

- AWS 클라우드 서버 활용: [API, DB](https://github.com/sea1hee/Rainbow/tree/main/API%2C%20DB)  
  - 라즈베리파이로부터 얻은 데이터를 저장할 서버
  - 적절한 비용으로 많은 양의 데이터 보관

- [App](https://github.com/sea1hee/Rainbow/tree/main/App)  
  - 언제 어디서나 쉽게 확인 가능
  - 성취감을 줄 수 있도록 기능 구성 및 UI 채택

## 🏛 프로젝트 구조

![overall](https://user-images.githubusercontent.com/22738293/124556114-dcfae400-de72-11eb-8aeb-e0fa8accd931.png)  

![rpi](https://user-images.githubusercontent.com/22738293/124556174-ef751d80-de72-11eb-9c7f-28f4b2599594.png)  

![aws](https://user-images.githubusercontent.com/22738293/124556225-fb60df80-de72-11eb-8bfc-de5921d3cd89.png)  

![app](https://user-images.githubusercontent.com/22738293/124556252-0582de00-de73-11eb-9f42-d738fd562530.png)  


## 🤼 역할 분배
- Android - 강세희, 이진아  
- DB, Server - 최용욱, 김성수 
- Network - 서예진
- RPi - 김성수


