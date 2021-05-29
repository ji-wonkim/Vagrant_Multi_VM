This project is the outcome of a school practice assignment(Cloud Computing Service Security Management). 
Use Vagrant and VirtualBox to set up multiple VMs on a private network: two Apache WebExampleBoxes with form on web pages and one MySQL DB ExampleBox that receives and stores this form data.

1. 3대의 가상머신을 기반으로 웹서비스 환경을 구축 
2. 2대의 가상머신은 웹서버를 1대의 가상 머신은 데이터베이스 서버를 갖고 있다.
3. 2대의 웹서버는 1대의 데이터베이스 서버의 데이터베이스 테이블들을 참조하여 데이터를 관리하고, 각 웹서버가 참조하는 데이터베이스 테이블은 다르다. 데이터베이스 서버의 테이블은 배포버전을 드대로 사용하되 아래와 같이 2개로 확장하여 각 웹서버가 접속할 수 있도록 한다.
  1) 웹서버 1은 response1  테이블을 참조하고 
  2) 웹서버 2은 response2  테이블을 참조하며

 각 어떤 웹서버에서 접속하느냐에 따라 수정하는 테이블이 결정된다.

 

