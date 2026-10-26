# 노래방 노트
서버 설치나 빌드 없이 사용하는 단일 HTML 사이트입니다. 곡 데이터, CSS, JavaScript가 index.html에 포함되어 있습니다.

## GitHub Pages 배포
1. GitHub에서 public 저장소를 만듭니다. 예: karaoke-note
2. ZIP을 압축 해제하고 index.html, .nojekyll, README.md를 저장소 최상위에 업로드합니다. ZIP 자체를 올리거나 상위 폴더째 올리지 마세요.
3. Settings → Pages → Source: Deploy from a branch
4. Branch: main, Folder: /(root)를 선택하고 Save.
5. 배포 완료 후 Pages 화면의 Visit site를 누릅니다.
기본 주소 형식: https://사용자명.github.io/karaoke-note/
GitHub 계정은 배포자에게만 필요하며 방문자는 로그인하지 않습니다.

## 사용
index.html을 PC 브라우저에서 직접 열 수도 있습니다.
웹에서 사용하려면 위 절차로 배포하세요.
기존 사이트에서 전체 백업을 내려받고 새 주소에서 가져오기 하면 개인 기록을 옮길 수 있습니다.
개인 기록은 방문자의 브라우저 localStorage에 저장됩니다. 기기 간 자동 동기화는 없습니다.
유튜브 영상과 검색은 인터넷 연결이 필요합니다.

## 데이터
6,673개 항목, TJ 번호가 있는 항목 6,653개. 수집 기준 2026-10-26.
한글 독음 상당수는 자동 생성으로 교정이 필요합니다.
직접 영상 링크는 2개이며 나머지는 영상 검색 링크입니다.
곡 번호와 데이터는 자동 갱신되지 않습니다.
