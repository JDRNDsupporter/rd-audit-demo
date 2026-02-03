# R&D 정산 교육 플랫폼

## 배포 URL
https://jdrndsupporter.github.io/rd-audit-demo/

## GitHub Repository
https://github.com/JDRNDsupporter/rd-audit-demo

## 프로젝트 개요
에기평(KEIT) 제안용 R&D 연구비 정산 교육 데모 플랫폼

## 주요 기능
1. **정산 디펜스 게임** - 105개 부적정집행 사례 기반 턴제 퀴즈 게임
2. **틀린증빙찾기** - 증빙서류 오류 찾기 게임
3. **사례 DB 검색** - 105개 부적정집행 사례 검색/조회
4. **이상거래 탐지** - AI 기반 모니터링 대시보드 (데모용 가상 데이터)

## 기술 스택
- React + Vite
- Tailwind CSS
- GitHub Pages (자동 배포)

## 데이터 소스
- `/src/data/cases105.js` - 105개 부적정집행 사례 (KAIA PDF 기반)
- `/src/data/defenseGameData.js` - 게임용 몬스터/카드/스테이지 데이터

## 배포
- `git push`시 GitHub Actions로 자동 배포
- 워크플로우: `.github/workflows/deploy.yml`

## GitHub 인증
- 계정: JDRNDsupporter
- 토큰 scope: repo, workflow
