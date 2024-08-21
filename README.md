# 차량 코너웨이트 측정 시스템

ICC EV 프로젝트

개발 코드 출처: 아주대 소프트웨어학과 18학번 https://luftaquila.io

### 서비스 URL
https://iccev.github.io/ICCEV

코너웨이트 사용법
1. 가정용 체중계 4개를 개조하여 체중계의 로드셀 신호를 HX711 증폭기로 입력합니다.
2. 아두이노가 증폭된 로드셀 신호를 읽어 차량의 각 바퀴에서의 무게를 측정합니다.
3. Web Serial API 를 통해 웹 브라우저에서 아두이노와 시리얼 통신으로 연결하여 측정한 데이터를 확인합니다.

# 하드웨어
1) 체중계(전체)
4개의 체중계의 회로를 재구성함

[Fig 1. 전체 무게 측정기]



<< 노트북 위치(차량 우측)




(사진 확대해서 보면 어디 체중계인지 다 알 수 있음.)
