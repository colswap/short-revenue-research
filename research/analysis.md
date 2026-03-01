# 단기 수익 창출 대회 — 패턴 분석 보고서

> **기반 데이터**: 55개 사례 (cases.md + dataset.csv)
> **분석 목적**: 18일 이하 팀 경쟁에서 역사적으로 가장 효과적인 수익 창출 방식 도출
> **최초 작성**: 2026-02-27 / **업데이트**: 2026-03-01 (15개 신규 사례 반영)

---

## 1. 사례 분류 개요

| 분류 | 사례 수 | 비율 | 변동 |
|------|---------|------|------|
| Startup Weekend 계열 | 12 | 21.8% | ▲+3 (Validately, Kwoter, Chingu) |
| 해커톤 (기술) | 8 | 14.5% | ▲+1 (KAIST) |
| 소자본 챌린지 ($0~$10) | 7 | 12.7% | ▲+2 (Babson, BYU) |
| 물리적 플리핑/아비트라지 | 6 | 10.9% | ▲+1 (Coachella) |
| StartupBus | 3 | 5.5% | — |
| Amazon FBA/온라인 아비트라지 | 3 | 5.5% | — |
| 디지털 콘텐츠/어필리에이트 | 3 | 5.5% | — |
| 학생 부트캠프 | 3 | 5.5% | — |
| **7일/14일 개인 챌린지 (신규)** | **3** | **5.5%** | ▲NEW (WP Curve, NomadList, Carrd) |
| **이벤트 현장 서비스/아비트라지 (신규)** | **3** | **5.5%** | ▲NEW (SXSW, CES, 정주영) |
| **Micro-SaaS 빠른 유료화 (신규)** | **2** | **3.6%** | ▲NEW (Bannerbear, Transistor.fm) |
| 기타 기업/글로벌 해커톤 | 2 | 3.6% | — |

---

## 2. 가장 흔한 수익 모델

### 빈도 순위 (55개 전체 기준)

| 순위 | 비즈니스 모델 | 사례 수 | 대표 사례 | 변동 |
|------|-------------|---------|---------|------|
| **1** | **SaaS/디지털 제품** | **15** | Zapier, WP Curve, Carrd, Bannerbear, Transistor.fm | ▲+7 (1위 등극) |
| 2 | 마켓플레이스/중개 | 12 | Zaarly, Rover, Chingu, 정주영 배달팀 | ▲+3 |
| 3 | 직접 서비스 판매 | 10 | GC Service Team, Babson, BYU, CES Photography | ▲+4 |
| 4 | 물리적 제품 아비트라지/플리핑 | 9 | Flea Market Flipper, Steffensens, Coachella | ▲+1 |
| 5 | 콘텐츠/어필리에이트 | 4 | YouTube Channel, 30-Day Affiliate | — |
| 6 | 소셜 엔터프라이즈 | 2 | Enactus Edinburgh | — |
| 7 | 커스텀 물리 제품 | 2 | Cerealize | — |

### 핵심 관찰 (업데이트)
- **신규 1위**: SaaS/디지털 제품이 15개로 마켓플레이스를 추월. 단, 18일 이내 실제 수익 발생률은 여전히 직접 서비스·아비트라지가 우위
- **가장 빠른 매출**: 직접 서비스 + 이벤트 아비트라지 (D0~D2)
- **신규 패턴**: "선판매 후 개발(Build in Public)" Micro-SaaS 모델이 14일 이내 $1K~$4K 달성 사례 다수 추가

---

## 3. 가장 빠른 수익 발생 방식 분석

### 첫 매출까지 걸린 시간 (55개 전체 기준)

| 시간 | 방식 | 사례 |
|------|------|------|
| **0일 (당일)** | 대면 직접 판매 / 이벤트 현장 서비스 | Stanford $5 자전거 펌프, CES Photography (부스 안내문 → 즉각 예약), Coachella MD (Day 1 매입) |
| **0~2일** | B2B 즉석 계약 (프로토타입 기반) | TradeMingle ($4,000/48h), Validately ($3,000/3d cold email), SXSW Rideshare ($2,800/5d) |
| **1~2일** | 노코드 MVP + 직접 판매 | GC Startup Weekend ($900, Typeform 기반), Babson ($1,270/D1 시작), BYU ($870/D1 시작) |
| **1~3일** | 물리적 아비트라지 | Flea Market Flipper, OA Challenge, Coachella ($4,200/3d) |
| **3~5일** | 디지털 커뮤니티/공개 스프레드시트 | NomadList MVP ($566/D3), Bannerbear ($245 MRR/D3) |
| **5~7일** | 구독 서비스 직접 영업 | WP Curve ($1,116 MRR/D5~7), Stanford $5 레스토랑 예약팀 |
| **5~14일** | 선판매 + 공개 빌드 (Build in Public) | Transistor.fm ($3,750/D5~14), Carrd ($1,900/D7~14) |
| **7~14일** | eBay 고가 물건 플리핑 | Steffensens ($2,600 profit/2w) |
| **30일+** | 어필리에이트/콘텐츠/SaaS 오가닉 성장 | 디지털 챌린지들 |
| **90일+** | 플랫폼 성장 (Amazon FBA 안정화) | Nikki Kirk |
| **180일+** | 마켓플레이스 성숙 | Zapier, Rover |

### 결론: 18일 이내 수익 가능성 순위 (55개 기준 업데이트)

1. **이벤트/컨퍼런스 현장 B2B 서비스** (D0~D1): 신규 진입 — CES Photography $5,800/5d가 증명
2. **직접 서비스 판매** (D0~D2): 기존 1위 유지, 신규 4개 사례로 재확인
3. **B2B 즉석 계약** (D1~D3): 단위당 수익 큼, 3개 신규 사례 추가
4. **물리적/이벤트 아비트라지** (D1~D7): Coachella $4,200/3d 등 신규 고수익 사례 추가
5. **노코드 디지털 제품** (D3~D7): NomadList, Bannerbear로 패턴 재확인
6. **Micro-SaaS 선판매** (D5~D14): 신규 진입 — Transistor.fm $3,750/14d 증명
7. **마켓플레이스 MVP** (D7~D18+): 검증은 가능, 본격 수익은 어려움

---

## 4. 기술 vs. 영업 비중 분석

| 전략 유형 | 기술 비중 | 영업 비중 | 단기 수익 속도 | 신규 확인 사례 |
|---------|---------|---------|------------|------------|
| 직접 서비스/아비트라지 | 0~10% | 90~100% | 매우 빠름 (D0~D3) | SXSW, CES, Coachella, Babson, BYU |
| 노코드 SaaS MVP | 10~30% | 70~90% | 빠름 (D1~D7) | WP Curve, NomadList |
| B2B 컨설팅/에이전시 | 20~40% | 60~80% | 빠름 (D3~D14) | Validately, Chingu |
| 마켓플레이스 | 40~60% | 40~60% | 중간 (D7~D30) | 정주영 배달팀 (D3 시작, 단 성장은 21일) |
| Micro-SaaS (커뮤니티 선판매) | 50~70% | 30~50% | **예외적 빠름** (D5~D14) | Transistor.fm, Carrd — 기존 오디언스가 핵심 |
| 기술 SaaS (코딩 필요, 오디언스 없음) | 70~90% | 10~30% | 느림 (D30+) | Zapier, Talkdesk |
| 딥테크/하드웨어 | 90~100% | 0~10% | 매우 느림 (D90+) | CoFlo Medical |

### 핵심 인사이트 (업데이트)
- **황금 공식 재확인**: 55개 분석에서도 "tech 0~30% + sales 70~100%" 조합이 D0~D7 수익에서 압도적 우위
- **새로운 예외 패턴**: tech 50~70%이더라도 **기존 커뮤니티/오디언스**가 있으면 D5~D14 수익 달성 가능 (Transistor.fm, WP Curve)
- **역설 심화**: 장기 성공 기업(Zapier, Talkdesk, Carrd)은 기술이 높지만, 단기 수익은 여전히 영업 중심 팀 압승

---

## 5. B2B vs. B2C 비교

| 기준 | B2B | B2C |
|------|-----|-----|
| 단위당 계약 금액 | 높음 ($500~$5,800+) | 낮음 ($5~$100) |
| 계약 속도 | 느림 (의사결정 복잡) | 빠름 (충동 구매 가능) |
| 18일 내 고객 수 | 적음 (1~20명) | 많음 (10~100명) |
| 총 매출 | B2B가 유리 (단위당) | B2C가 유리 (규모) |
| 팀 스킬 요구 | 영업 + 전문성 | 마케팅 + 제품 |
| 최고 단기 수익 사례 | CES Photography ($5,800/5d), TradeMingle ($4,000/48h), Validately ($3,000/3d) | Coachella MD ($4,200/3d), SXSW Rideshare ($2,800/5d) |
| 성공 핵심 | 의사결정권자 직접 접촉 + 포획 시장 | 정보 비대칭 + 이벤트 포획 시장 |

### 결론 (업데이트)
- **18일 이내 고수익 목표**: B2B 직접 영업이 여전히 유리 (단위당 최고 $5,800/5d — CES Photography)
- **B2C 새로운 가능성**: 트래픽/바이럴 없이도 "이벤트 포획 시장" 조건에서는 B2C 아비트라지가 D0~D3에 $4,000+ 달성 가능 (Coachella 사례)
- **공통 성공 조건**: B2B·B2C 모두 "포획된 고객(captive audience)"에게 접근할 때 속도와 수익이 극대화

---

## 6. 초기 자본의 영향 분석

| 초기 자본 | 사례 | 전략 특성 | 18일 내 매출 |
|---------|------|---------|-----------|
| $0 | Zapier, GroupMe, TradeMingle, Validately, WP Curve, NomadList, Transistor.fm | 서비스/디지털/아이디어/커뮤니티 판매 | 가능 (고영업력 또는 기존 오디언스 필요) |
| $1~$10 | Stanford 챌린지, Babson ($10), BYU ($1) | 창의적 서비스 아비트라지 | 즉각 가능 ($100~$1,270) |
| $100~$500 | Flea Market Flipper, SXSW Rideshare ($300), CES Photography ($400) | 서비스/아비트라지 | D0~D5 내 가능, ROI 700~1,400% |
| $1,000~$2,000 | Steffensens, Coachella ($1,500) | 물리적 아비트라지 (고가 단품) | 2주 내 가능, ROI 180~280% |
| $1,000~$5,000 | OA Challenge, Amazon FBA | 온라인 아비트라지 | 2~4주 내 |
| $50,000+ (지원금) | Lean LaunchPad (NSF) | 기술 스타트업 검증 | 수개월 |

### 핵심 인사이트 (업데이트)
- **소자본 최고 ROI**: BYU $1 Challenge ($1 → $870, ROI 87,000%), Stanford $5 발표시간 ($5 → $650, ROI 12,900%)
- **$300~$500 이벤트 서비스**: 신규 최적 구간 발견 — CES Photography ($400 → $5,800, ROI 1,350%), SXSW ($300 → $2,800, ROI 833%)
- **자본이 많다고 빠른 수익 보장되지 않음**: 원칙 유지. $0~$500에서 최고 ROI 다수 발생
- **이벤트 타겟 자본 투입**: $300~$500을 "이벤트 현장 서비스 세팅"에 쓰는 것이 새로운 고수익 패턴

---

## 7. 디지털 vs. 물리 전략 비교

| 기준 | 디지털 전략 | 물리 전략 |
|------|-----------|---------|
| 초기 설정 시간 | 빠름 (노코드 도구 활용) | 빠름 (즉각 실행 가능) |
| 확장성 | 높음 | 낮음 |
| 18일 내 첫 매출 | 가능 (B2B 계약 또는 노코드) | 가능 (아비트라지·현장 서비스) |
| 리스크 | 기술 구현 실패; 마케팅 비용 | 재고 리스크; 운반 필요 |
| 단기 최고 수익 사례 | Transistor.fm ($3,750/14d 선판매) | CES Photography ($5,800/5d) |
| 스케일업 가능성 | 높음 (Zapier, Carrd) | 낮음 (개인 사업 한계) |

### 신규 인사이트
- **물리 전략의 재평가**: CES Photography ($5,800/5d)와 Coachella MD ($4,200/3d)가 단기 수익 물리 전략의 상한선을 크게 높임
- **디지털 선판매 패턴 추가**: 코드가 없어도 "스프레드시트 → 유료 멤버십"(NomadList), "공개 빌드 → 선판매"(Transistor.fm)처럼 디지털 + 커뮤니티 조합이 D3~D14 수익 달성 가능

---

## 8. 심리적 요인 분석

단기 수익 창출 55개 사례에서 공통적으로 나타난 심리적 메커니즘:

### 8.1 긴급성 (Urgency) 활용
- **사례**: Stanford 레스토랑 예약 팀 → "지금 당장 45분 기다리기 싫다"
- **신규 확인**: Babson 이력서 검토 → "인턴 지원 마감 3일 전", WP Curve → "WordPress 지금 다운됨"
- **원리**: 즉각적 고통 해소에 사람들은 프리미엄 지불
- **적용**: 시간 압박이 있는 문제를 빠르게 해결하는 서비스

### 8.2 희소성 (Scarcity)
- **사례**: Stanford 발표 시간 판매 팀 → "이 3분의 청중은 다시 없다"
- **신규 확인**: Coachella MD → "매진 공식 굿즈는 더 이상 살 수 없음"
- **원리**: 한정된 자원의 희소성이 가격을 높임
- **적용**: 독점적 접근권, 한정판, 특정 시간대 예약

### 8.3 정보 비대칭 (Information Asymmetry)
- **사례**: 교재 아비트라지, 레스토랑 예약, 가전 플리핑
- **신규 확인**: Coachella ("Day 1에 뭐가 매진될지 안다"), NomadList ("어느 도시가 원격근무에 좋은지 안다")
- **원리**: 한쪽만 아는 정보의 차익 거래
- **적용**: 특정 시장/카테고리의 가격 정보 습득 후 거래

### 8.4 트렌드 서핑 (Trend Riding)
- **사례**: Foodspotting (음식 사진 소셜), Talkdesk (클라우드 전환), Docplix (헬스케어 디지털화)
- **신규 확인**: NomadList (원격근무 트렌드), WP Curve (WordPress 의존도 증가)
- **원리**: 이미 올라오는 파도에 올라타기
- **적용**: 시장이 이미 원하는 것을 빠르게 제공

### 8.5 기존 플랫폼 활용 (Platform Leverage)
- **사례**: GroupMe (Twilio), Talkdesk (Twilio), OA Challenge (Amazon FBA), Flea Market Flipper (eBay)
- **신규 확인**: Bannerbear (Hacker News), NomadList (Twitter 팔로워), Transistor.fm (팟캐스트 청중)
- **원리**: 이미 구축된 인프라/트래픽 위에 올라타기
- **적용**: 기존 플랫폼의 기능을 조합해 새로운 가치 창출

### 8.6 선판매 심리 (Pre-sell Psychology) ← 신규 추가
- **사례**: Transistor.fm (제품 없이 $3,750 선결제 수령), WP Curve (서비스 완성 전 구독 판매), KAIST 팀 (앱 완성 전 선판매)
- **원리**: "만들고 팔기"보다 "팔고 만들기"가 18일 내 수익을 보장. 고객이 먼저 돈을 내면 팀이 동기부여되고 시장 검증도 동시 완료
- **적용**: D+1에 랜딩페이지 + 결제 링크 먼저 열고, D+7부터 실제 서비스 제공

### 8.7 포획 시장 (Captive Market) ← 신규 추가
- **사례**: CES Photography (전시관 안에 갇힌 스타트업들), Babson/BYU (캠퍼스 포획), SXSW Rideshare (교통 수단 제한된 참가자), 정주영 배달팀 (캠퍼스 내 학생들)
- **원리**: 고객이 "다른 선택지가 없거나 매우 불편한" 공간에 모여있을 때, 마케팅 비용 없이 즉각 판매 가능
- **적용**: 서울대 캠퍼스, 특정 컨퍼런스, 특정 계절 이벤트 등 "모여있는 고객"을 먼저 찾고, 그곳에 필요한 서비스를 가져간다

---

## 9. 고수익 극단 사례 분석

### 9.1 단기(5일 이내) 최고 실제 수익 사례 (업데이트)

| 순위 | 사례 | 수익 | 기간 | 방법 |
|------|------|------|------|------|
| **1** | **CES Startup Photography** | **$5,800** | 5일 | B2B 현장 서비스 (이벤트 포획) |
| 2 | Coachella MD Arbitrage | $4,200 | 3일 | 매진 MD 아비트라지 |
| 3 | TradeMingle (Startup Weekend GC) | $4,000 AUD | 48시간 | B2B 즉석 계약 |
| 4 | SXSW Fixed-Price Rideshare | $2,800 | 5일 | 서지 가격 차익 서비스 |
| 5 | Validately (Startup Weekend) | $3,000 | 3일 | cold email B2B SaaS 판매 |
| 6 | GC Service Team | ~$900 | 3일 | 노코드 직접 판매 |
| 7 | Stanford $5 챌린지 (발표 시간) | $650 | 2시간 | 청중 주목권 판매 |

### 9.2 2주 이내 최고 실제 수익 사례 (업데이트)

| 순위 | 사례 | 수익 | 기간 | 방법 |
|------|------|------|------|------|
| **1** | **Transistor.fm 선판매** | **$3,750** | 14일 | 공개 빌드 + 얼리어답터 선결제 |
| 2 | Steffensens Range Flip | $2,600 (순이익) | 14일 | 가전 아비트라지 |
| 3 | Babson $10 Challenge | $1,270 | 14일 | 캠퍼스 이력서 검토 서비스 |
| 4 | OA Challenge 상위 참가자 | $1,000~$9,999 | 14일 | Amazon FBA 아비트라지 |
| 5 | Carrd (Indie Hacker) | $1,900 | 14일 | B2C SaaS Pro 플랜 전환 |

### 9.3 Micro-SaaS 빠른 유료화 사례 (신규 섹션)

| 순위 | 사례 | 수익 형태 | 달성 기간 | 방법 |
|------|------|---------|---------|------|
| 1 | Transistor.fm | $3,750 선판매 | D+5~14 | 기존 팟캐스트 오디언스에 Build in Public |
| 2 | WP Curve | MRR $1,116 (첫 달) | D+7 | WordPress 블로거 커뮤니티 직접 영업 |
| 3 | Carrd | $1,900 (2주) | D+7~14 | Product Hunt 론칭 + 무료 티어 바이럴 |
| 4 | Bannerbear | MRR $245 | D+3~7 | Hacker News Show HN 포스팅 1건 |
| 5 | NomadList | $566 (첫 주) | D+3 | 구글 스프레드시트 → 유료 멤버십 전환 |

### 9.4 투자 유치 기준 극단 사례

| 사례 | 투자액 | 기간 (최초 이벤트~투자) |
|------|--------|----------------------|
| Zaarly | $1M angel | 수주 |
| GroupMe | $850K seed | 수개월 |
| Docplix | $600K Pre-Series A | 수개월 |
| Talkdesk (500 Startups) | $50K | 수개월 |

---

## 10. 실패 및 저수익 사례 분석

### 저수익 패턴

| 사례 | 결과 | 실패 원인 |
|------|------|---------|
| YouTube 채널 챌린지 | 18일 내 수익 불가 | 오디언스 구축에 수개월 필요 |
| 30일 어필리에이트 챌린지 | 목표 미달 | 어필리에이트 지연 수익 구조 |
| Sana & Ribat $5/5일 | 소규모 | 5일은 제품+마케팅에 부족 |
| 딥테크 해커톤 팀들 | 주말 내 수익 0 | 기술 완성 자체가 어려움 |
| WunderWalk | 주말 내 수익 0 | 앱 완성에 6개월 추가 필요 |
| Bannerbear (비교) | MRR $245/7d (상대적 소규모) | 개발자 전용 시장이 작음 |

### 실패 공통 패턴

1. **기술 완성에 시간 소진**: 코딩이 전부인 팀은 판매 시간 없음
2. **지연 수익 모델 선택**: 어필리에이트, YouTube, 구독 오가닉 성장은 단기에 효과 없음
3. **고객 접촉 없음**: 만들고 기다리면 18일 안에 수익 0
4. **과도한 완성도 추구**: MVP가 아닌 완성품을 만들려다 시간 소진
5. **포획 시장 미선택**: 오픈 마켓에서 고객을 찾는 팀보다 이미 모여있는 고객에게 찾아간 팀이 우위 (55개 신규 확인)

---

## 11. 전략 유형 분류 체계 (Taxonomy) — 업데이트

```
단기 수익 창출 전략 (18일 이하)
│
├── A. 직접 서비스 판매 (Direct Service)
│   ├── A1. 오프라인 서비스 (Bike pump, 청소, 운반)
│   ├── A2. 온라인 프리랜싱/컨설팅 (Fiverr, Upwork)
│   └── A3. B2B 즉석 계약 (TradeMingle, Validately 방식)
│
├── B. 아비트라지/플리핑 (Arbitrage/Flipping)
│   ├── B1. 물리적 아비트라지 (벼룩시장→eBay)
│   ├── B2. 온라인 아비트라지 (Amazon FBA, OA)
│   ├── B3. 정보 아비트라지 (레스토랑 예약, 교재)
│   └── B4. 이벤트 아비트라지 (Coachella MD, 티켓 리셀)
│
├── C. 노코드/디지털 빠른 빌드 (No-Code MVP)
│   ├── C1. Typeform/Notion으로 서비스 판매
│   ├── C2. AI 도구로 디지털 제품 제작 (Gumroad)
│   └── C3. 기존 플랫폼 에이전시 (광고/콘텐츠 대행)
│
├── D. 이벤트/네트워크 활용 (Event Leverage)
│   ├── D1. 해커톤에서 투자자 직접 접촉
│   ├── D2. 대회 청중/심사위원 고객화
│   └── D3. 이벤트 연계 론칭 (SXSW 등)
│
├── E. 고위험 고수익 (High Risk / High Return)
│   ├── E1. SaaS MVP + 즉각 유료화 시도
│   ├── E2. 커스텀 물리 제품 (Cerealize 방식)
│   └── E3. 기업 B2B 솔루션 빠른 계약
│
├── F. Micro-SaaS 빠른 유료화 (신규) ← NEW
│   ├── F1. 공개 빌드 + 선판매 (Transistor.fm, WP Curve 방식)
│   ├── F2. 커뮤니티 레버리지 (기존 팔로워/오디언스 활용)
│   └── F3. 론칭 드라이브 (Hacker News Show HN, Product Hunt)
│
└── G. 포획 시장 서비스 (Captive Market Service) (신규) ← NEW
    ├── G1. 컨퍼런스/이벤트 현장 B2B 서비스 (CES Photography 방식)
    ├── G2. 캠퍼스 내 직접 서비스 (Babson, BYU, 정주영 배달팀 방식)
    └── G3. 이벤트 서지 아비트라지 (SXSW 고정가 라이드 방식)
```

---

## 12. 최종 결론: 3주 이하에서 역사적으로 가장 효과적인 수익 창출 방식

### 데이터 기반 순위 (55개 전체 기준, 확실성 × 수익 × 속도)

| 순위 | 전략 | 예상 18일 수익 | 속도 | 적합한 팀 역량 | 변동 |
|------|------|--------------|------|-------------|------|
| **#1** | **이벤트/컨퍼런스 현장 B2B 서비스** | $3,000~$8,000 | D0~D2 | 전문 스킬 + 현장 영업 | ▲ 신규 진입 |
| **#2** | **B2B 즉석 계약 + 노코드 MVP** | $1,000~$10,000 | D1~D3 | 영업, 문제 식별 | — 유지 |
| **#3** | **직접 서비스 판매 (오프라인/온라인)** | $500~$5,000 | D0~D2 | 영업력, 네트워크 | — 유지 |
| **#4** | **물리적/이벤트 아비트라지** | $500~$5,000 | D1~D7 | 시장 지식, 타이밍 | ▲ 상한선 상승 |
| **#5** | **Micro-SaaS 선판매 (커뮤니티 기반)** | $1,000~$5,000 | D3~D14 | 기존 오디언스, 제품 개발 | ▲ 신규 진입 |
| **#6** | **정보 아비트라지 (예약/교재/티켓)** | $200~$2,000 | D1~D7 | 정보 수집, 타이밍 | — 유지 |
| **#7** | **Amazon FBA 온라인 아비트라지** | $500~$5,000 | D7~D18 | 소싱, 분석력 | — 유지 |
| **#8** | **AI 도구 디지털 제품 + 직접 판매** | $100~$1,000 | D3~D14 | 마케팅, 제작 | — 유지 |
| **#9** | **마켓플레이스 MVP + 중개 시작** | $0~$500 | D7~D18+ | 기술, 네트워크 | — 유지 |

---

### 핵심 결론 (55개 사례 기반 업데이트)

> **"단기 수익 극대화의 황금 공식은 '영업 90% + 기술 10%'이다. 단, 포획 시장을 먼저 선택하라."**

55개 사례 분석에서 도출된 18일 이내 수익 달성의 공통 원칙:

**1. 만들기보다 팔기 먼저 (Sales Before Build)**
- 최고 단기 수익 사례들은 제품 완성이 아닌 고객 계약이 우선이었다
- TradeMingle: 프로토타입으로 $4,000 계약 체결
- Transistor.fm: 제품 없이 $3,750 선결제 수령 ← 신규 확인

**2. 포획 시장을 먼저 선택하라 (Captive Market First)** ← 신규 추가
- CES Photography: 전시관 안의 스타트업들 ($5,800/5d)
- Babson/BYU: 캠퍼스 학생들 ($870~$1,270/7~14d)
- 정주영 배달팀: 교내 학생들 (KRW 180만원/21d)
- 원칙: 마케팅 비용 0원. "모여있는 고객"에게 필요한 것을 가져가면 D0에 첫 매출 가능

**3. 기존 플랫폼 위에 올라타기 (Platform Leverage)**
- GroupMe (Twilio), Talkdesk (Twilio), OA Challenge (Amazon), Flea Market (eBay)
- 신규 확인: Bannerbear (Hacker News), NomadList (Twitter), Transistor.fm (팟캐스트 오디언스)
- 18일 내에 플랫폼을 직접 구축할 수 없다 → 이미 있는 플랫폼을 도구로 활용

**4. 단위당 수익을 높이기 (High Ticket)**
- B2C 소규모 거래 ($5~50)보다 B2B 대형 계약 ($500~$5,000)이 18일 내 총수익에서 우위
- 신규 확인: CES Photography 세션당 $200~$500, Transistor.fm 건당 $150

**5. 정보 비대칭을 찾기 (Asymmetric Information)**
- 아비트라지의 공통 원리: 한쪽은 모르는 가격 차이를 이용
- 신규 확인: Coachella ("Day 1 이후 매진 굿즈"), NomadList ("어느 도시가 원격근무에 좋은지")
- 18일 안에 구축할 수 있는 가장 강력한 "제품"은 정보

**6. 피드백 루프를 하루 단위로 돌리기 (Daily Feedback Loops)**
- 성공한 팀들은 주간이 아닌 일간 단위로 가설을 검증하고 피벗했다
- Lean LaunchPad 원칙을 18일로 압축: 매일 고객 접촉 → 매일 피벗

---

### 5명 팀, 18일 최적 전략 조합 (55개 사례 기반 추천)

> ⚠️ 이하는 패턴 분석에서 나온 관찰이며, 전략 추천이 아닌 데이터 요약입니다.

역사적 사례에서 18일 이내 가장 높은 수익을 낸 팀들의 공통 구조:

```
역할 분배 (5명 팀 기준):
- 영업/고객 접촉: 2명 → 매일 B2B 미팅 또는 포획 시장 직접 판매
- 제품/서비스 실행: 2명 → 노코드 도구 or 아비트라지 실행 or 현장 서비스
- 분석/피벗: 1명 → 매일 데이터 정리, 다음날 방향 결정

수익 발생 일정 (역사적 평균, 55개 기준):
- D0~D2: 첫 소규모 수익 (포획 시장 서비스 or 직접 판매)
- D3~D7: 수익 모델 검증 및 첫 스케일업 시도
- D8~D14: 가장 반응 좋은 채널에 리소스 집중
- D15~D18: 최적 채널 집중 + 총수익 극대화
```

---

## 부록: 신뢰도 분포 (업데이트)

| Confidence | 사례 수 | 비율 | 변동 |
|-----------|---------|------|------|
| HIGH | 32 | 58.2% | ▲+9 |
| MEDIUM | 20 | 36.4% | ▲+6 |
| LOW | 3 | 5.5% | — |

> HIGH: 복수 직접 출처 확인 (저서, 공식 블로그, 복수 기사)
> MEDIUM: 복수 간접 출처 (기사, 블로그, 커뮤니티 게시물)
> LOW: 단일 간접 출처 또는 세부 미확인

---

## 참고 자료

- [Startup Weekend Success Stories](https://up-rev.com/10-startup-weekend-success-stories/)
- [Techstars Blog - Rover.com](https://www.techstars.com/blog/advice/from-techstars-startup-weekend-to-usd970-million-valuation-rover)
- [SaaStr - Talkdesk Hackathon to Unicorn](https://www.saastr.com/hackathon-to-unicorn-talkdesk-co-founder/)
- [Inc.com - 5 Companies in 3 Days](https://www.inc.com/articles/201111/companies-that-launched-in-three-days-startup-weekend.html)
- [TechCrunch - GroupMe Disrupt Story](https://techcrunch.com/2012/05/11/from-disrupt-ny-to-a-43-million-skype-acquisition-groupme-tells-all/)
- [Next Big Idea Club - Stanford $5 Challenge](https://nextbigideaclub.com/magazine/stanford-students-turned-5-650-just-2-hours/20016/)
- [Gold Coast Innovation Hub](https://www.gchub.com.au/gold-coast-global-startup-weekend-winners-announced/)
- [Online Selling Experiment - Flipping](https://onlinesellingexperiment.com/flipping-challenge-recap/)
- [Flea Market Flipper Challenge](https://fleamarketflipper.com/challenge-update/)
- [MIT $100K Competition](https://news.mit.edu/2025/drug-injection-device-wins-mit-100k-competition-0514)
- [Rice Business Plan Competition](https://rbpc.rice.edu/about)
- [StartupBus Wikipedia](https://en.wikipedia.org/wiki/StartupBus)
- [Lean LaunchPad Wikipedia](https://en.wikipedia.org/wiki/Lean_Launchpad)
- [AngelHack Case Studies](https://angelhack.com/case-studies/)
- [OA Challenge](https://pro.onlinesellingexperiment.com/p/challenge)
- [WP Curve - 7 Day Startup](https://wpcurve.com/7-day-startup/)
- [NomadList - Pieter Levels](https://levels.io/product-hunt-hacker-news-number-one/)
- [Carrd About](https://carrd.co/about)
- [Babson College Entrepreneurship Challenge](https://entrepreneurship.babson.edu/babson-college-challenge)
- [BYU Rollins Center](https://marriott.byu.edu/rollins/entrepreneurship)
- [Bannerbear Blog](https://www.bannerbear.com/blog/how-i-built-bannerbear/)
- [Transistor.fm - First 100 Customers](https://saas.transistor.fm/articles/how-we-got-our-first-100-customers)
- [현대 정주영 창업경진대회](https://startup.hyundai.com/ko/competition)
- [KAIST 창업원](https://startup.kaist.ac.kr/hackathon)
- [CES Startups & Entrepreneurs](https://www.ces.tech/Topics/Startups-and-Entrepreneurs.aspx)
