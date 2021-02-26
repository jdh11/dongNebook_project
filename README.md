# dongNebook_project

   <br>
    <ul>
  <li>프로젝트 소개</li>
  <li>DB 설계</li>
  <li>주요 기능 소개</li>
</ul>

<hr><br>
<div class="con-1">
<h2>프로젝트 소개</h2>
<img src="https://user-images.githubusercontent.com/74252292/109281489-b642f600-785f-11eb-86b2-f5d217a72cd1.png", width="700">
<h3>전체 기능</h3>

<h4>1. 사용자</h4>
<img class="con-1-1" src="https://user-images.githubusercontent.com/74252292/109281915-3bc6a600-7860-11eb-89ac-bdc7a2b92411.png", width="700">
<br>
<img class="con-1-1" src="https://user-images.githubusercontent.com/74252292/109282199-8f38f400-7860-11eb-952c-b588eea30640.png", width="700">
<br>
<h4>2. 관리자</h4>
<img class="con-1-1" src="https://user-images.githubusercontent.com/74252292/109282476-e939b980-7860-11eb-9ffe-efecff8626f2.png", width="700">
<br>
</div>
<hr><br>
<h2>DB 설계</h2>
<img class="con-1-1" src="https://user-images.githubusercontent.com/74252292/109282703-3ae24400-7861-11eb-8d88-06ce1303dce4.png", width="700">
<br><hr><br>
<h2>주요 기능 소개</h2>
<h3>○ 북마크</h3>
<h4>북마크한 책이 없을 때</h4>
<img class="con-1-2" src="https://user-images.githubusercontent.com/74252292/109284017-c0b2bf00-7862-11eb-8b2a-082478157455.png", width="800">
<br>
<h4> 북마크한 책이 있을 때</h4>
<img class="con-1-2" src="https://user-images.githubusercontent.com/74252292/109284260-01aad380-7863-11eb-8ea7-ee41cc93f0a8.png", width="800">
<h4> 대여하기를 눌렀을 때</h4>
<div>＊ Ajax를 이용하여 현재 대여한 책의 수를 조회하고 대여한 권수에 따라 대여 가능한 횟수를 제한하였습니다.
</div>
<div>
&nbsp 1. 대여한 책이 없을 경우 -> 3권 대여 가능
</div>
<div>
&nbsp 2. 2권 대여한 경우 -> 1권 대여 가능
</div>
<div>
&nbsp 3. 1권 대여한 경우 -> 2권 대여 가능
</div>
<br>
<img class="con-1-2" src="https://user-images.githubusercontent.com/74252292/109284872-b218d780-7863-11eb-9dc5-c309737d49c5.png", width="800">
<br><br><hr><br>
<h3>○ 도서 신청 관리</h3>

<div>＊
메뉴에 따라 전체 보기, 신청한 책, 승인된 책, 반려된 책이 보여 집니다.
</div>
<h4>전체 보기</h4>
<img class="con-1-2" src="https://user-images.githubusercontent.com/74252292/109285532-8c400280-7864-11eb-9886-f67468ed8a95.png", width="800">
<h4>신청한 책</h4>
<img class="con-1-2" src="https://user-images.githubusercontent.com/74252292/109286098-2f911780-7865-11eb-9694-6a60d4e84e79.png", width="800">
<h4>승인된 책</h4>
<img class="con-1-2" src="https://user-images.githubusercontent.com/74252292/109286113-33249e80-7865-11eb-80d2-2cdcd46c2b2d.png", width="800">
<h4>반려된 책</h4>
<img class="con-1-2" src="https://user-images.githubusercontent.com/74252292/109286128-361f8f00-7865-11eb-8a12-0bec31f5db52.png", width="800">

<h4>승인 버튼을 눌렀을 때</h4>
<div>＊ 모달을 이용하여 한번 더 확인합니다.
</div>
<br>
<img class="con-1-2" src="https://user-images.githubusercontent.com/74252292/109286428-90205480-7865-11eb-9cc3-fdb9ff1f2a74.png", width="800">
<h4>반려 버튼을 눌렀을 때</h4>
<img class="con-1-2" src="https://user-images.githubusercontent.com/74252292/109286459-9c0c1680-7865-11eb-995c-c487bca74e4a.png", width="800">
<h4>승인/반려 되었을 때 사용자에게 알려줍니다.</h4>
<div>＊ 사용자가 로그인 후 메인 화면에서 승인/반려된 책을 알 수 있습니다.</div>
<br>
<img class="con-1-2" src="https://user-images.githubusercontent.com/74252292/109286673-e8575680-7865-11eb-9ced-45de53b927ae.png", width="800">
<br><br><hr><br>
<h3>○ 대출 순위</h3>
<img class="con-1-2" src="https://user-images.githubusercontent.com/74252292/109286948-471cd000-7866-11eb-93a7-4472b5595822.png", width="800">
<br><hr><br>
