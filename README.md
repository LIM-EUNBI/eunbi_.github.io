#### 이번주 작업예정
- 태블릿 메인 CSS 스타일 , PC용 메인 CSS 스타일 
- 모바일 서브페이지 CSS
- 태블릿 + PC용 CSS  
- 모바일 게시판 페이지(CRUD) CSS
- 태블릿 + PC용 CSS
- 모바일 + 태블릿 + PC 댓글 (CSS + 제이쿼리 + 부트스트랩)
- AdminLTE(부트스트랩 기반 템플릿 - 반응형)를 이용해서 관리자단 디자인 만들기
- UI디자인 끝
- UI구현 시작 -> 스프링 프로젝트 시작 (이클립스, 자바 + 오라클 + 스프링)
- UI구현 -> 위에서 제작한 UI디자인 이용해서 프로그램을 입힌다.

#### 20210517(월) 작업
- jQuery JSON 데이터 파싱 (o)
- 외부 data.js파일에서 json데이터를 저장한 후 html에서 불러와서 파싱 (o)
- 외부 사이트에서 제공하는(RestAPI서버) json데이터를 html에서 불러와서 파싱 (o)
- RestAPI서버 중 코로나19 확진자 데이터를 받아서 html에서 파싱
- 파싱 : 데이터를 분해해서 화면에 뿌려주는 작업
- RestAPI서버 주소(빅데이터) : https://coroname.me/getdata

- 메인페이지에 자바스크립트(jQuery) 적용. (o)
- 메뉴, 슬라이드 이미지 3개 처리 (o)
- 보통 이미지 슬라이드 처리는 외부 라이브러리 사용(니보 슬라이드, 캐로셀 슬라이드)
- 외부 라이브러리 사용 안하고 우리가 만들기 (o)

#### 20210514(금) 작업
- 사용자단 모바일 메인페이지 footer영역 CSS 입히기 (o)
- top 상단으로 이동처리 (o)
- 과제물 제출 (o)
- 메인페이지에서 자바스크립트(jQuery)적용 - 메뉴, 슬라이드 이미지 처리, top 상단 이동

#### 20210513(목) 작업내역
- 원격지원으로 팀뷰어에서 애니데스크로 바꿈
- 오늘부터는 모바일 메인 페이지 1개 만들어서 과제물로 제출
- -> 추후에 스프링에서 프로그램 입히는 소스로 사용하게 될 예정
- jQuery 코어 다운받기 : min버전(압축-속도빠름), 일반버전(개발)
- 작업폴더를 나누는 이유 : 시청, 관공서, 대학, 기업의 웹프로그램(사이트)를 제작할 때,
- 보통 1년간 무상 유지보수가 된다.
- 그 이후 유지보수 비용 보통 2천, 리뉴얼 4천만원의 비용이 책정된다.
- 리뉴얼할 때 덮어씌우는 방식이 아니라 home2022 즉, 새로운 폴더에 작업을 하게된다.

- 픽사베이에서 받은 이미지 3개 : 로고, 슬라이드 이미지, 이미지없음 이미지 총 3개
- 로고 : https://pixabay.com/ko/illustrations/%EB%A7%A4%EB%8B%AC%EB%A0%A4%EB%8A%94-%EA%B3%A0%EC%96%91%EC%9D%B4-%EB%82%99%EC%96%91-%EA%B3%A0%EC%96%91%EC%9D%B4-4794472/

- 슬라이드 커피 : https://pixabay.com/ko/photos/%EC%BB%A4%ED%94%BC-%EC%88%98%EC%B2%A9-%EB%82%98%EB%AC%B4-%EC%98%A4%EB%A0%8C%EC%A7%80-%EC%9D%BC-1276784/

- 슬라이드 3
- https://pixabay.com/ko/illustrations/%EC%BB%A4%ED%94%BC-%EC%BB%A4%ED%94%BC-%EC%BD%A9-%EC%BD%A9-%EC%BB%A4%ED%94%BC%EC%9E%94-1390800/

- 이미지없음 : 
https://pixabay.com/ko/vectors/%EC%B9%B4%EB%A9%94%EB%9D%BC-%EC%82%AC%EC%A7%84-%EC%9D%B4%EB%AF%B8%EC%A7%80-1085705/

- 슬라이드 여분
https://www.freepik.com/free-vector/watercolour-brushstrokes-background_13067993.htm#page=8&query=cute&position=21#position=21&page=8&query=cute

- 슬라이드 1 
https://www.freepik.com/free-photo/front-view-funny-cute-dog-concept_11524378.htm#page=11&query=cute&position=17#position=17&page=11&query=cute

- 슬라이드 4
https://www.freepik.com/free-vector/cartoon-hello-summer-illustration_13722519.htm#page=1&query=summer&position=15#position=15&page=1&query=summer

#### 20210512(수) 작업내역
- git clone으로 프로젝트를 가져온 경우 아래 내용을 추가해 줘야된다.
- git config --list 확인에서 user.name, user.email 없으면 추가해야된다.
- git config --local user.name
- git config --local user.email
- 프로젝트를 1명이 제작하는 경우가 없기 때문에, 2명이상 일때 소스 수정한 사람 확인용 정보

- html5.html, css.html, js.html (jQuery 기본구조만)까지 실습.
- jQuery 마무리 작업은 다음주에 실습할 예정

#### 20210511(화) 작업내역
- 서버(응답하는 프로그램 = response) = 아파치, 톰캣 서버
- 클라이언트(요청하는 프로그램 = request) = 웹 브라우저
- HTML은 마크업이 태그로 구성되어있다. <의미있는 태그>.. 등

- http://127.0.0.1:5500(포트8080|5050|6000)등...
- URL 경로(path) : /루트, /test/html5.html

- pc의 네트워크 내부주소(공통) : 127.0.0.1 == localhost
- 고유주소 : yahoo.com(도메인) == 74.6.143.25
- IP주소 버전 : IPv4, IPv6 

- HTML도 버전이 있다. : HTML5, HTML4.01(이전)

- lorem ipsum 영어 URL 주소 : https://loremipsum.io/
- lorem ipsum 한글 URL 주소 : http://guny.kr/stuff/klorem/#/table-html


#### 20210510(월) 작업내역
- 개발PC(html) 와 깃 저장소와 연결시킵니다. 초기에 연결시 아래와 같은 
  문제점이 나올 수 있습니다.

- 레포지토리(저장소) 초기화: git init 또는 VS code에서 레포지토리초기화 버튼 이후
- Git에서 'user.name' 및 'user.email'을 구성하라고 떠요!(해결책)
- git config --local user.name 이름
- git config --local user.email 이메일
- git git remote add origin https://github.com/사용자저장소/사용자저장소.git
- 작업결과는 .git 폴더안의 config 파일에 저장됩니다.

- 이후 VS code 프로그램에서 아래 처럼 작업 하시면 됩니다.

- 업로드절차: 1. 커밋(commit) 2. 푸시(push)
- 다운로드절차: 1. 풀(pull) : 교실에서 작업한 결과를 집에서 이어서 작업할 상황
- 주의) 다른 신규 PC에서 작업시 아래 명령어로 깃내용을 새로 가져옵니다.(아래)
- git clone https://github.com/학생저장소/학생저장소.github.io.git

- 안정된 이후 기존 사용자 폴더에서는 작업 시작전에
- git pull 로 어제 작업한 내용을 최신버전으로 업데이트 합니다.

- 포트의 역할이 트렌드로 많이 사용됩니다.
- 포트(port): 포트번호로 서비스를 만드는것이 트렌드
- 이전에는 80포트에 모든 서비스 묶어놓았습니다.
- 모든서비스를 개별로 분리하는 트렌드가 있습니다.: 마이크로서비스라고 합니다. == RestAPI로 구현이 됩니다.
- 도메인(예, https://naver.com:1451241/네이버 인증서비스 개발)
- 외부 인원(네이버직원아닌) 위 포트기준으로 제작한 서비스를 갖다가 사용

- html : Hyter Text MarkUp Language 태그를 사용하는 언어
- md : MarkDown Language 태그를 사용하지 않는 언어

