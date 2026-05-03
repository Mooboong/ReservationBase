# 이메일 문의 기능 구현 가이드

랜딩 페이지의 '문의하기' 폼을 통해 실제 메일을 수신하기 위한 방법들입니다.

## 1. 외부 폼 처리 서비스 (추천: Formspree)
별도의 서버 구축 없이 HTML 수정만으로 메일을 받을 수 있는 가장 빠른 방법입니다.

### 설정 방법
1. [Formspree](https://formspree.io/) 가입 및 새로운 폼 생성.
2. 생성된 고유 ID(또는 URL)를 확인합니다.
3. `index.html`의 `<form>` 태그를 다음과 같이 수정합니다.

```html
<form action="https://formspree.io/f/{YOUR_FORM_ID}" method="POST">
  <input type="text" name="name" placeholder="이름" required />
  <input type="email" name="_replyto" placeholder="이메일" required />
  <input type="text" name="subject" placeholder="조직 / 공간 이름" />
  <textarea name="message" rows="5" placeholder="현재 운영 방식이나 문제를 설명해주세요"></textarea>
  <button type="submit" class="submit">문의 보내기</button>
</form>
```

---

## 2. Google Apps Script (무료)
구글 스프레드시트에 데이터를 쌓고 싶을 때 유용한 방법입니다.

### 장점
- 완전 무료.
- 데이터베이스 대용으로 구글 시트 활용 가능.

---

## 3. 백엔드 서버 구축
서비스 규모가 커질 경우 직접 서버(Node.js, Python 등)를 구축하여 이메일 API(SendGrid, Mailgun 등)를 연동하는 방식입니다.
