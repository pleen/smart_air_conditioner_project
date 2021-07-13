# smart_air_conditioner_project

구형 에어컨을 홈어시스턴트를 이용해 컨트롤하는 프로젝트

주요 재료   
esp 보드   
IR 수신부   
IR 발광부   
라즈베리파이   

제작 현황   
1. 환경 설정   
라즈베리파이에 home assistant os 설치   
home assistant에 adds-on 목록에서  esphome 설치   
dhcp 설정   
포드포워딩 설정   
dns 설정   
2. 리모컨 신호 해킹(https://dokkodai.tistory.com/185)   
IR 수신부와 아두이노를 연결하여 구성   
리모컨의 신호를 확인하여 기록   
3. 리모컨 송신 테스트   
기록한 리모컨 신호를 에어컨으로 송신해 작동하는지 테스트   
