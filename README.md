# smart_air_conditioner_project

구형 에어컨을 홈어시스턴트를 이용해 컨트롤하는 프로젝트

주요 기능   
1. 리모컨 대신 휴대폰만으로 에어컨 조절 가능
2. 집에 가까이 오면 자동으로 에어컨 켜기
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
dhcp 설정   
포드포워딩 설정   
dns 설정   
2. 리모컨 신호 해킹(https://dokkodai.tistory.com/185)   
IR 수신부와 아두이노를 연결하여 구성   
리모컨의 신호를 IR신호부에 쏘아 확인하여 기록   
3. 리모컨 송신 테스트   
ESP보드에 IR송신 LED를 장착해 기록한 리모컨 신호를 에어컨으로 송신해 작동하는지 테스트   
->현재 트랜지스터가 없어 신호가 약해 부품 배송 후 재시도 예정
4. 온습도 센서 설치
esp보드에 온습도 센서를 달고 HOMEASSISTNAT에 추가하여 현재 온습도 모니터링 가능
