# Heewon Yang — academic website

GitHub Pages용 개인 학술 홈페이지입니다. 별도 빌드나 패키지 설치 없이 작동합니다.

예정 주소: https://esczzang.github.io/

## 파일 수정

- `index.html`: 소개, 논문 제목과 공저자, 학회 발표
- `assets/style.css`: 글꼴, 색상, 간격, 모바일 화면
- `assets/cv_heewon_yang.pdf`: 공개 CV. CV를 수정한 뒤 이 파일도 갱신합니다.
- `assets/favicon.svg`: 브라우저 탭 아이콘

논문은 현재 CV의 Working Papers / Work in Progress 분류를 유지합니다. 공개 초록이나 논문 파일이 준비되면 해당 논문에 실제 링크와 `<details><summary>Abstract</summary>…</details>`를 추가할 수 있습니다. 현재는 빈 버튼이나 가상의 설명을 표시하지 않습니다.

사진은 제공되지 않아 넣지 않았습니다. 사진을 추가하려면 본인이 선택한 파일을 `assets/`에 넣고 profile 영역에 이미지 요소를 추가합니다.

## GitHub Pages 배포

1. GitHub의 `Esczzang` 계정에 `esczzang.github.io` 저장소를 생성합니다. 기존 저장소가 있다면 먼저 내용을 확인하고 합칩니다.
2. 이 폴더의 파일을 `main` 브랜치에 올립니다.
3. 저장소 Settings → Pages → Build and deployment에서 **Deploy from a branch**를 선택합니다.
4. Branch는 **main**, 폴더는 **/ (root)**로 설정하고 저장합니다.
5. 배포 완료 후 https://esczzang.github.io/ 를 확인합니다.

GitHub 공식 안내: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## 구성

Eva Lestant의 학술 홈페이지를 참고해 프로필 사이드바, 여백, 연구 분류 중심의 구조를 새로 구현했습니다. 다른 연구자의 사진·소개·논문 내용은 포함하지 않았습니다. 개인정보와 연구 내용의 기준은 본인의 CV 및 제공한 SOP입니다.

실행 코드, 외부 글꼴, 분석 추적 도구, 폼, 쿠키를 사용하지 않습니다. GitHub Pages 외에도 정적 파일 호스팅에서 작동합니다.
