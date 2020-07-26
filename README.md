<h1>androidstudio_project_1 mypetmily</h1>
</br>
<p></p>

## 1. 서비스 소개 
<p>마이펫밀리는 애견호텔 안심 예약서비스로 견주들이 애견호텔에 안심하고 강아지를 맡길 수 있게 하는 서비스입니다. 기존의 커뮤니티 위주 또는 야놀자, 여기어때의 애견 버전 애견 호텔 서비스와는 다르게 
이 서비스는 모니터링, 체크리스트, 리뷰의 세분화를 담은 서비스입니다.</p>
</br>

## 2. server
node.js
</br>
</br>

## 3. Database
MySQL
</br>
</br>

## 4. 디자인 패턴
MVVM

## 5. project androidstudio 작업 내용 세분화

* ### navigation 활용
   Login, Register, MyPage 등의 큰 부분만 Activitiy -> 나머지 세부사항은 모두 하단의 fragment로 제작
<p></p>
       ex)
<img width="752" alt="img" src="https://user-images.githubusercontent.com/68799146/88473305-2ea6a900-cf57-11ea-9de4-73f6610a3cdb.png">

* ### ViewModel & LiveData 이용
   ui별로 ViewModel을 생성하여 안드로이드 수명 주기를 고려하여 제작
   
* ### roomdatabase이용
   roomdatabase를 (Entitiy, Dao, Database...) 활용하여 테이블을 생성하고 호텔과 유저의 정보를 처리

* ### RecyclerView를 이용한 호텔리스트 생성
   adapter에 ViewHolder를 넣고, 클릭하면 호텔 상세페이지로 넘어갈 수 있게 함.

* ### Internet연결
   REST는 Retorfit 클리이언트 라이브러리를 사용
   Gson을 이용해 Object를 JSON형식으로 파싱
   
## 6. 실행했을 때의 화면
   리사이클러뷰를 이용한 호텔 리스트
   </br>
   </br>
   <img width="381" alt="스크린샷 2020-07-24 오후 3 32 30" src="https://user-images.githubusercontent.com/68799146/88476096-93bac880-cf70-11ea-9410-ea68be19418d.png">
   
   호텔 상세 페이지
   </br>
   </br>
   <img width="379" alt="스크린샷 2020-07-24 오후 3 36 26" src="https://user-images.githubusercontent.com/68799146/88476104-9b7a6d00-cf70-11ea-97ce-b84d845b81db.png">
   
   강아지 등록화면
   </br>
   </br>
   <img width="384" alt="스크린샷 2020-07-24 오후 3 34 49" src="https://user-images.githubusercontent.com/68799146/88476293-31fb5e00-cf72-11ea-8003-e552bb285218.png">

   
   

