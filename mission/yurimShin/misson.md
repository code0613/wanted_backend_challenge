1. 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)
<br>
> 운영체제에서 실행되는 프로세스를 격리(Isolation)하여 별도의 실행 환경을 제공해주며, 해당 프로세스는 운영체제 상에서 실행되는 유일한 프로세스인 것처럼 작동하는 기술

2. 도커란 무엇입니까? (100자 이내로 요약)
<br>
> 독립된 환경을 만들어서 하드웨어를 효율적으로 활용하는 기술

3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?
<br>
> 도커 파일 : 컨테이너를 생성하는 데 사용되는 스크립트 파일
<br>
> 도커 이미지 : 도커에서 서비스 운영에 필요한 서버 프로그램, 소스코드 및 라이브러리, 컴파일 된 실행 파일을 묶는 형태
<br>
> 도커 컨테이너 : 도커 이미지를 기반으로 생성된 실행 환경
<br>
> 관계 : 도커 파일은 도커 이미지를 만들기 위해 사용되며, 도커 컨테이너는 도커 이미지를 실행하는 인스턴스