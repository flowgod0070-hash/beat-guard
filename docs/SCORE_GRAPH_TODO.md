# 점수 막대그래프 구현 계획

## 실시간 VS 바 (In-Game)
- 상단 중앙에 P1(청록) vs P2(마젠타) 비율 바
- 전체 = P1+P2, 비율로 나눠서 표시
- 리드 바뀌면 펄스 애니메이션

## 게임 오버 그래프
1. Score Timeline (Line + Area)
   - X: 0~60초, Y: 점수
   - P1 청록 라인, P2 마젠타 라인

2. Accuracy Bar Chart
   - PERFECT / GOOD / MISS 카운트
   - 1P: 3개 바
   - 2P: 그룹 바 (P1 vs P2 비교)

3. Max Combo Bar

구현: Canvas 2D, neon glow, rounded bars, beat sync pulse
