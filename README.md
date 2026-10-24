# 국소배기 덕트 사이즈 계산기 — vovexe1 GitHub Pages용

## 업로드 방법
1. 이 ZIP을 다운로드한 뒤 압축을 풉니다.
2. GitHub 저장소 `duct-calculator-261017-1`의 최상위(root)에 ZIP 자체가 아니라 압축 안의 파일을 모두 업로드합니다.
3. 기존 파일을 덮어쓸지 묻는 경우 `index.html`, `manifest.webmanifest`, `service-worker.js`를 포함해 모두 교체합니다.
4. Settings → Pages에서 Branch `main`, Folder `/(root)`인지 확인합니다.
5. 배포 완료 후 Android Chrome에서 https://vovexe1.github.io/duct-calculator-261017-1/ 를 엽니다.
6. 페이지에서 `앱 설치` 버튼이 나타나면 누릅니다. 버튼이 나타나지 않으면 Chrome 메뉴(⋮)에서 `앱 설치` 또는 `홈 화면에 추가`를 선택합니다.

## 포함 파일
- `index.html` — 계산기 및 설치 버튼
- `manifest.webmanifest` — 이 저장소 경로에 맞춘 설치 정보
- `service-worker.js` — 오프라인 캐시 및 fetch 처리
- `icon-192.png`, `icon-512.png` — 앱 아이콘
- `.nojekyll`, `README.md`

참고: 이 파일은 APK가 아니라 GitHub Pages용 PWA입니다. Chrome/Android의 설치 메뉴는 브라우저 버전, 설치 상태, 웹앱의 설치 조건에 따라 달라질 수 있습니다.
