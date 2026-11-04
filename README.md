# Ohn Kim — personal homepage

간결한 개인 연구자 홈페이지입니다. 별도 설치나 빌드 없이 GitHub Pages에서 사용할 수 있습니다.

## 파일 구성

- `index.html`: 이름, 소개, 연락처, 학력, 논문 목록
- `assets/profile.jpg`: 프로필 사진
- `stylesheet.css`: Jon Barron 원본 템플릿의 글꼴과 기본 스타일
- `styles.css`: 페이지 레이아웃과 모바일 대응
- `drip/index.html`: DRIP 연구 페이지 자리

## 내용 수정

소개와 연락처는 `index.html`의 PROFILE 및 CONTACT 주석 위치에서 수정합니다. CV·Scholar 주소가 정해지면 실제 링크만 넣어주세요. 회색 CV·Google Scholar 표시는 아직 링크가 아닙니다. 학력은 Education 섹션에서, 논문은 PUBLICATIONS 주석 위치에서 추가합니다. DRIP의 상세 정보는 `drip/index.html`에 추가합니다. DRIP는 RA-L 논문으로 Publications에 표시하며, 제목·저자·게재 승인 연도는 `paper/camera_ready.tex`를 따릅니다.

홈페이지 템플릿을 바꿀 때도 `drip/` 경로와 사진 원본을 보존하면 연구 페이지 링크를 유지할 수 있습니다. 프로필 사진은 제공된 원본을 복사했으며 이미지 자체는 수정하지 않았습니다.

## 미리 보기

이 디렉터리에서 `python3 -m http.server 8765 --bind 127.0.0.1`을 실행한 다음 브라우저에서 `http://127.0.0.1:8765/`를 엽니다.

## GitHub Pages

`Ohn-Kim/ohn-kim.github.io` 저장소의 공개 대상 루트에 이 폴더의 내용을 넣습니다. Settings → Pages에서 배포할 브랜치와 루트 폴더를 선택하면 됩니다. 현재 폴더를 하위 폴더째 올리는 대신 `index.html`, `stylesheet.css`, `styles.css`, `assets/`, `drip/`, `.nojekyll`이 배포 루트에 오도록 합니다.

Jon Barron의 공개 개인 홈페이지 템플릿을 기반으로 합니다: https://github.com/jonbarron/jonbarron.github.io . 원본의 `stylesheet.css`를 포함하고, 800px 본문과 표 기반 프로필 레이아웃을 사용합니다. 하단에 원본 출처 링크를 유지했습니다. Lato 글꼴은 원본 스타일시트와 같이 Google Fonts에서 불러옵니다. 외부 JavaScript나 추적 스크립트는 사용하지 않습니다.
