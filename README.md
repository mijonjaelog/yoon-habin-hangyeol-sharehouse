# 윤하빈 · 한결대 셰어하우스

카미챗 캐릭터 윤하빈의 독립형 소개 홈페이지. 사용자 제공 `YOON_HABIN_DETAIL_FINAL_20261109_lite_code.html`을 바탕으로 편집했습니다.

- GitHub 계정: `mijonjaelog`
- 새 저장소 이름: `yoon-habin-hangyeol-sharehouse`
- 예상 GitHub Pages 주소: `https://mijonjaelog.github.io/yoon-habin-hangyeol-sharehouse/` **(Pages 활성화 후 실제 공개 주소를 확인)**
- 버전: `v1`
- 작성일시: `2026-11-09 10:15 KST`

## 파일별 역할

| 파일 | 용도 |
|---|---|
| `index.html` | GitHub Pages 홈페이지 전체 소스. 원본의 시간별 테마/카드 뒤집기/챗 프리뷰/향 UI 유지 |
| `KAMI_PROFILE.html` | 카미챗 **공개 캐릭터 소개 HTML** 입력란에 붙일 짧은 자기소개 + 배너. 파일 전체를 복사 |
| `KAMI_BANNER.html` | 기존 카미챗 공개 소개 아래에 **추가할 배너만** 모아 둔 코드 |
| `images/README.md` | 윤하빈 이미지 2장을 추후 업로드하기 위한 경로 설명 |
| `.nojekyll` | GitHub Pages에서 빌드 처리 없이 정적 파일 제공용 |

## GitHub 연결 방법

1. GitHub 계정 `mijonjaelog`로 로그인하고 https://github.com/new 를 엽니다.
2. **Repository name**: `yoon-habin-hangyeol-sharehouse`; **Visibility**: `Public`으로 선택합니다. `Add a README file`은 선택해도 됩니다.
3. **Create repository**를 누릅니다. 저장소 생성 및 홈페이지 파일 업로드는 완료했습니다.
4. 저장소 **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main → /(root) → Save**로 설정합니다.
5. Pages가 게시되면 화면에 표시되는 실제 주소를 확인하세요. 예상 주소는 `https://mijonjaelog.github.io/yoon-habin-hangyeol-sharehouse/`입니다.
6. `KAMI_PROFILE.html` 또는 `KAMI_BANNER.html`의 코드만 카미챗 **수정 및 등록 → 캐릭터 소개(HTML)**에 붙여 넣습니다. 카미챗 소개에는 `index.html` 전체를 넣지 않습니다.

> 현재 `index.html`, `KAMI_PROFILE.html`, `KAMI_BANNER.html` 및 안내 파일을 전용 GitHub 저장소에 업로드했습니다. **GitHub Pages 활성화 및 실제 배포 확인은 별도 단계**입니다. 기존 `samsaenghwa` 저장소는 변경하지 않았습니다. 공개 사이트에는 비공개 프롬프트를 포함하지 마세요.

## 이미지 2장 넣기

`images/habin-front.webp`, `images/habin-back.webp` 두 파일을 사용합니다. 실제 인물 이미지가 아직 없다면 프로필 카드가 CSS 그라디언트/타이포그래피로 안전하게 보입니다. 이미지 업로드 전까지 이미지 URL은 임의의 외부 파일로 연결하지 않았습니다. 이미지가 생기면 두 파일을 `images/` 폴더에 같은 이름으로 올리면 됩니다. 1:1 카드보다 3:4 인물 이미지를 권장하며, 원본 이미지의 사용 권한을 확인해 주세요.

## 카미챗 공개 HTML 호환성

- `KAMI_PROFILE.html`과 `KAMI_BANNER.html`은 플랫폼 허용 태그/인라인 스타일만 사용했습니다.
- 자바스크립트, `<style>` 태그, iframe, CSS 클래스, 고정 포지션을 포함하지 않습니다.
- 반면 `index.html`은 GitHub Pages에서 작동하도록 만든 정식 웹페이지이므로 CSS/JavaScript를 포함합니다.
- 카미챗에서 주소가 실제 열리는지 확인한 뒤 작품을 게시하세요. 배포 전 링크는 404가 될 수 있습니다.

## 수정 시 주의

대사와 인물 관계·오메가버스 설정은 사용자가 제공한 원본을 우선했습니다. 이미지 경로 대응을 위해 카드에 fallback만 추가했습니다. `KAMI_PROFILE.html`의 한 줄 캐치프레이즈는 공개 소개용으로 새롭게 구성한 문안입니다.

## v3 GitHub 업데이트

- `index.html`: 한결대 셰어하우스 섹션에 층별 배치 이미지와 공용 공간 설명을 추가했습니다.
- `images/hangyeol-sharehouse-floorplan.svg`: 최신 평면도의 ROOM 01~06 배치와 인물 이름을 표기한 웹용 SVG 도식입니다. 원본 PNG 파일은 별도 미게시 상태입니다.
- `HANGYEOL_SHAREHOUSE_PROMPT_v3.txt`: 방번호/기존 호수 대응, 동선, 공용공간, NPC 위치, [user] 선택권을 반영했습니다.
- 기존 `101/102/201/202/203/204` 표기와 새 평면도의 ROOM 01~06 표기는 서로 대응하며, 별개의 방을 뜻하지 않습니다.
