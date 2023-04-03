# Nginx
Nginx는 microservice를 제공하는데 적합한 웹 서버로, <br>
container로 구현되어 클라우드의 CDN (contnent delivery network) 에서 배포되어 서비스를 제공<br>
HTTP,HTTPS,SMTP,POP3,IMAP프로토콜과 로드 밸런서,HTTP캐시,웹 서버를 위한 오픈소스 Reverse Proxy서버다. <br>

# Work
apache 보다 훨씬 가벼운 웹 서버 중에 대표적으로 Nginx가 있다. <br>
간단한 html 문서를 보여주는 Nginx container를 만들어서 실행시켜 보는 과정을 볼 수 있도록 몇 장의 화면을 캡쳐하여 하나의 pdf 파일로 만들어 봅니다.

#도커 설치


#도커 오류 정리

### entjeunji@ieunjiui-MacBookAir ~ % docker -v
Docker version 20.10.23, build 7155243
entjeunji@ieunjiui-MacBookAir ~ % docker pull nginx
Using default tag: latest
Cannot connect to the Docker daemon at unix:///var/run/docker.sock. Is the docker daemon running?

function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
