# woong — 랜덤 캐릭터 디펜스 (Random Character Defense)

단일 HTML 기반 전략 타워 디펜스 게임 저장소입니다.  
10개 월드(각 24인 배치 대형), 7단계 등급 합성(일반 → 초월), 장비 강화/제련 대장간, 특성 연구소, 퀘스트 및 Web Audio 효과음/BGM을 별도 빌드 과정 없이 바로 실행할 수 있습니다.

## 플레이 링크 (GitHub Pages)

- **웹 실행 주소**: `https://wjsrlfdnd-gif.github.io/woong/`
  *(GitHub 저장소 **Settings → Pages**에서 Source: `Deploy from a branch`, Branch: `main` / `/ (root)` 활성화 후 약 1~2분 뒤 접속 가능합니다.)*

## 파일 구성

- `index.html` — 게임 본체 (모든 유닛·월드 아트, 로직, Web Audio 사운드 포함)
- `sw.js` — PWA 오프라인 캐시 및 홈 화면 앱 설치 지원용 서비스 워커
- `.nojekyll` — GitHub Pages 정적 배포 시 불필요한 Jekyll 빌드 생략

## 로컬 테스트 방법

`index.html`을 직접 열거나 VS Code Live Server / `npx serve .` / `python -m http.server 8080` 등 정적 HTTP 서버로 루트 경로(`/`)를 열어 테스트하면 `sw.js` 등록 및 PWA 기능까지 동일하게 동작합니다.
