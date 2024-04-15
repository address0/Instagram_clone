# 인스타그램 피드 클론코딩
### 진행 날짜: 2024.04.08 -
역할|Front End|Back End
---|---|---
팀원|주소영|허지윤
git|[address0](https://github.com/address0)|
### 실행 환경
python 3.9
### Tech
- BackEnd  
<a href="https://www.python.org/" target="_blank"><img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=FFFFFF"/></a>
<a href="https://www.djangoproject.com/" target="_blank"><img src="https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=FFFFFF"/></a>
- FrontEnd  
<a href="https://www.acmicpc.net/user/soyong32" target="_blank"><img src="https://img.shields.io/badge/Html-3366CC?style=flat&logo=htmx&logoColor=FFFFFF"/></a>
<a href="https://developer.mozilla.org/ko/docs/Web/CSS" target="_blank"><img src="https://img.shields.io/badge/CSS-7952B3?style=flat&logo=bootstrap&logoColor=FFFFFF"/></a>

## 1. 구현사항
### FE
- django가 아닌 독립적인 폴더에 프로젝트를 구성
- 프론트엔드는 vanila HTML, CSS, JS를 사용해 주세요. TailwindCSS와 같은 CSS라이브러리는 사용 가능합니다.
- 게시물 / 릴스 / 태그됨 탭 중 게시물 탭만 구현
- NavBar: 좌측, 인스타그램이 제공하는 다양한 기능을 버튼을 통해 사용할 수 있습니다.
  - NavBar를 아이콘과 함께 구현해주세요. 단 본 과제에선 홈, 프로필 페이지만 구현하기 때문에 그 외의 버튼에 대해서는 별도의 링크 연결은 하지 않으셔도 괜찮습니다.
- StoryContainer: 팔로잉 중인 인물의 스토리 존재 여부 확인
  - 기본값은 해당 인물의 스토리를 확인하지 않은 상태(테두리에 빛이 들어온 상태)
  - 해당 인물의 사진을 클릭할 경우 별도의 모달창을 표시하지 않고 해당 인물을 확인한 상태(테두리에 빛이 꺼진 상태)로 변경
- Post: 인스타그램 게시물
  - 하트 버튼을 누르면 빨간색 하트로 토글, 좋아요 개수 표시
  - 댓글 달기에서 댓글을 달 수 있으며, 게시글에 댓글이 존재한다면 최대 3개까지 표시
- Profile: 유저 디테일 페이지
  - 작성한 게시글 확인(왼쪽부터 쌓이며, 한줄에 최대 3개까지)
  - 게시물, 팔로잉, 팔로우 수 확인 가능
### BE
- FE와 합치기 전에는 간단한 Templates 내에서 DTL을 활용하여 테스트 해보세요. Postman과 같은 API 플랫폼을 이용하셔도 좋습니다.
- 요청받을 데이터는 아래와 같습니다.
  - 로그인: createsuperuser로 진행
  - 게시글 작성: 이미지(최대 1개), 내용
  - 게시글 정보: 이미지, 내용, 좋아요, 댓글...
  - 프로필: 게시글, 팔로워, 팔로잉
## 2. 사용 방법
## 3. API 명세서(BE 작성)
## 4. 페이지 소개(FE 작성)