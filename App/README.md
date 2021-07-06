# Rainbow - Application
by 세희, 진아

라즈베리파이에서 얻은 데이터를 바탕으로 사용자의 데이터를 효과적으로 볼 수 있도록 구성한 앱

---
## 기술적 요구 사항
- Java, Android Studio
- SQLite
- Retrofit2
- Open Source ['material-calendarview'](https://github.com/prolificinteractive/material-calendarview)
- gradle 구성
- AdobeXD

---
## 기능적 구현 사항
- 메인 페이지에 전체적인 공부량 볼 수 있도록 구성
- 달력UI에 목표 공부량 달성한 날 요일별로 색 다르게 표시
- 목표 시간 설정 페이지
- 최근 3주 동안의 주별 공부량 평가 페이지
- 일간 공부량을 보여주는 일자 페이지


---
## UI 구현
다음 화면으로 구성된다.  

### 달력 화면
<img width="200" src="https://user-images.githubusercontent.com/22738293/97805140-9af02180-1c97-11eb-808b-bfd120d9ca50.jpeg">  

- 달력 형태로 공부 여부를 보여준다.  
- 한달 전까지의 공부 기록을 보여준다.  
- 하루하루의 공부여부를 요일별로 빨강/주황/노랑/초록/파랑/남/보라색으로 나타낸다.  


### 지난 한 달간의 무지개 성적 화면
<img width="200" src="https://user-images.githubusercontent.com/22738293/97805150-aa6f6a80-1c97-11eb-8c26-21e31a00dd97.jpeg">  

- 지난 한달 동안, 일주일 별로 나누어 무지개 성적을 알려준다.  
- 7이 모두 성공하였으면 무지개, 4일 이상 성공하였으면 반무지개, 4일이하 성공하였으면 먹구름을 받는다.  

### 일자 화면
<img width="200" src="https://user-images.githubusercontent.com/22738293/97805146-a3485c80-1c97-11eb-9d20-1c2c1a7aff27.jpeg">  

- 달력 화면에서 일자를 선택하면, 선택한 일자의 일자 화면으로 넘어 간다.  
- 일자화면에서는, 그 일자의 총 공부량과 핸드폰 사용량을 나타내준다.  
- 총 공부량은 텍스트 뿐만 아니라, progress bar 형태로도 보여줘 한 눈에 알기 쉽게 한다.  

### 목표 시간 설정 화면
<img width="200" src="https://user-images.githubusercontent.com/22738293/97805148-a6dbe380-1c97-11eb-90eb-89e29e481752.jpeg">  

- 달력 화면에서 설정아이콘을 누르면, 목표 시간 설정 화면으로 넘어 간다.  
- 타임피커를 통해 목표 시간을 설정할 수 있고 해당 목표시간을 텍스트 뿐만 아니로 토스트 메세지로 명시한다.  
