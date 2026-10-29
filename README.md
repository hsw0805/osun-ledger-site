# 오순 가계부 소개 페이지

「오순 가계부」(오순도순 함께 쓰는 가계부)를 소개하는 웹페이지예요. 파일은 `index.html` 하나이고, 글꼴·그림·꾸밈이 모두 안에 들어 있어서 바깥에서 받아 오는 것이 없어요.

- 앱 쓰러 가기: https://family-ledger.expo.app
- 계정 지우기: https://family-ledger.expo.app/delete-account

## 기능이 새로 나오면

`index.html` 안에 기능 목록이 두 개 있어요.

- `<ul class="features" id="now">` — 지금 되는 것
- `<ul class="features" id="soon">` — 곧 나와요

기능 하나는 `<li> … </li>` 한 줄이에요. 그 기능이 나오면 **그 줄을 통째로 잘라 `id="now"` 목록에 붙이면 끝**이에요. 「준비 중」 꼬리표는 위치에 따라 저절로 붙고 떨어져요.

없는 기능을 「지금 되는 것」에 쓰지 않아요. 실제로 나간 것만 옮겨요.

## 그림

첫 화면의 폰 그림은 HTML로 직접 그렸어요. 장부 이름·사람·가게·금액은 모두 지어낸 예시예요. 실제 가족 이름·금액·캡처·이메일은 넣지 않아요.

## 색

색·글자 크기·모서리는 앱의 `src/ui/theme.ts`(Apple 테마) 값과 같아요. 어두운 화면은 폰·PC 설정을 따라가요.

## 올리는 법(GitHub Pages, 무료)

공개 저장소의 Settings › Pages › 「Deploy from a branch」 › `main` / `/(root)` 를 고르면, 몇 분 뒤 `https://<GitHub 아이디>.github.io/<저장소 이름>/` 에 열려요.
