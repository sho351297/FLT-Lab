# 비행실습 Workspace README

이 폴더의 목표는 흩어진 학습 체크리스트와 과제 아웃라인을 최대한 활용해, 최종 제출물까지 바로 제작할 수 있는 작업 공간으로 만드는 것이다.

현재 자료는 크게 두 갈래다.

- `비행실습5`: IFR Oral / 계기비행증명 실기시험표준서 기반 학습 로드맵
- `비행실습6`: Jeppesen chart 분석 + KWA -> RKJB ILS/VOR 접근 시나리오 PPT 제작 로드맵

---

## 폴더 구조

```text
비행실습/
├── README.md
├── 비행실습5/
│   └── # 비행실습 5 과제 마스터 로드맵.md
└── 비행실습6/
    ├── 비행실습 6 과제 마스터 로드맵.md
    └── # 비행실습 6 PPT 아웃라인.md
```

---

## 최종 산출물 목표

### 비행실습 5

최종 목표는 IFR 구술시험 또는 계기비행 실기시험 대비 자료를 완성하는 것이다.

완성 상태:

- IFR 기본 개념을 말로 설명할 수 있음
- 항법시설, 계기, 기상, ATC, holding, approach, emergency 절차를 연결해서 설명할 수 있음
- 예상 구술 질문에 `개념 -> 이유 -> 절차 -> 실제 운용 -> 안전요소` 순서로 답변할 수 있음
- 실기 기준치와 불합격 조건을 암기함

추천 최종 결과물:

- `비행실습5/IFR Oral 답변집.md`
- `비행실습5/IFR 실기시험 체크리스트.md`
- `비행실습5/예상 구술질문 Q&A.md`

### 비행실습 6

최종 목표는 Jeppesen 계기접근차트 분석과 KWA -> RKJB 접근 시나리오를 발표 가능한 PPT로 완성하는 것이다.

완성 상태:

- Jeppesen chart 구조와 핵심 기호를 설명할 수 있음
- RKJB ILS 접근과 VOR 접근을 실제 briefing처럼 설명할 수 있음
- ILS와 VOR의 차이를 precision / nonprecision 관점에서 비교할 수 있음
- Missed approach 절차와 ATC phraseology를 포함함

추천 최종 결과물:

- `비행실습6/비행실습 6 최종 PPT.pptx`
- `비행실습6/비행실습 6 발표 대본.md`
- `비행실습6/RKJB 접근 차트 분석.md`
- `비행실습6/KWA-RKJB ILS 접근 시나리오.md`
- `비행실습6/KWA-RKJB VOR 접근 시나리오.md`

---

## 작업 우선순위

### 1. 원본 자료 확보

최종 제출물을 만들기 전에 아래 자료가 필요하다.

- RKJB 무안공항 Jeppesen ILS approach chart
- RKJB 무안공항 Jeppesen VOR approach chart
- KWA 광주 VOR 정보
- 과제 제출 형식: PPT, 문서, 발표 여부, 분량 제한
- 이름, 학번, 과목명, 제출일

### 2. 사실값 추출

차트에서 아래 값을 먼저 뽑아 별도 문서에 정리한다.

- 활주로 번호
- Localizer frequency
- VOR frequency
- Final approach course
- FAF
- MAP
- DA/DH 또는 MDA
- MSA
- Missed approach procedure
- Approach lighting
- Communication frequencies

주의: 이 값들은 추정하지 말고 실제 차트 기준으로 입력해야 한다.

### 3. 접근 시나리오 작성

ILS와 VOR를 각각 별도 흐름으로 작성한다.

ILS 기본 흐름:

```text
KWA departure
-> ATC radar vectors or transition
-> Localizer intercept
-> Glide slope intercept
-> FAF crossing
-> Final approach
-> DH
-> Landing or missed approach
```

VOR 기본 흐름:

```text
KWA departure
-> VOR radial/course intercept
-> FAF crossing
-> Descend to MDA
-> Maintain MDA
-> MAP
-> Landing or missed approach
```

### 4. PPT 제작

`비행실습6/# 비행실습 6 PPT 아웃라인.md`를 기준으로 만든다.

권장 슬라이드 구성:

1. Title
2. Objective
3. Jeppesen Chart Overview
4. Jeppesen Chart Structure
5. Important Symbols
6. ILS Approach Basics
7. RKJB ILS Approach Overview
8. KWA -> RKJB ILS Scenario
9. ILS Final Segment and Missed Approach
10. VOR Approach Basics
11. RKJB VOR Approach Overview
12. KWA -> RKJB VOR Scenario
13. VOR Final Segment and Missed Approach
14. ILS vs VOR Comparison
15. Conclusion

### 5. 발표 대본 작성

각 슬라이드마다 30~60초 분량의 설명을 만든다.

대본은 단순 번역이 아니라 조종사 briefing처럼 작성한다.

좋은 설명 순서:

```text
차트 정보 확인
-> 접근 방식 설명
-> 조종사가 해야 할 조작
-> 고도/방위/주파수 확인
-> minimum 도달 시 판단
-> missed approach 대비
```

---

## 품질 체크리스트

최종 제출 전 아래 항목을 확인한다.

- [ ] 활주로 번호가 모든 문서와 PPT에서 일치함
- [ ] ILS frequency와 VOR frequency가 정확함
- [ ] Final approach course가 정확함
- [ ] FAF와 MAP를 혼동하지 않음
- [ ] DH/DA와 MDA를 혼동하지 않음
- [ ] ILS는 precision approach로 설명함
- [ ] VOR는 nonprecision approach로 설명함
- [ ] Missed approach 절차를 별도 슬라이드 또는 대본에 포함함
- [ ] 차트 캡처에 fix, course, minimum, missed approach가 표시됨
- [ ] 발표자가 차트를 보지 않고 전체 흐름을 설명할 수 있음

---

## 다음에 만들면 좋은 파일

```text
비행실습6/
├── 자료/
│   ├── RKJB_ILS_chart.pdf
│   ├── RKJB_VOR_chart.pdf
│   └── chart_screenshots/
├── RKJB 접근 차트 분석.md
├── KWA-RKJB ILS 접근 시나리오.md
├── KWA-RKJB VOR 접근 시나리오.md
├── 비행실습 6 발표 대본.md
└── 비행실습 6 최종 PPT.pptx
```

---

## 현재 기준 가장 중요한 다음 작업

1. RKJB ILS/VOR 실제 차트를 확보한다.
2. 차트에서 frequency, course, FAF, MAP, minimums, missed approach를 추출한다.
3. `비행실습6/# 비행실습 6 PPT 아웃라인.md`의 빈칸을 실제 차트 값으로 채운다.
4. ILS와 VOR 시나리오를 각각 독립 문서로 작성한다.
5. 시나리오와 차트 캡처를 사용해 최종 PPT를 만든다.
