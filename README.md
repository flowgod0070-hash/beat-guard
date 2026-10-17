# BEAT GUARD v4.18 EDM NEON CLUB • FINAL
GitHub Pages 배포용 최종 버전

## 파일
- index.html : 단일 파일 게임 2931.7 KiB (외부 의존성 없음)
- cyan_robot_transparent.png / magenta_robot_transparent.png : 원본 투명 PNG (참고용)
- README.md : 이 파일

## GitHub Pages 배포 (3분)

1. GitHub에서 새 저장소 생성
   - 이름: beat-guard
   - Public 체크
   - README 초기화 체크 해제

2. index.html 업로드
   - 웹 방식: Add file > Upload files > index.html 드래그 > Commit changes
   - git 방식:
     git clone https://github.com/YOURNAME/beat-guard.git
     cp index.html beat-guard/
     cd beat-guard
     git add index.html
     git commit -m "v4.18 EDM NEON CLUB FINAL"
     git push

3. Pages 활성화
   - Settings > Pages
   - Build and deployment > Source: Deploy from a branch
   - Branch: main / root 선택 > Save
   - 1-2분 후 https://YOURNAME.github.io/beat-guard/ 에서 플레이 가능

## v4.18 FINAL 스펙

### 기반 (v4.17)
- 레이아웃: ( hero ) - 방패 14% 폭, 4px 테두리, 20px 글로우, 0.28 투명도
- 적: 68px desktop / 52px mobile, 불규칙 움직임 (속도 0.85-1.25, 높이 랜덤, 흔들림)
- 주인공: 160px desktop / 100px mobile, 중앙 압도적 크기
- 점수판: 상단 BATTLE 카드 점수 36px + 콤보 48px만 크게, P1/P2는 하단 노란 RANKING 바로 통합
- 하단: 흰 VS INTENSITY 바 44px + 노란 RANKING 바 44px 동일 크기 8px 간격 스택
- 배경 #06060a 가독성 확보, 버전 배지 minimal top-left
- 투명 PNG, 흰 박스 없음

### 신규 EDM 네온 클럽
- 배경 펄스: 120 BPM (500ms)마다 #06060a -> #0a0a1e 플래시 페이드 150ms
- 레이저 빔: 대각선 시안 #00F0FF + 마젠타 #FF00E5, opacity 0.15, glow 20px, 천천히 이동
- 방패 RGB: 500ms마다 cyan -> magenta -> yellow 사이클, glow 20px->40px 펄스
- 주인공 펌프: 비트마다 scale 1.0->1.15 (160px->184px) 200ms elastic, 눈 밝기 1.5배, Y -2px 흔들림
- 히트 이펙트: 12개 네온 파티클 폭발 + BOOM!/DROP! 텍스트 32px 네온 아웃라인 + 화면 흔들림 4px
- 콤보 레인보우: 콤보 5+ 시 그라데이션
- 비주얼라이저: 상단 5바 20-60px 랜덤 높이 시안->마젠타 그라데이션
- 하단 바 네온 글로우: 흰 바 시안 12px, 노란 바 마젠타 12px

## 로컬 테스트
index.html 더블클릭하면 브라우저에서 바로 실행됨

## 실행 경로
container:///mnt/data/beat_guard_agentic_artifact_1_fdd32b8f0654.html

## 다음
- v4.19에서 사운드 트랙 추가 예정

Enjoy the club!
