# ENARO PROTEIN 랜딩페이지

에나로(ENARO) 단백질 50g RTD 음료를 소개하는 포트폴리오용 반응형 랜딩페이지입니다. 제공받은 제품 보틀 이미지, 로고, 20초 광고 영상 및 랜딩페이지 참고 이미지를 활용했습니다.

## 폴더 구성

- `index.html` — 페이지의 문구와 섹션 구조
- `styles.css` — 색상, 레이아웃, 모바일 반응형 디자인
- `script.js` — 맛 선택 버튼과 모바일 메뉴 동작
- `assets/enaro-protein-bottle.png` — 제공받은 제품 보틀 이미지
- `assets/enaro-logo.png` — 제공받은 ENARO 로고(투명 여백 정리)
- `assets/enaro-protein-logo.png` — 제공받은 ENARO PROTEIN 로고(투명 여백 정리)
- `assets/enaro-ad-video.mp4` — 제공받은 20초 광고 영상
- `assets/landing-design-reference.png` — 랜딩페이지 디자인 참고 이미지

## 1. VS Code에서 처음 실행하기

1. ZIP 파일을 먼저 압축 해제합니다. `enaro-landing-page` 폴더가 생깁니다.
2. VS Code를 실행합니다.
3. 상단 메뉴 `File(파일) > Open Folder...(폴더 열기)`를 누릅니다.
4. 압축 해제한 `enaro-landing-page` 폴더를 선택하고 `폴더 선택`을 누릅니다.
5. 화면 왼쪽 탐색기에서 `index.html`, `styles.css`, `script.js`, `assets` 폴더가 보이는지 확인합니다.
6. VS Code에 `Restricted Mode` 또는 `Workspace Trust` 안내가 보이면, 직접 만든 이 프로젝트 폴더가 맞는지 확인한 뒤 `Trust` 또는 `Yes, I trust the authors`를 선택합니다.
7. 왼쪽 탐색기에서 `index.html`을 클릭합니다.
8. 아래 상태 표시줄의 `Go Live`를 누릅니다. 보이지 않으면 `Ctrl + Shift + P`를 누르고 `Live Server: Open with Live Server`를 검색해 실행합니다. 그래도 안 되면 `index.html` 탭에서 마우스 오른쪽 버튼을 누르고 `Open with Live Server`를 선택합니다.
9. 브라우저가 열리면 로컬 랜딩페이지가 표시됩니다. 파일을 저장하면 보통 브라우저가 자동으로 갱신됩니다.

## 2. GitHub에 업로드하기

1. GitHub에 로그인하고 오른쪽 위 `+` > `New repository`를 선택합니다.
2. 저장소 이름을 `enaro-landing-page`로 입력합니다.
3. `Public`을 선택하고 `Create repository`를 누릅니다. (포트폴리오를 공개하고 싶지 않으면 Private으로 둘 수 있지만 GitHub Pages 공개 설정은 계정/플랜 조건을 확인해야 합니다.)
4. 새 저장소 화면에서 `uploading an existing file` 링크를 선택합니다.
5. 컴퓨터의 `enaro-landing-page` 폴더 안에 있는 **파일과 assets 폴더**를 업로드 영역에 끌어다 놓습니다. 폴더를 통째로 ZIP 파일로 올리는 게 아니라, 압축을 푼 안쪽 파일들을 올려야 합니다.
6. 아래 `Commit changes`를 눌러 저장합니다.

## 3. GitHub Pages로 사이트 공개하기

1. GitHub 저장소에서 `Settings`를 엽니다.
2. 왼쪽 메뉴에서 `Pages`를 선택합니다.
3. `Build and deployment`의 `Source`를 `Deploy from a branch`로 선택합니다.
4. Branch는 `main`, 폴더는 `/ (root)`로 선택하고 `Save`를 누릅니다.
5. 잠시 기다린 뒤 같은 Pages 화면에 표시되는 사이트 링크를 엽니다. 처음 공개까지 몇 분 걸릴 수 있습니다.

## 4. 문구와 이미지 수정하기

- 글자와 섹션 순서: `index.html`
- 색상/간격/글자 크기: `styles.css` 맨 위의 `:root` 색상 변수부터 수정
- 버튼 동작: `script.js`
- 이미지 교체: `assets` 폴더의 파일을 교체하고 HTML의 `src="assets/파일명"`도 맞게 수정

## 확인할 점

- 이 페이지는 가상 브랜드를 위한 포트폴리오 시안이며 결제 시스템은 연결되어 있지 않습니다.
- 구매 문의 버튼은 예시 이메일 주소로 연결되어 있습니다. 실제 판매에 사용하기 전에는 실제 구매 링크/문의 주소로 바꿔야 합니다.
- 초코맛/기본맛/바닐라맛은 디자인상 맛 선택 카드입니다. 실제 맛별 제품 사진이 별도로 있다면 해당 이미지로 교체하면 완성도가 더 높아집니다.
- 무설탕/저지방/영양 성분 관련 표기는 실제 제품 확정 정보와 일치하는지 게시 전에 확인하세요.
