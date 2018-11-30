# My Music Blog

## Overview
<ul>
<li>Service : 남자 가수와 노래들 추천 및 소통(댓글)</li>
<li>Skill : Apache, MySQL, PHP, HTML, CSS</li>
<li>Term : 2016. 05 ~ 2016. 06</li>
<li>Role : Frontend, Backend</li>
</ul>

## Architecture
![image](https://user-images.githubusercontent.com/21019088/49278340-d12f3000-f4c7-11e8-9c5b-50d3e330f46f.png)

## Feature
<ol>
<li>Main, Login, Signup, Bulletin Board Page 제작 </li>
<li>사용자 인증 처리</li>
<li>Cookie를 사용한 자동 로그인</li>
<li>Review 기능 구현</li>
<li>Comment 기능 구현</li>
</ol>

## Individual Pages Introduction
### MainPage
블로그를 소개하는 글과 함께 오른쪽 위에 welcome, login, signup, bulletin board 그리고 소개 글 옆에 추천 가수리스트 및 노래리스트를 보기 위해 선택할 수 있도록 하는 전체 노래 UI로 구성하였습니다. (모든 page에는 songs라는 블로그 네임을 클릭하면 main 화면으로 돌아갈 수 있도록 구성하였습니다.)
![image](https://user-images.githubusercontent.com/21019088/49278554-882bab80-f4c8-11e8-9291-3a864caf8441.png)
![image](https://user-images.githubusercontent.com/21019088/49278563-8bbf3280-f4c8-11e8-96d3-5febd6817627.png)
![image](https://user-images.githubusercontent.com/21019088/49278590-9974b800-f4c8-11e8-9c45-5e9f0847ecff.png)

### SingerPage
가수의 이름과 이미지를 화면 위에 보이게 하고 클릭 시 그 가수의 대표곡과 특색들이 적힌 공간으로 넘어가도록 하며 옆에는 회원에 한하여 의사소통을 위한 게시물을 달고 댓글을 쓸 수 있도록 UI를 구성하였습니다.
![image](https://user-images.githubusercontent.com/21019088/49278619-a98c9780-f4c8-11e8-88eb-b7b42cf3bcfd.png)
![image](https://user-images.githubusercontent.com/21019088/49278628-b01b0f00-f4c8-11e8-8b71-037e9325c3a6.png)

### SongPage
전체 추천리스트를 한 눈에 볼 수 있도록 하며 옆의 화면에는 회원에 한하여 사용자 간의 의사소통 위한 댓글 UI를 구성하였습니다.
![image](https://user-images.githubusercontent.com/21019088/49278673-d04ace00-f4c8-11e8-945b-e7435b3e2278.png)

### SingerSelectPage
가수들을 한 화면에 볼 수 있으며 선택 시 해당 가수의 화면으로 넘어가 관련된 여러 가지 정보들을 볼 수 있으며 게시물과 댓글을 통하여 의사소통을 할 수 있습니다.
![image](https://user-images.githubusercontent.com/21019088/49278720-f6706e00-f4c8-11e8-9554-23a2e049afd5.png)

### SignupPage
E-mail, Password, Image를 넣을 수 있도록 UI를 구성하였으며 입력을 다 끝내면 Signup버튼을 누르면 RDS를 검색해 정보가 중복된 것이 없는지 체크 후 없다면 RDS에 회원 정보를 저장합니다.
![image](https://user-images.githubusercontent.com/21019088/49278879-5b2bc880-f4c9-11e8-96f4-03f5d343b91f.png)

### LoginPage
E-mail과 Password를 입력 할 수 있도록 하였으며 모두 입력 후 Signin 버튼을 누르면 확인 후 성공 시 로그인이 될 수 있도록 UI를 구성하였습니다.
![image](https://user-images.githubusercontent.com/21019088/49278942-87474980-f4c9-11e8-8730-f77650ff063c.png)

### Review register form
사용자의 글을 등록하기 위해 제목 메모 이미지를 등록 시킬 수 있도록 하였습니다.
![image](https://user-images.githubusercontent.com/21019088/49278994-a80f9f00-f4c9-11e8-87fd-79fcb0b90265.png)
![image](https://user-images.githubusercontent.com/21019088/49279002-aba32600-f4c9-11e8-8e90-17b406084d38.png)

### Comment register and Edit form
개개인의 사용자가 댓글을 등록 및 삭제 할 수 있도록 하였습니다. 
![image](https://user-images.githubusercontent.com/21019088/49279311-7fd47000-f4ca-11e8-8936-6bfc9516e8e2.png)
![image](https://user-images.githubusercontent.com/21019088/49279321-86fb7e00-f4ca-11e8-9f6a-ee7c1e218d36.png)

