# 국소배기 덕트 사이즈 계산기

GitHub Pages로 배포할 수 있는 모바일 최적화 계산기입니다.

## GitHub Pages 배포

1. GitHub에서 새 저장소(repository)를 만듭니다.
2. 이 ZIP의 **압축을 푼 파일 전체**를 저장소 최상위(root)에 업로드합니다.
3. 저장소의 **Settings → Pages**로 이동합니다.
4. **Build and deployment → Source**에서 `Deploy from a branch`를 선택합니다.
5. Branch는 `main`, 폴더는 `/(root)`로 선택한 뒤 Save를 누릅니다.
6. 배포가 완료되면 표시된 GitHub Pages 주소를 엽니다.

## 안드로이드 홈 화면에 추가

1. GitHub Pages 주소를 Android Chrome에서 엽니다.
2. Chrome 메뉴(⋮)에서 `앱 설치` 또는 `홈 화면에 추가`를 선택합니다.
3. 설치 메뉴가 바로 보이지 않으면 사이트가 배포된 뒤 HTTPS 주소로 다시 접속하고 잠시 기다립니다.

## 포함 파일

- `index.html`: 계산기 본체
- `manifest.webmanifest`: PWA 앱 정보
- `service-worker.js`: 오프라인 캐시
- `icon-192.png`, `icon-512.png`: 앱 아이콘
- `.nojekyll`: GitHub Pages의 Jekyll 처리 비활성화

참고: GitHub Pages는 웹앱을 호스팅합니다. 이 패키지는 APK 파일이 아닙니다.
