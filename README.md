# Nodejs + Jade + PassportJs + Mysql Authentificate Template

## 설치 방법 (Express)
  1. 설치 폴더에서 npm install express
  2. npm install -g express-generator : 뼈대를 만든다. -g : 전역 모듈을 의미
  3. express --ejs : ejs(Embedded javascript) 옵션으로 기본 뼈대를 생성
     express 만 타이핑 할 경우 jade 로 어플리케이션을 생성. 이 때 jade 파일 생성
  4. npm install


## 생성되는 폴더 및 파일
```
  app.js
  package.json
  bin - www
  public - images, javascripts, stylesheets
  routes - index.js, users.js
  views - error.ejs, index,ejs, error.jade, index,jade, layout.jade
  node_modules - body-parser, cookie-parser, debug, ejs, express, morgan, serve-favicon
  -------------------------------------------------------------------------------------
  app.js : 웹프로젝트의 메인코드
  package.json : 모듈의 의존성 및 npm script 명령어를 정의
  /public : 정적파일(html, images, javascript, css) 들을 저장
  /routes : URL 별로 수행되는 로직을 저장
  /views : HTML view 템플릿을 저장(ejs파일, jade파일)
  /node_modules : express 앱에 필요한 모듈
```
