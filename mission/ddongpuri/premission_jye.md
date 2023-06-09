### 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)    
컨테이너 기술은 코드와 종속성을 함께 패키지화하는 응용 프로그램 계층의 추상화 기술입니다. 여러 컨테이너가 동일한 컴퓨터에서 실행되고 OS 커널을 공유할 수 있습니다.

### 도커란 무엇입니까? (100자 이내로 요약)     
도커는 컨테이너라고 하는 느슨하게 격리된 환경에서 응용 프로그램을 패키지화하고 실행할 수 있는 기능을 제공합니다. 코드를 신속하게 전송, 테스트 및 배포할 수 있습니다.

### 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?    
- Dockerfile : 사용자가 이미지를 조립(assemble)할 수 있는 텍스트 문서   
- image : 도커 컨테이너를 생성하는 방법이 기술된 읽기 전용 템플릿    
- container : 이미지의 실행가능한 인스턴스 

도커 이미지를 빌드하려면 이미지를 실행하는데 필요한 단계를 정의하기 위한 간단한 구문을 사용하여 도커 파일을 만듭니다. 도커 파일의 각 명령은 이미지에 레이어를 생성합니다. 이미지를 동적인 형태로 변경한 것이 컨테이너이고, 컨테이너의 현재 상태를 기반으로 새 이미지를 생성할 수도 있습니다. 
