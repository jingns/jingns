
# HTML5 태그 단어장

## 1. `<html>`
- **용도**: HTML 문서의 시작과 끝을 나타내는 루트 요소.
- **속성**: `lang` (문서의 언어 지정)
- **예시**:
  ```html
  <html lang="ko">
    <head>...</head>
    <body>...</body>
  </html>
  ```

## 2. `<head>`
- **용도**: 문서의 메타데이터(제목, 문자셋, 스타일 등)를 포함하는 요소.
- **속성**: 없음
- **예시**:
  ```html
  <head>
    <meta charset="UTF-8">
    <title>문서 제목</title>
  </head>
  ```

## 3. `<title>`
- **용도**: 문서의 제목을 정의하며, 브라우저 탭에 표시됩니다.
- **속성**: 없음
- **예시**:
  ```html
  <title>웹페이지 제목</title>
  ```

## 4. `<body>`
- **용도**: 문서의 본문을 나타내는 요소. 콘텐츠가 여기에 포함됩니다.
- **속성**: 없음
- **예시**:
  ```html
  <body>
    <h1>안녕하세요!</h1>
    <p>HTML5 문서입니다.</p>
  </body>
  ```

## 5. `<h1>`, `<h2>`, ..., `<h6>`
- **용도**: 제목을 정의하는 태그. `<h1>`은 가장 중요한 제목이고, `<h6>`은 가장 덜 중요한 제목.
- **속성**: 없음
- **예시**:
  ```html
  <h1>가장 중요한 제목</h1>
  <h2>두 번째로 중요한 제목</h2>
  ```

## 6. `<p>`
- **용도**: 문단을 정의하는 태그.
- **속성**: 없음
- **예시**:
  ```html
  <p>이것은 하나의 문단입니다.</p>
  ```

## 7. `<a>`
- **용도**: 하이퍼링크를 정의하는 태그.
- **속성**: `href` (링크의 대상 URL), `target` (링크 열기 방식)
- **예시**:
  ```html
  <a href="https://example.com" target="_blank">Example 링크</a>
  ```

## 8. `<img>`
- **용도**: 이미지를 삽입하는 태그.
- **속성**: `src` (이미지 파일 경로), `alt` (대체 텍스트), `width`, `height`
- **예시**:
  ```html
  <img src="image.jpg" alt="이미지 설명" width="200" height="100">
  ```

## 9. `<ul>`, `<ol>`
- **용도**: 각각 순서 없는 목록과 순서 있는 목록을 정의하는 태그.
- **속성**: 없음
- **예시**:
  ```html
  <ul>
    <li>항목 1</li>
    <li>항목 2</li>
  </ul>

  <ol>
    <li>첫 번째 항목</li>
    <li>두 번째 항목</li>
  </ol>
  ```

## 10. `<li>`
- **용도**: 목록 항목을 정의하는 태그.
- **속성**: 없음
- **예시**:
  ```html
  <ul>
    <li>리스트 항목 1</li>
    <li>리스트 항목 2</li>
  </ul>
  ```

## 11. `<div>`
- **용도**: 문서의 구획을 정의하는 일반적인 블록 레벨 요소.
- **속성**: `id`, `class`, `style`
- **예시**:
  ```html
  <div class="content">
    <h2>제목</h2>
    <p>본문 내용</p>
  </div>
  ```

## 12. `<span>`
- **용도**: 인라인 요소로, 특정 텍스트를 구분하거나 스타일을 적용할 때 사용.
- **속성**: `class`, `style`
- **예시**:
  ```html
  <p>이 문장에서 <span style="color: red;">빨간색</span> 텍스트입니다.</p>
  ```

## 13. `<form>`
- **용도**: 사용자 입력을 받을 수 있는 폼을 정의하는 태그.
- **속성**: `action` (폼 데이터 전송 대상 URL), `method` (GET, POST 등)
- **예시**:
  ```html
  <form action="/submit" method="post">
    <label for="name">이름:</label>
    <input type="text" id="name" name="name">
    <input type="submit" value="제출">
  </form>
  ```

## 14. `<input>`
- **용도**: 다양한 종류의 사용자 입력을 받을 수 있는 태그.
- **속성**: `type` (입력 종류), `name`, `value`, `placeholder`
- **예시**:
  ```html
  <input type="text" name="username" placeholder="사용자 이름">
  <input type="password" name="password">
  ```

## 15. `<button>`
- **용도**: 버튼을 생성하는 태그.
- **속성**: `type`, `onclick`
- **예시**:
  ```html
  <button type="submit">제출</button>
  ```

## 16. `<table>`
- **용도**: 표를 생성하는 태그.
- **속성**: 없음
- **예시**:
  ```html
  <table>
    <tr>
      <th>헤더 1</th>
      <th>헤더 2</th>
    </tr>
    <tr>
      <td>데이터 1</td>
      <td>데이터 2</td>
    </tr>
  </table>
  ```

## 17. `<tr>`
- **용도**: 표의 행을 정의하는 태그.
- **속성**: 없음
- **예시**:
  ```html
  <tr>
    <td>셀 1</td>
    <td>셀 2</td>
  </tr>
  ```

## 18. `<th>`
- **용도**: 표의 헤더 셀을 정의하는 태그.
- **속성**: 없음
- **예시**:
  ```html
  <th>헤더 셀</th>
  ```

## 19. `<td>`
- **용도**: 표의 데이터 셀을 정의하는 태그.
- **속성**: 없음
- **예시**:
  ```html
  <td>데이터 셀</td>
  ```

## 20. `<iframe>`
- **용도**: 다른 웹 페이지를 현재 페이지에 삽입하는 태그.
- **속성**: `src` (삽입할 페이지 URL), `width`, `height`
- **예시**:
  ```html
  <iframe src="https://www.example.com" width="600" height="400"></iframe>
  ```
