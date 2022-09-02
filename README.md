# Teamproject
국비학원 팀프로젝트
‘지인 맛집 공유 웹사이트’ 팀 프로젝트

목적 : 신빙성 있는 리뷰와 지인들의 취향을 서로 공유할 수 있는 맛집 커뮤니티 개발<br />

진행기간 : <br />
(1) 기본설계<br />
주제선정(7.18) /<br />
기능회의(7.18-7.20) / <br />
디자인 컨셉 회의(7.19-7.22)<br />

(2) 상세 설계<br />
Warframe(7.20-7.27) /<br />
DFD(7.21-7.25) /<br />
ERD(7.21-7.25) /<br />
UML(7.21-7.25)<br />

(3) 구현<br />
코딩(7.26-8.19) /<br /> 
수정&보완(8.16-8.24) / <br />
운영환경구축(8.16-8.26) / <br />
시스템 검수(8.27-8.29)<br />

진행인원 수 : 5명<br />
-------------------------------------------------------------------------------------------<br />
운영 체제 : Windows 10 <br />
WAS : Apache-Tomcat 9.0.6 <br />
Framework : Spring Boot (2.7.2) <br />
데이터베이스 : MariaDB 10.6 <br />
개발 도구 : Eclipse(2022-03), Visual Studio Code <br />
개발 언어 : Java(11), JSP, Javascript, Css, Html5, Bootstrap <br />
필요 기술 : Jsoup, JQuery, Open API(네이버 지도) <br />
협업 툴 : Github, Discord, Google Docs <br />

구현 정도 : 로그인/회원가입, 마이페이지, 소모임&관리자, 즐겨찾기, 식당검색, 서버배포(AWS) 등등<br />

-------------------------------------------------------------------------------------------<br />
Role : 프론트엔드 디자인 총괄 및 백엔드 보조 <br />
구현한 주요 화면<br />
1) 로그인/회원가입 <br />
2) 메인 <br />
3) 알림창  <br />
4) 관리자 페이지 <br />
5) 마이페이지<br />
6) 즐겨찾기 <br />
7) 에러페이지(타임리프로 시도중..)<br />

-------------------------------------------------------------------------------------------<br />
* 기획과 달라진 점 : <br />
1) 쪽지 & 공유 미구현 <br />
2) 웹 서버 DB가 아닌 Localhost:3306으로 실행 시 upload Path 문제로 인해 사진이 안보임<br /><br />
* 기획과 달리진 이유 : 기획 초반에 너무 많은 기능을 포함시키려고 했기 때문에 시간이 부족했음 <br />
* 문제해결을 위한 노력 : <br />
1) upload Path 경로를 다시 지정하여 실행-> 본인 upload만 보이고 타인에겐 안보여짐 + 타인 upload한 것이 안보이는 문제 발생(미해결) <br />
2) 로그인 페이지에서 이미지 크기가 조정이 제대로 안됨 -> img-responsive, img-fluid로 이미지 설정 but 미해결 -> @media min-width, max-width 재설정 but 미해결<br />
