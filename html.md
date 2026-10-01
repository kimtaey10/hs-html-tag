아래 내용을 **그대로 복사해서 `.md` 파일**에 붙여넣으면 돼.

# HTML 태그 정리

## 📌 HTML 기본 태그

| 태그         | 용도          | 예시                      |
| ---------- | ----------- | ----------------------- |
| `<html>`   | HTML 문서 전체  | `<html> ... </html>`    |
| `<head>`   | 문서의 정보 설정   | `<head> ... </head>`    |
| `<title>`  | 웹페이지 제목     | `<title>내 홈페이지</title>` |
| `<body>`   | 화면에 표시되는 내용 | `<body> ... </body>`    |
| `<!-- -->` | 주석          | `<!-- 설명 -->`           |

---

## 📝 글자/텍스트 관련 태그

| 태그              | 용도         | 예시                     |
| --------------- | ---------- | ---------------------- |
| `<h1>` ~ `<h6>` | 제목         | `<h1>큰 제목</h1>`        |
| `<p>`           | 문단         | `<p>안녕하세요.</p>`        |
| `<br>`          | 줄바꿈        | `안녕<br>하세요`            |
| `<hr>`          | 가로선        | `<hr>`                 |
| `<strong>`      | 중요한 내용, 굵게 | `<strong>중요</strong>`  |
| `<b>`           | 굵게         | `<b>굵은 글씨</b>`         |
| `<em>`          | 강조, 기울임    | `<em>강조</em>`          |
| `<i>`           | 기울임        | `<i>기울임</i>`           |
| `<u>`           | 밑줄         | `<u>밑줄</u>`            |
| `<small>`       | 작은 글씨      | `<small>작은 글씨</small>` |
| `<mark>`        | 형광펜 효과     | `<mark>강조</mark>`      |

---

## 🔗 링크/이미지 태그

| 태그             | 용도              | 예시                                    |
| -------------- | --------------- | ------------------------------------- |
| `<a>`          | 하이퍼링크           | `<a href="https://google.com">구글</a>` |
| `<img>`        | 이미지 삽입          | `<img src="image.jpg">`               |
| `<figure>`     | 이미지 등의 독립적인 콘텐츠 | `<figure>...</figure>`                |
| `<figcaption>` | 이미지 설명          | `<figcaption>사진 설명</figcaption>`      |

---

## 📋 목록 태그

| 태그     | 용도       | 예시                    |
| ------ | -------- | --------------------- |
| `<ul>` | 순서 없는 목록 | `<ul>...</ul>`        |
| `<ol>` | 순서 있는 목록 | `<ol>...</ol>`        |
| `<li>` | 목록 항목    | `<li>사과</li>`         |
| `<dl>` | 설명 목록    | `<dl>...</dl>`        |
| `<dt>` | 설명할 항목   | `<dt>HTML</dt>`       |
| `<dd>` | 항목 설명    | `<dd>웹 문서 작성 언어</dd>` |

---

## 📊 표(Table) 태그

| 태그        | 용도        | 예시                   |
| --------- | --------- | -------------------- |
| `<table>` | 표 전체      | `<table>...</table>` |
| `<tr>`    | 표의 행      | `<tr>...</tr>`       |
| `<th>`    | 제목 셀      | `<th>이름</th>`        |
| `<td>`    | 일반 셀      | `<td>김태윤</td>`       |
| `<thead>` | 표의 머리 부분  | `<thead>...</thead>` |
| `<tbody>` | 표의 본문     | `<tbody>...</tbody>` |
| `<tfoot>` | 표의 마지막 부분 | `<tfoot>...</tfoot>` |
| `colspan` | 여러 열 합치기  | `<td colspan="2">`   |
| `rowspan` | 여러 행 합치기  | `<td rowspan="2">`   |

---

## 🧾 입력/폼 태그

| 태그           | 용도        | 예시                         |
| ------------ | --------- | -------------------------- |
| `<form>`     | 입력 양식     | `<form>...</form>`         |
| `<input>`    | 다양한 입력    | `<input type="text">`      |
| `<label>`    | 입력 요소의 설명 | `<label>이름</label>`        |
| `<textarea>` | 여러 줄 입력   | `<textarea></textarea>`    |
| `<button>`   | 버튼        | `<button>확인</button>`      |
| `<select>`   | 선택 목록     | `<select>...</select>`     |
| `<option>`   | 선택 항목     | `<option>남자</option>`      |
| `<fieldset>` | 폼 요소 그룹화  | `<fieldset>...</fieldset>` |
| `<legend>`   | 그룹 제목     | `<legend>회원정보</legend>`    |

---

## 🏗️ HTML 구조/레이아웃 태그

| 태그          | 용도          | 예시                       |
| ----------- | ----------- | ------------------------ |
| `<div>`     | 영역을 나눌 때 사용 | `<div>내용</div>`          |
| `<span>`    | 문장 일부 영역 지정 | `<span>강조</span>`        |
| `<header>`  | 머리말 영역      | `<header>...</header>`   |
| `<nav>`     | 네비게이션 메뉴    | `<nav>...</nav>`         |
| `<main>`    | 주요 콘텐츠      | `<main>...</main>`       |
| `<section>` | 콘텐츠 구역      | `<section>...</section>` |
| `<article>` | 독립적인 콘텐츠    | `<article>...</article>` |
| `<aside>`   | 사이드 콘텐츠     | `<aside>...</aside>`     |
| `<footer>`  | 하단 영역       | `<footer>...</footer>`   |

---

## 🎬 멀티미디어 태그

| 태그         | 용도             | 예시                            |
| ---------- | -------------- | ----------------------------- |
| `<audio>`  | 오디오 삽입         | `<audio controls>...</audio>` |
| `<video>`  | 동영상 삽입         | `<video controls>...</video>` |
| `<source>` | 미디어 파일 지정      | `<source src="video.mp4">`    |
| `<iframe>` | 다른 웹페이지/콘텐츠 삽입 | `<iframe src="..."></iframe>` |

---

# ⭐ 자주 사용하는 HTML 태그

다음 태그들은 웹프로그래밍을 공부할 때 특히 자주 사용한다.

* `<h1>` ~ `<h6>` : 제목
* `<p>` : 문단
* `<a>` : 링크
* `<img>` : 이미지
* `<ul>` / `<ol>` / `<li>` : 목록
* `<table>` / `<tr>` / `<th>` / `<td>` : 표
* `<form>` / `<input>` / `<button>` : 입력 폼
* `<div>` / `<span>` : 영역 구분
* `<header>` / `<nav>` / `<main>` / `<section>` / `<footer>` : 웹페이지 구조

---

# 💻 기본 HTML 문서 예시

```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>내 홈페이지</title>
</head>

<body>

    <h1>안녕하세요!</h1>

    <p>저의 홈페이지입니다.</p>

    <a href="https://www.google.com">구글 바로가기</a>

    <br><br>

    <img src="image.jpg" alt="이미지">

    <h2>좋아하는 음식</h2>

    <ul>
        <li>파스타</li>
        <li>치킨</li>
        <li>피자</li>
    </ul>

    <h2>학생 정보</h2>

    <table>
        <tr>
            <th>이름</th>
            <th>나이</th>
        </tr>
        <tr>
            <td>김태윤</td>
            <td>21</td>
        </tr>
    </table>

    <br>

    <form>
        <label>이름:</label>
        <input type="text">

        <button>확인</button>
    </form>

</body>
</html>
```

# 📌 태그 공부 순서

### 1단계 — 기본

`html` → `head` → `title` → `body`

### 2단계 — 텍스트

`h1~h6` → `p` → `br` → `strong` → `b`

### 3단계 — 링크와 이미지

`a` → `img`

### 4단계 — 목록과 표

`ul` → `ol` → `li` → `table` → `tr` → `th` → `td`

### 5단계 — 입력

`form` → `input` → `label` → `button` → `select` → `textarea`

### 6단계 — 웹페이지 구조

`header` → `nav` → `main` → `section` → `article` → `aside` → `footer`

### 7단계 — CSS와 JavaScript 연결

HTML은 **구조**, CSS는 **디자인**, JavaScript는 **동작**을 담당한다고 생각하면 된다.
