# Repo 개요

- docker 환경 WEB-WAS 애플리케이션 연동 연습용 repo
- docker-compose 활용
- jpetstore 샘플 애플리케이션 사용
  - https://github.com/mybatis/jpetstore-6
- nginx-tomcat docker-compose 연동 블로그 글을 참고함
  - https://jistol.github.io/docker/2017/09/19/docker-compose-tomcat-clustering/



# 현재까지 한 것

- Nginx 1대와 Tomcat 2대를 reverse proxy 방식으로 연동
- Tomcat에 jpetstore를 war 형태로 배포
- docker0와 NIC 간 mtu 달라서 통신 안되는 문제 해결
- docker에 내장 DNS 서버가 있어서 container 이름으로 통신 가능함



# 시도해볼 것

- Tomcat 클러스터링
- 로드 밸런싱이 실제로 잘 되는지 확인
- 