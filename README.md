## ⭐ Lively
Lively는 2조의 Final Project로 진행한 작업물입니다.
2023.04.03 ~ 2023.06.09 기간동안 진행하였으며, 6명의 팀원들과 함께 하였습니다.

프로젝트 내용이 팀원들 부분 포함 전체로 올라와 있어,
프로젝트 전체 설명 및 제가 작업한 작업물 경로와 설명을 해보도록 하겠습니다.


&nbsp;

## 💡 프로젝트 소개 
저희의 지역 커뮤니티 앱 프로젝트인 Lively는 지역 사람들을 연결하고 이들이 함께 이벤트와 활동에 참여할 수 있도록 하는 플랫폼입니다.

Lively를 이용하면 사용자는 개인 간의 거래하거나 도움을 구할 수 있고, 구인·구직, 기부 등의 지역 기반의 서비스를 이용할 수 있습니다.

Lively는 위치기반 실시간 API를 제공하고 있으며, Lively의 목표는 사람들을 서로 더 가깝게 만들고 동네에서 공동체 의식을 유지하는 데 있습니다.

지역에 새로 이사한 사람이든 오래된 거주자이든 Lively는 모두에게 적합한 플랫폼입니다.


&nbsp;



## 📌 자신이 맡은 파트
저는 게시판중 친구 게시판을 맡았으며, 이러한 기능들을 구현하였습니다.
 - 게시글(피드)조회
 - 게시글검색,작성
 - 사진슬라이드
 - 지역태그
 - 피드순서정렬
 - 피드내용더보기/숨기기
 - 모집상태별리스트조회

&nbsp;

## 🛠 사용기술 및 개발환경
- STS :  3
- Apache Tomcat 9.0
- Mybatis
- maven
- Java : 11
- Spring framework : 5.3.22
- Oracle : 11g
- jQuery
- Visual Studio Code : 1.78
- HTML5
- CSS
- javascript


&nbsp;

## 🔗 나의 작업 파일 경로
**spring**

- controller : https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/java/com/lively/friend/controller/FriendController.java
- dao : https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/java/com/lively/friend/dao/FriendDao.java
- service : https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/java/com/lively/friend/service/FriendService.java
- mapper(mybatis) : https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/resources/mybatis/mapper/friend-mapper.xml

**jsp**

- 피드목록 : https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/WEB-INF/views/board/friend/friend-list.jsp



&nbsp;

## 📸 완성된 화면
<details>
  <summary>친구게시판 피드목록</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/FriendList.PNG" />
  </div>
</details>
<details>
  <summary>친구게시판 이미지슬라이드</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/edit3.PNG" />
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/imgslide2.PNG" />
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/imgslide3.PNG" />
  </div>
</details>
<details>
  <summary>피드 검색기능</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/FriendSearch.PNG" />
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/FriendSearch2.PNG" />
  </div>
</details>
<details>
  <summary>피드 수정</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/edit3.PNG" />
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/edit1.PNG" />
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/edit2.PNG" />
  </div>
</details>
<details>
  <summary>피드 모집마감</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/END.PNG" />
  </div>
</details>
<details>
  <summary>피드 모집 중만 보기</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/ING1.PNG" />
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/ING2.PNG" />
  </div>
</details>
<details>
  <summary>피드 내용 더보기(more)</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/more1.PNG" />
    <image src="https://github.com/taewoon123/FinalProject/blob/main/FinalProjectLIVELY/src/main/webapp/resources/img/more2.PNG" />
  </div>
</details>


