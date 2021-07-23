# smart_air_conditioner_project

구형 에어컨을 홈어시스턴트를 이용해 컨트롤하는 프로젝트

주요 기능   
1. 리모컨 대신 휴대폰만으로 에어컨 조절 가능
~~2. 집에 가까이 오면 자동으로 에어컨 켜기~~   
3. 온습도 모니터링

주요 재료   
esp 보드   
IR 수신부   
IR 발광부   
라즈베리파이   
온습도센서   

제작 현황   
1. 환경 설정   
라즈베리파이에 home assistant os 설치   
home assistant에 adds-on 목록에서  esphome 설치   
![esphome설치](https://user-images.githubusercontent.com/39102828/126729566-675e9315-13cd-449c-8670-0d4f2d220671.png)   
dhcp 설정   
![dhcp설정](https://user-images.githubusercontent.com/39102828/126729528-3c0d8bab-da50-4d4f-93e9-536fc717a2fa.png)   
포드포워딩 설정   
![포드포워딩설정](https://user-images.githubusercontent.com/39102828/126729575-08c6093f-37e9-4f8e-8c8e-7511a6cf6d87.png)   
dns 설정   
2. 리모컨 신호 해킹
IR 수신부와 아두이노를 연결하여 구성   
리모컨의 신호를 IR신호부에 쏘아 확인하여 기록   
![적외선수신구성](https://user-images.githubusercontent.com/39102828/126729591-b48c5949-94ab-431e-ae18-9313ec4040a2.jpg)   
3. 리모컨 송신 테스트   
ESP보드에 IR송신 LED를 장착해 기록한 리모컨 신호를 에어컨으로 송신해 작동하는지 테스트   
~~->현재 트랜지스터가 없어 신호가 약해 부품 배송 후 재시도 예정~~   
![적외선송신모듈제작](https://user-images.githubusercontent.com/39102828/126729614-67940957-3030-4ca2-8155-01a071bb83d6.jpg)   
4. 온습도 센서 설치
esp보드에 온습도 센서를 달고 HOMEASSISTNAT에 추가하여 현재 온습도 모니터링 가능
![온습도모니터링화면](https://user-images.githubusercontent.com/39102828/126729670-ee0da523-4683-45cf-83b1-8fd287ec9cd1.jpg)   

결과   
![홈어시스턴트pc화면](https://user-images.githubusercontent.com/39102828/126729771-75200ac7-a8fa-4bff-9659-e9ff576b99e3.png)   
![홈어시스턴트모바일화면](https://user-images.githubusercontent.com/39102828/126729789-ef66d8ba-5133-4409-bc32-d604e8568fc9.jpg)
![KakaoTalk_20210723_010514162](https://user-images.githubusercontent.com/39102828/126729881-0a9d9513-d8aa-4e82-a784-32151a3035dc.gif)
