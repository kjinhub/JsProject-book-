📚 JsProject-book
📌 프로젝트 소개

JsProject-book은 순수 JavaScript, HTML, CSS로 구현한 도서 관리 웹 애플리케이션입니다.
사용자는 책을 등록, 조회, 수정, 삭제 (CRUD) 할 수 있으며, 데이터는 로컬 배열(list) 에 저장되어 별도의 DB가 필요하지 않습니다.

이 프로젝트는 자바스크립트 기본 문법과 DOM 조작, 이벤트 처리, 배열 기반 데이터 관리 등을 학습하기 위해 제작되었습니다.

🛠 기술 스택

Frontend: HTML5, CSS3, JavaScript (ES6+)

Backend: 없음 (배열 기반 데이터 처리)

Database: 없음 (로컬 배열 사용)

Tool: VSCode, Live Server

📂 프로젝트 구조
JsProject-book
 ┣ index.html      # 메인 페이지
 ┣ style.css       # 스타일 정의
 ┣ app.js          # 핵심 로직 (CRUD 기능)
 ┗ README.md       # 프로젝트 설명 파일

✨ 주요 기능

도서 등록 (Create)

사용자가 책 제목, 저자, 출판일 등을 입력하여 배열에 저장

도서 목록 조회 (Read)

등록된 책을 테이블 또는 리스트 형태로 출력

도서 수정 (Update)

선택한 책의 정보를 수정 가능

도서 삭제 (Delete)

특정 책을 배열에서 삭제 후 화면에서도 반영

🚀 실행 방법

프로젝트를 클론하거나 다운로드합니다.

git clone https://github.com/username/JsProject-book.git


VSCode에서 열고, Live Server를 실행합니다.

브라우저에서 http://localhost:5500/index.html 접속 후 사용합니다.

📬 Postman 테스트 (예시 JSON Body)

DB를 사용하지 않지만, API 연동을 고려한다면 아래와 같은 JSON 구조를 활용할 수 있습니다.

{
  "id": 1,
  "title": "Clean Code",
  "author": "Robert C. Martin",
  "publishedDate": "2008-08-01"
}
