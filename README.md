# BEAT GUARD v4.17 - THIN SHIELD 14% - FINAL FOR GITHUB

## What's included
- index.html (single file game, 2930.2 KiB, no external deps)
- Transparent robot PNGs (reference)
- This README

## GitHub Pages 배포 방법

1. GitHub에서 새 repo 생성: beat-guard (Public)
2. 이 폴더의 index.html을 repo root에 업로드
   - 방법 A: GitHub 웹에서 Add file > Upload files > index.html 드래그
   - 방법 B: git
     git init
     git add index.html
     git commit -m "v4.17 thin shield 14% final"
     git branch -M main
     git remote add origin https://github.com/YOURNAME/beat-guard.git
     git push -u origin main

3. Settings > Pages > Source: Deploy from branch > main / root > Save
4. 1-2분 후 https://YOURNAME.github.io/beat-guard/ 에서 플레이 가능

## v4.17 변경점
- Step1 점수판 정리: 상단 BATTLE 카드 점수/콤보만 크게, P1/P2는 하단 노란 RANKING 바로 통합
- Step2 방패 두께: 18% -> 14%, border 6px->4px, glow 28px->20px, opacity 0.35->0.28 가볍게
- 레이아웃: ( hero ) 두꺼운->얇은 방패, 적 68/52px 불규칙, 주인공 160/100px 중앙
- 하단: 흰 VS INTENSITY 바 + 노란 RANKING 바 동일 크기 44px 8px gap
- 배경 #06060a 가독성, 버전 배지 minimal top-left
- 투명 PNG, 흰박스 없음

## 로컬 테스트
index.html 더블클릭으로 브라우저에서 바로 실행 가능

## 다음 버전
- v4.18 EDM 버전 예정
