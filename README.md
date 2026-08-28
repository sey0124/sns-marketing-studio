# SNS Marketing Studio

상품·고객·채널 정보를 입력하면 SNS 마케팅 기획서, Gemini Gems 지침, 콘텐츠 아이디어를 생성하는 실습형 웹앱입니다.

## 구성

- `index.html` — 메인 웹앱
- `assets/favicon.svg` — 파비콘
- `assets/og-image.svg` — 공유 미리보기 이미지
- `manifest.webmanifest` — 웹앱 메타 정보
- `404.html` — GitHub Pages 404 화면
- `robots.txt` — 검색엔진 크롤링 허용
- `.nojekyll` — GitHub Pages에서 정적 파일을 그대로 배포

## GitHub Pages 배포 방법

1. GitHub에서 새 저장소를 만듭니다. 예: `sns-marketing-studio`
2. 이 폴더 안의 파일을 **폴더째가 아니라 저장소 최상위(root)** 에 업로드합니다.
3. 저장소에서 **Settings → Pages** 로 이동합니다.
4. **Build and deployment → Source** 를 `Deploy from a branch`로 선택합니다.
5. Branch를 `main`, 폴더를 `/(root)`로 선택하고 **Save** 합니다.
6. 배포가 완료되면 `https://사용자이름.github.io/sns-marketing-studio/` 형태의 주소로 접속합니다.

## PDF 다운로드

PDF 생성은 `html2pdf.js` CDN을 사용합니다. 따라서 PDF 다운로드 시 인터넷 연결이 필요합니다. 네트워크가 차단된 환경에서는 `인쇄` 버튼을 이용해 브라우저의 **PDF로 저장** 기능을 사용할 수 있습니다.

## 수정 포인트

`index.html` 상단의 CSS `:root`에서 주요 색상을 변경할 수 있습니다.

- `--brand: #6d28d9` — 메인 보라색
- `--brand2: #a855f7` — 보조 보라색
- `--ink: #17131c` — 주요 검정 텍스트

브랜드명과 하단 표기는 `AI 콘텐츠 클래스` 관련 문구를 검색해 수정하면 됩니다.
