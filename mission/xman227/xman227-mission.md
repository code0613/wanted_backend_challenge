## 사전 미션
1. 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)
```text
기존의 가상머신은 하나의 운영체제 위에 또 다른 운영체제를 설치할 수 있는 가상의 컴퓨터를 가동하는 것이다.
때문에 컴퓨터를 구동시키기 위한 모든 것이 준비되어 있어야 하므로 비용이 크다.
하지만 컨테이너 기술을 사용하면 하나의 호스트 운영체제 위에 다양한 운영체제 및 프로그램을 논리적으로 구분할 수 있고,  
운영 체제 환경에 상관없이 각자 독립적으로 일관된 결과를 보장할 수 있다.

```

2. 도커란 무엇입니까? (100자 이내로 요약)
```text
컨테이너 환경에서 독립적으로 애플리케이션을 실행할 수 있도록  
컨테이너를 만들고 관리할 수 있는 오픈소스 플랫폼이다.
```

3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계일까?  

**도커파일**
```text
도커파일은 도커 이미지를 어디서나 동일하게 빌드하기 위한 설명서이다.
도커파일 안에는 컨테이너의 운영체제 및 각 라이브러리 명세서가 기록되어 있으며,  
도커파일 만으로 이미지의 기능과 버전을 쉽게 파악할 수 있다.
```

**도커 이미지**
```text
도커 이미지는 도커 파일로 의해 만들어지는 컨테이너 내부에 담길 프로그램의 집합이다.  
```

**도커 컨테이너**
```text
이미지를 실행하기 위한 그릇이다.
이미지를 논리적 구분 공간에 설치하여 프로세스의 전체적인 동작을 관리해준다.
```


4. [실전 미션] 도커 설치하기 (참조: [도커 공식 설치 페이지](https://docs.docker.com/engine/install/))
- 아래 `도커 설치부터 실행 튜토리얼`을 참조하여 도커를 설치하고, 도커 컨테이너를 실행한 화면을 캡쳐해서 Pull Request에 올리세요.
