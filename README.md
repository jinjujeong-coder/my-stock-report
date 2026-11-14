# 🚀 SpaceX (SPCX) 주식 대시보드 (최근 1개월 보고서)

> **초보자도 이해하기 쉬운 스페이스X(NASDAQ: SPCX) 최근 1개월 주가 분석 및 기업 핵심 요약 대시보드**  
> GitHub Pages를 통해 브라우저에서 바로 확인 가능한 반응형 웹 애플리케이션입니다.

---

## 🌟 주요 특징 (Key Features)

1. **최근 1개월 인터랙티브 종가 차트**
   - Chart.js 기반의 오로라 네온 그라데이션 차트
   - 일자별 종가(USD), 원화 환산가(KRW), 고가/저가, 거래량 툴팁 제공
   - 공모가($135.00) 기준선 켜기/끄기 토글 지원

2. **한눈에 보는 3단계 흐름 요약 (3-Phase Summary)**
   - **Phase 1 (10월 중순):** 실적 기대감과 1개월 최고가($166.18) 랠리
   - **Phase 2 (10월 말~11월 초):** 대선 전후 거시 불확실성 및 단기 급락($120.39)
   - **Phase 3 (11월 중순):** 공모가($135.00) 지지선 확인 후 반등 안착($139.11)

3. **정보 신뢰도 3단계 배지 표기**
   - 🟢 `사실 (Fact)` : 나스닥 거래소 체결가, 공식 공시 및 실적
   - 🟣 `AI 해석 (AI Analysis)` : 시장 변동성 및 수급 요인 분석
   - 🟡 `확인 필요 (Needs Check)` : 기밀 안보 계약(스타실드) 마진율, 락업 해제 상세 물량

4. **⚡ 초보자 모의 투자 계산기**
   - 주식 수를 입력하면 공모가 대비 현재 평가 금액 및 수익률(+$41.10 / +3.04%) 실시간 자동 계산

5. **사업 구조 풀이 & 투자자 체크리스트**
   - 스타링크(Starlink), 팰컨9(Falcon 9), 스타십(Starship), 스타실드(Starshield) 4대 핵심 사업 설명
   - 스타십 시험 비행, 스마트폰 직결(Direct to Cell) 통신, 12월 보호예수 해제 등 주요 변수 정리

---

## 🛠️ 기술 스택 (Tech Stack)

- **Frontend:** Semantic HTML5, Modern CSS3 (Glassmorphism & Aurora Glow), JavaScript (Vanilla ES6+)
- **Library:** Chart.js v4.4.1 (CDN)
- **Typography:** Plus Jakarta Sans, Pretendard, JetBrains Mono
- **Hosting:** GitHub Pages

---

## 📂 프로젝트 구조 (Project Structure)

```text
├── index.html                  # 메인 대시보드 웹 애플리케이션
├── spacex_market_data.json     # 수집된 최근 1개월 시세 원시 데이터
├── .gitignore                  # Git 추적 제외 설정
└── README.md                   # 프로젝트 안내 문서
```

---

## 📊 데이터 기준 및 면책 안내 (Disclaimer)

- **자료 기준일:** 2026년 11월 13일 (미국 현지 정규장 마감 기준)
- **통화 환산 기준:** 1 USD = 1,400 KRW
- **출처:** NASDAQ Global Select Market 공시, StockAnalysis, TradingView, SpaceX 공개 자료
- **면책 공지:** 본 프로젝트는 공개된 과거 자료를 바탕으로 작성된 **AI 초안 대시보드**입니다. 실시간 시세가 아니며 특정 종목의 매수 또는 매도를 권유하지 않습니다.
