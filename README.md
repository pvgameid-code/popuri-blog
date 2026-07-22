# 🌸 호떡해의 포푸리트릭스터 블로그

추억의 2D게임 **트릭스터(포푸리 서버)** 를 즐기는 유저 **호떡해**의 팬 블로그입니다.
빌드 도구 없이 **HTML 파일만으로 동작**하고, 아래 방법으로 **완전 무료 배포**가 가능합니다.

## 📁 구성

```
popuri-blog/
├─ index.html              ← 블로그 홈 (이벤트 규칙 + 글 목록)
├─ posts/
│  ├─ 01-first-day.html        [포푸리트릭스터] 첫날 후기
│  ├─ 02-character-guide.html  [포푸리트릭스터] 캐릭터 선택 가이드
│  ├─ 03-drill-guide.html      [포푸리트릭스터] 드릴 삽질 공략
│  ├─ 04-free-to-play.html     [포푸리트릭스터] 무과금 꿀팁
│  └─ 05-event.html            [포푸리트릭스터] 이벤트 참여 인증
├─ assets/style.css        ← 디자인
├─ images/                 ← 스크린샷 넣는 곳 (images/README.md 참고)
└─ README.md
```

모든 글은 이벤트 규칙에 맞춰 **제목이 `[포푸리트릭스터]`로 시작**하고, 본문에 **닉네임 `호떡해`** 가 들어가 있어요.

## 👀 먼저 미리보기 (내 컴퓨터에서)

`index.html` 파일을 **더블클릭**하면 브라우저에서 바로 열려요. 배포 전에 이렇게 확인하세요.

## 🚀 무료로 배포하기 (택 1)

### 방법 A. Netlify Drop — 가장 쉬움, 계정 없이 드래그 한 번 (추천)
1. <https://app.netlify.com/drop> 접속
2. 이 `popuri-blog` **폴더째로 드래그 앤 드롭**
3. 몇 초 뒤 `https://랜덤이름.netlify.app` 주소가 생성됨 → 끝!
   - (로그인하면 주소 이름도 바꿀 수 있어요)

### 방법 B. GitHub Pages — 무료, 주소 안 바뀜 (가장 안정적)
1. GitHub 가입 후 새 저장소(repository) 생성 (예: `popuri-blog`)
2. 이 폴더의 파일 전부 업로드 (`Add file → Upload files`)
3. 저장소 **Settings → Pages** 이동
4. `Branch: main` / `Folder: / (root)` 선택 후 **Save**
5. 잠시 뒤 `https://내아이디.github.io/popuri-blog/` 주소로 공개됨
   - (`.nojekyll` 파일이 이미 들어있어 바로 잘 동작해요)

### 방법 C. Cloudflare Pages — 무료, 빠름
1. <https://pages.cloudflare.com> 접속 → 로그인
2. `Create a project → Direct Upload`
3. 폴더 업로드 → 배포 → `https://프로젝트.pages.dev` 주소 생성

> 세 방법 모두 **무료**입니다. 빠르게 한 번 써보려면 **A(Netlify Drop)**,
> 오래 운영할 거면 **B(GitHub Pages)** 를 추천해요.

## 🖼️ 사진(스크린샷) 넣기

`images/README.md` 에 **찍기 쉬운 사진 목록**과 넣는 방법을 정리해뒀어요.
사진을 아직 안 넣어도 점선 박스가 예쁘게 표시되니, 글 먼저 올리고 나중에 채워도 됩니다.

## ✏️ 내용 수정

- 글 내용: `posts/` 안의 `.html` 파일을 메모장/편집기로 열어 수정
- 색상·디자인: `assets/style.css` 상단의 `:root` 색상값 변경
- 글 추가: 기존 글 파일을 복사해 새 파일로 만들고, `index.html` 목록에 카드 한 장 추가

---
🌸 게임 닉네임: **호떡해** · 트릭스터 포푸리 서버
