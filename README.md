# :deciduous_tree: 산넘고 산넘어

<pre>
  4일동안 진행된 미니 프로젝트로 전국의 산을 소개합니다.
  등산을 사랑하는 사람들이 등산 후기와 산의 정보를 공유할 수 있는 사이트 입니다. 
</pre>

## Stack

### Frontend

-   HTML
-   CSS (Bulma)
-   JavaScript

### Backend

-   Flask, MongoDB Atlas

## Product

[유튜브](https://youtu.be/ScFCljhbfw0)

# 역할

## Member

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/shippig"
        ><img
          src="https://avatars.githubusercontent.com/u/42665042?v=4"
          width="100px;"
          alt=""
        /><br /><sub><b>인상운</b></sub></a
      ><br />
    </td>
    <td align="center">
      <a href="https://github.com/coldrain-f"
        ><img
          src="https://avatars.githubusercontent.com/u/81298415?v=4"
          width="100px;"
          alt=""
        /><br /><sub><b>황윤정</b></sub></a
      ><br />
    </td>
    <td align="center">
      <a href="https://github.com/beomjin96"
        ><img
          src="https://avatars.githubusercontent.com/u/102977561?v=4"
          width="100px;"
          alt=""
        /><br /><sub><b>김범진</b></sub></a
      ><br />
    </td>
    <td align="center">
      <a href="https://github.com/gureumwoon"
        ><img
          src="https://avatars.githubusercontent.com/u/83581867?v=4"
          width="100px;"
          alt=""
        /><br /><sub><b>김채운</b></sub></a><br />
    </td>
  </tr>
</table>

## Page UI 및 기능 구현

| 이름       | pages                                                                            |
| ---------- | -------------------------------------------------------------------------------- |
| **인상운** | 로그인                             |
| **김채운** | 회원가입                           |
| **김범진** | 로그아웃, 메인페이지, 상세보기,     |
| **황윤정** | 게시물 업로드, 게시물 수정, 게시물 삭제|

# 상세 기능

<h2>로그인 (인상운)</h2>

<table>
  <tr align="center">
    <td align="center">
        <img
          src="https://user-images.githubusercontent.com/83581867/168465262-52de9e0f-f098-4cd9-963d-1034288d61f3.gif"
          width="400px;"
          alt=""
        /><br/><sub><b>로그인 성공</b></sub><br />
    </td>
     <td align="center">
        <img
          src="https://user-images.githubusercontent.com/83581867/168465320-abd0d4bd-ed51-4916-bfa9-b377c7f3ae84.gif"
          width="400px;"
          alt=""
        /><br /><sub><b>로그인 실패</b></sub><br />
    </td>
  </tr>
</table>


- '로그인' 버튼을 클릭하면 이메일 주소와 비밀번호에 대한 유효성 검사를 진행하고, 이메일 주소와 비밀번호가 일치하지 않으면 알림창으로
  '이메일과 비밀번호가 일치하지 않습니다.' 라는 경고문구가 나타납니다.
  
<h2>회원가입 (김채운)</h2>

<table>
  <tr align="center">
    <td align="center">
        <img
          src="https://user-images.githubusercontent.com/83581867/168467154-056f4a99-0b16-4dc5-9724-9547886b7d30.gif"
          width="400px;"
          alt=""
        /><br/><sub><b>중복검사</b></sub><br />
    </td>
     <td align="center">
        <img
          src="https://user-images.githubusercontent.com/83581867/168467189-e9e96fdc-2772-4f69-87ca-1b50c3d4189a.gif"
          width="400px;"
          alt=""
        /><br /><sub><b>유효성검</b></sub><br />
    </td>
  </tr>
</table>

- 회원가입 할 이메일과 비밀번호는 중복검사 버튼을 통해서 사용이 가능한지 불가한지 검사 해줍니다.
- 회원가입 버튼을 클릭하면 이메일과 닉네임 형식이 올바른지, 비밀번호와 비밀번호 확인란에 입력한 게 일치하는지, 닉네임 형식이 올바른지 전체적인 유효성 검사를 해주고, 빈칸이거나 이메일(@), 비밀번번호(영문과 숫자 필수 포함, 특수문자(!@#$%^&*)사용가능 8-20자)이 유효하지 않거나, 닉네임(2-10자의 영문과 숫자와 일부 특수문자(._-)만 입력 가능합니다.) 등의 형식이 맞지 않으면 입력창 밑에 경고문이 뜹니다.
- 중복확인을 하지 않고 회원가입 버튼을 누르면 중복검사를 하라는 경고 창이 뜹니다.
  
<h2>게시물 업로드 (황윤정)</h2>
<h2>게시물 수정 (황윤정)</h2>
<h2>게시물 삭제 (황윤정)</h2>
<h2>메입페이지 & 상세보기 (김범진)</h2>
<h2>로그아웃 (김범진)</h2>
