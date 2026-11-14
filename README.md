# Heewon Yang — academic website

GitHub Pages용 개인 학술 홈페이지입니다. 별도 빌드나 패키지 설치 없이 작동합니다.

예정 주소: https://esczzang.github.io/

## 파일 수정

- `index.html`: 소개, 논문 제목과 공저자, 학회 발표
- `assets/style.css`: 글꼴, 색상, 간격, 모바일 화면
- `assets/cv_heewon_yang.pdf`: 공개 CV. CV를 수정한 뒤 이 파일도 갱신합니다.
- `assets/favicon.svg`: 브라우저 탭 아이콘
- `assets/photo.jpg`: 프로필 사진. 원본 파일을 유지하고 CSS로 표시 영역을 조정합니다.
- `assets/papers/sme-policy-draft.pdf`: SME 정책 논문 초안 (2026년 8월)
- `assets/papers/exchange-rates-draft.pdf`: 환율 논문 영문 초안 (2026년 10월)

논문은 현재 CV의 Working Papers / Work in Progress 분류를 유지합니다. Working Papers 두 편에는 공저자 아래에 PDF 초안 링크와 초안 날짜를 표시합니다.

프로필 사진은 `Yonsei/PhD Application/photo.jpg`에서 가져왔습니다. 첫 논문은 `epc_2025/03 발표 자료/2026년 10월 16일-midewest/midwest_draft_v1.pdf`, 두 번째는 `TEC/06 보고서/english_draft_v3/paper_draft_v3_en.pdf`의 사본입니다. PDF 내용은 수정하지 않았습니다. 첫 초안의 표제는 "The Impact of SME Support on Supply Chain Networks"이며, 홈페이지 제목은 기존 CV 기준 표기를 유지합니다.

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
