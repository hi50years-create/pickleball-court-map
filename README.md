# 우리 동네 피클볼 코트 지도

Leaflet + OpenStreetMap 기반 피클볼 코트 지도 프로토타입입니다.
GitHub Pages로 배포하면 `https://{아이디}.github.io/{저장소이름}/` 주소로 바로 접속 가능합니다.

## 배포 전 체크리스트
- [ ] `index.html` 안 `SEED_COURTS` 배열을 예시 데이터 → 직접 확인한 실제 코트로 교체
- [ ] 제보 데이터는 shared storage라 이 페이지를 보는 모든 사람에게 공개된다는 점 페이지 어딘가에 안내 문구로 추가 고려
- [ ] 배포 후 모바일에서 실제로 지도 클릭 → 등록 → 새로고침 후 마커 유지되는지 테스트

## 나중에 카카오맵으로 바꾸고 싶다면
1. 카카오 개발자센터(developers.kakao.com)에서 앱 등록
2. 플랫폼 > Web에 배포된 GitHub Pages 주소(`https://{아이디}.github.io`) 등록
3. `index.html`의 Leaflet 스크립트/타일 부분을 카카오맵 JS SDK로 교체
