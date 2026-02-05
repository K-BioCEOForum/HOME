# Korea Biotech CEO Forum 2026

## 프로젝트 개요

Korea Biotech CEO Forum 2026은 대한민국 바이오테크 산업의 리더들이 모이는 프리미엄 포럼을 위한 공식 웹사이트입니다. "Designing the Next Corporate Reality in the Age of Uncertainty"를 주제로, CEO들의 고독한 의사결정, 인재 확보, 자본 조달, 불확실성 관리 등 핵심 이슈를 다룹니다.

## 주요 정보

- **일시**: 2026년 2월 27일 - 3월 1일
- **장소**: 비오토피아 · 디아넥스호텔, 제주
- **참가자**: 30+ 소수정예 CEO
- **세션**: 6가지 핵심 세션

## 완료된 기능

### ✅ 1. 히어로 섹션
- **어두운 그라데이션 배경**: 텍스트 가독성 극대화
- **동적 네트워크 애니메이션**: 
  - Canvas 기반 인터랙티브 배경
  - 연결선 밀도 20% 감소 (모바일 최적화)
  - 브라운 운동 노드 30% (역동적 효과)
- **KBCF 로고**: 배경 없는 로고 적용
- **주제**: "Lonely Decisions by CEOs: People, Capital and Managing Uncertainty"
- **부제**: "Designing the Next Corporate Reality in the Age of Uncertainty"
- **일시/장소**: 2026년 2월27일-3월1일, 비오토피아 · 디아넥스호텔
- **여백 최적화**: 
  - min-height 85vh
  - 상단 여백: 8rem (128px)
  - 하단 여백: 5rem (80px)
  - 상단이 더 넓어 로고/햄버거 메뉴와 충분한 거리 확보

### ✅ 2. 네비게이션
- **햄버거 메뉴**: 
  - 오른쪽 상단 삼선 아이콘 (#85AC0D 틸그린)
  - 두꺼운 라인 (h-1, 4px)
  - 발광 효과 (box-shadow)
- **사이드 드로어 메뉴**:
  - 왼쪽에서 슬라이드 인/아웃
  - 배경색: #0F6B7E (틸 청록)
  - 너비: 320px (w-80) - 이메일 주소가 잘 보이도록 확장
  - **헤더**: 닫기 버튼만 표시 (오른쪽 정렬)
  - 메뉴 항목: 소개, 주요 주제 (상세 프로그램), 일정, 장소 (오시는 길, Dining & Networking, 숙소 안내, 셔틀 안내)
  - **세련된 스크롤바**:
    - 폭: 6px (얇은 디자인)
    - 트랙: 반투명 흰색 (rgba 0.05)
    - 썸: 반투명 흰색 (rgba 0.2)
    - 호버: 반투명 흰색 (rgba 0.3)
    - Firefox 지원 (scrollbar-width: thin)
  - **Contact 섹션** (하단 고정):
    - 스크롤 영역 외부에 고정 배치
    - 상단 구분선 디자인 (border-t border-white/20)
    - 박스 제거, 구분선만으로 경계 표현
    - 이메일 아이콘 + koreabiotechceoforum@gmail.com
    - 전화 아이콘 + +82 10 2079 8754
    - 이메일: word-break로 자연스러운 줄바꿈
    - 폰트 크기: 0.8rem (가독성 향상)
    - 항상 하단에 표시되어 접근성 향상
- **부드러운 애니메이션**: 0.3s transition

### ✅ 3. 포럼 소개 섹션
- 포럼의 목적과 비전 소개
- 주요 특징 카드 (2단 레이아웃)
- **통계 카드 제거**: 30+, 1일, 5+ 삭제
- 깔끔하고 전문적인 디자인
- 여백 최적화: py-12

### ✅ 4. 채텀하우스 룰 섹션
**제목**: 
- "포럼 운영 원칙: 채텀하우스 룰"
- "(Chatham House Rule)" - 영문 부제

**배경**: 틸 그라데이션 (#2C7A5F → #1a4d3d)

**구조**:
- **메인 설명**: 채텀하우스 룰 적용 안내
  - **아이콘 제거** ✓
  - 텍스트만 표시 (왼쪽 정렬)
  - **모바일 줄바꿈**:
    - "본 포럼은" 다음 줄바꿈 (sm:hidden)
    - "논의 내용은 외부 공유 가능," 다음 줄바꿈 (sm:hidden)
  - 반투명 카드 (bg-white/10, backdrop-blur)
  - 패딩: p-6
  - 하단 여백: mb-4
  - 제목 크기: text-lg
  - 본문 크기: text-base
  
- **핵심 원칙 (2열 그리드)**:
  - **레이아웃**: 아이콘과 제목이 가로로 나란히 (flex items-start gap-3)
  - 아이콘과 제목: 상단에 함께 배치 (mb-3)
  - 본문: 아이콘과 제목 아래 전체 너비
  - 아이콘 크기: w-6 h-6
  - 제목 크기: text-base
  - ✅ **자유로운 활용**: 정보·아이디어·인사이트 공유 가능 (아이콘: #85D4C4)
  - ❌ **엄격한 금지**: 녹음/녹화/실시간 송출 금지 (아이콘: #FF6B6B)
  
- **목적**:
  - **레이아웃**: 아이콘과 제목이 가로로 나란히 (flex items-start gap-3)
  - 아이콘과 제목: 상단에 함께 배치 (mb-3)
  - 본문: 아이콘과 제목 아래 전체 너비
  - 아이콘 크기: w-6 h-6
  - 아이콘 색상: #85D4C4
  - 제목 크기: text-base
  - 본문 크기: text-sm
  - 부가 설명: text-xs

**디자인 요소**:
- **메인 제목**: 
  - 크기: clamp(1.75rem, 4vw, 3rem)
  - 색상: text-white
  - 하단 여백: mb-2
  - 줄 높이: 1.4
  - **모바일 줄바꿈**: "포럼 운영 원칙:" 다음 줄바꿈 (sm:hidden)
- **영문 부제**:
  - 크기: text-xl
  - 색상: text-white/80
  - 하단 여백: mb-6
- 흰색 텍스트 (text-white, text-white/90, text-white/80)
- 반투명 카드 테두리: border-white/20
- 아이콘: 체크마크(#85D4C4), 금지(#FF6B6B), 눈(#85D4C4)
- 여백: py-12

### ✅ 5. 주요 주제 섹션
- **부제**: "3가지 핵심 주제를 확장한 6가지 세션"
  - 반응형 폰트: clamp(0.95rem, 2vw, 1.1rem)
  - 색상: #2C7A5F (틸 그린)
  - 굵기: font-semibold
  - 하단 여백: mb-16
- **3가지 핵심 주제 카드**:
  - **People**: 핵심 인재 확보와 조직 문화
  - **Capital**: 투자 유치와 재무 관리
  - **Managing Uncertainty**: 불확실성 속 의사결정
- 호버 효과가 있는 인터랙티브 카드
- 상단 아이콘 (Teal 그라데이션)
- 카드 상단 패딩: pt-20
- 그리드 상단 마진: mt-16
- 여백 최적화: py-12 pt-20

### ✅ 6. 일정 섹션
**2열 그리드 레이아웃**: Day 1과 Day 2가 나란히 표시 (데스크톱)

**Day 1 - 2월 27일 (금)** - 비오토피아 · 메인홀 · W22:
- 15:30-16:00: Registration (비오토피아 입구)
- 15:30-16:30: Welcome Reception (연회장 포이어, Standing)
- 16:40-16:50: Opening Remarks (메인홀)
- 16:50-17:15: Keynote Address (이동훈 SK 바이오팜 대표)
- 17:15-17:40: Fireside Chat (존림 삼성바이오로직스 대표)
- 17:40-18:30: Member Introduction (참석자 소개)
- 18:30-20:00: Gala Dinner (코스 디너)
- 20:00-22:00: Networking Night (W22, 타운하우스)

**Day 2 - 2월 28일 (토)** - 디아넥스호텔 컨퍼런스룸 · 포도호텔 · W22:
- 07:30-08:50: Breakfast 조식 (디아넥스호텔 레스토랑, Buffet)
- 08:50-09:00: Opening Remarks (Agenda & Flow 소개)
- 09:00-09:30: FEATURED TALK - License & Licensibility (윤태영 오스코텍 대표)
- 09:30-10:10: SESSION 1 - 재무적 생존 전략
- 10:10-10:30: Morning Coffee Break
- 10:30-11:10: SESSION 2A - 전략적 딜-메이킹 I: Asset Deal
- 11:10-11:40: SESSION 2B - 전략적 딜-메이킹 II: Platform Deal
- 11:40-12:50: Networking Luncheon (at The Annex Restaurant · 중식)
- 12:50-13:10: R&D TALK - R&D Portfolio (최영기 유한양행 연구소장)
- 13:10-13:40: SESSION 3 - What to keep within company and what to outsource?
- 13:40-14:30: SESSION 4 - Macro View on AI
- 14:30-15:00: Afternoon Refresh
- 15:00-15:40: SESSION 5 - Resilient Leadership
- 15:40-16:30: SESSION 6 - Human Capital & Org Redesign
- 16:30-16:50: SPECIAL TALK - 한국 바이오의 미래 로드맵 (이병건 특별고문)
- 16:50-17:20: Discussion (자유 토론)
- 17:20-17:30: Closing Remarks (The Next Chapter)
- 18:00-20:00: Dinner (포도호텔 레스토랑, 담코스/오름코스)
- 20:00-22:00: Post-Event Gathering (W22 타운하우스, Casual Gathering)

**Day 3 - 3월 1일 (일)** - 디아넥스호텔 레스토랑:
- 07:30-09:30: Breakfast 조식 (디아넥스호텔 레스토랑, Buffet)

여백 최적화: py-12

### ✅ 7. 장소 정보 섹션
- **디아넥스 컨퍼런스룸**:
  - Hero 그라데이션 배경
  - 주소 및 연락처 정보 (2열 그리드)
  - **아이콘 및 레이아웃**:
    - 아이콘 크기: w-5 h-5 (20px)
    - 아이콘 색상: #85D4C4 (인트로 달력 색상)
    - 정렬: items-center (수직 중앙 정렬)
    - 간격: gap-3
  - **텍스트 스타일**:
    - 크기: text-base (16px)
    - 투명도: opacity-90
    - 호버: opacity-100 + underline
  - "주소", "문의" 라벨 제거
  - Google Maps 링크 및 tel: 링크
- 프리미엄 시설 이미지 (conference-room.jpg)
- 여백 최적화: py-12

### ✅ 8. 오시는 길 섹션
- **비오토피아**: 
  - **제목**: 비오토피아 (틸 그린 #85AC0D, 아이콘 제거)
  - **주소**: 📍 위치 아이콘 (#85AC0D) + 제주 서귀포시 안덕면 산록남로 863-24 (Google Maps 링크)
  - **전화**: 📞 전화 아이콘 (#85AC0D) + 064-794-0888 (클릭 시 전화 연결)
  - 아이콘 색상이 호텔명 색상과 매칭
  - 주요 행사: 2월 27일(금) 등록, 웰컴 리셉션, 공식 만찬
- **디아넥스호텔**:
  - **제목**: 디아넥스호텔 (틸 그린 #2C7A5F, 아이콘 제거)
  - **주소**: 📍 위치 아이콘 (#2C7A5F) + 제주 서귀포시 안덕면 산록남로762번길 71 (Google Maps 링크)
  - **전화**: 📞 전화 아이콘 (#2C7A5F) + 064-793-6005 (클릭 시 전화 연결)
  - 아이콘 색상이 호텔명 색상과 매칭
  - 주요 행사: 2월 28일(토) 포럼 세션, 조식, 중식
- **깔끔한 디자인**:
  - 제목에서 위치 아이콘 제거
  - 위치 아이콘을 주소 앞으로 이동
  - 각 카드의 아이콘 색상이 제목 색상과 일치
  - 아이콘 크기: w-4 h-4
  - tel: 링크로 원클릭 전화 연결
- 여백 최적화: py-12

### ✅ 9. 모달 (Modals)
**Dining & Networking Events**:
- **2열 레이아웃**: 데스크톱에서 Day 1, Day 2가 나란히 표시
- Day 1 이벤트 (2월 27일): Registration, Welcome Reception, Gala Dinner, Networking Night
- Day 2 이벤트 (2월 28일): Breakfast, Luncheon Networking, Dinner, Post-Event Gathering
- 특별 식단 안내 및 공지사항 포함

**Accommodation (숙소 안내)**:
- **숙소 배정 안내**:
  - **느낌표 아이콘 제거** ✓
  - 깔끔한 텍스트 블록
  - 폰트: text-xs
  - 여백 최소화
  - <br> 태그로 줄바꿈 정리
- **Official Accommodation**:
  - 여백 축소: p-8 → p-5
  - 제목 축소: text-xl → text-lg
  - 호텔명 축소: text-lg → text-base
  - 항목 간격: space-y-6 → space-y-5
  - **"위치", "문의" 라벨 제거**:
    - 위치 아이콘 (📍) + 주소 (Google Maps 링크)
    - 전화 아이콘 (📞) + 전화번호 (tel: 링크)
  - **Google Maps 링크**:
    - 디아넥스호텔: 제주 서귀포시 안덕면 산록남로762번길 71
    - 포도호텔: 제주 서귀포시 안덕면 산록남로 863
    - 타운하우스: 제주 서귀포시 안덕면 산록남로762번길 79
  - **아이콘 색상**: #85D4C4 (인트로 달력 색상) ✓
    - 위치 아이콘: #85D4C4
    - 전화 아이콘: #85D4C4
    - 통일된 밝은 틸 색상으로 시각적 일관성
  - 아이콘 크기: w-4 h-4
  - 간격: space-y-2 → space-y-1.5
  - 깔끔하고 답답하지 않은 레이아웃
- **안내사항**:
  - 제목 하단 여백: mb-2 → mb-3
  - 불릿 포인트 간격: gap-2 → gap-3
  - 숙소 배정 안내
  - 셔틀 버스 운행 안내
- ~~Contact: koreabiotechceoforum@gmail.com~~ (제거)

### ✅ 9. 푸터
- 중앙 정렬 레이아웃
- **대형 로고**: 
  - 크기: h-24 sm:h-28 md:h-32 lg:h-36
  - 반응형 크기 조정 (모바일 → 데스크톱)
- **입체감 효과**:
  - 다층 그림자 (drop-shadow)
  - 0 10px 20px, 0 6px 12px, 0 15px 30px
  - 3D 변환 최적화 (translateZ)
- Copyright 정보
- Hero 그라데이션 배경
- **간결한 디자인**: Quick Links와 Contact 섹션 제거
- 여백 증가: py-12

## 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: 그라데이션, 애니메이션, 반응형 디자인
- **Tailwind CSS**: 유틸리티 기반 스타일링
- **JavaScript**: 
  - Canvas API 네트워크 애니메이션 (브라운 운동 지원)
  - 스크롤 이벤트 처리
  - 모달 관리 (Meal, Accommodation)
  - 햄버거 메뉴 토글
  - 부드러운 내비게이션
- **Google Fonts**: Noto Sans KR (300-900)

## 파일 구조

```
/
├── index.html                      # 메인 페이지
├── program.html                    # 상세 프로그램 페이지
├── shuttle-schedule-mobile.html    # 셔틀 안내 페이지
├── images/
│   ├── logo-nobg.png              # 배경 없는 메인 로고
│   └── conference-room.jpg         # 컨퍼런스룸 이미지
└── README.md                       # 프로젝트 문서
```

## 컬러 팔레트

### 주요 색상
- **Hero 배경**: Dark teal-blue 그라데이션 (rgba 투명도 0.95)
  - `rgba(25, 60, 45, 0.95)` → `rgba(30, 70, 100, 0.95)` → `rgba(50, 90, 30, 0.95)`
- **햄버거 메뉴**: `#85AC0D` (틸 그린)
- **사이드 메뉴 배경**: `#0F6B7E` (틸 청록)
- **Teal 그라데이션**: `#2C7A5F` → `#3A6BA3`
- **부제 강조**: `#2C7A5F` (틸 그린)
- **강조 아이콘**: `#85D4C4` (밝은 Teal)
- **텍스트**: 화이트, 다크 그레이 (#1A1A1A), 미디엄 그레이 (#666666)
- **배경**: #F8F6F1 (밝은 베이지), 화이트

### 제거된 색상
- ~~골드 그라데이션 (#FFF44F → #E6C300)~~
- ~~노란색 강조 (#FFD700, #FFC107 등)~~

## 반응형 디자인

- **모바일 우선** 접근 방식
- Tailwind CSS 브레이크포인트 활용 (sm, md, lg)
- 유연한 그리드 레이아웃 (일정, Dining 모달: 2열)
- `clamp()` 함수로 반응형 타이포그래피
- 햄버거 메뉴: 모든 화면 크기에서 표시
- 사이드 드로어: 288px 폭

## 애니메이션 효과

- **네트워크 애니메이션**: 
  - Canvas 기반 동적 노드 연결
  - 40개 노드 (30% 브라운 운동)
  - 연결 거리: 200px
  - 랜덤 필터: 80% (연결선 밀도 감소)
  - 색상: 밝은 틸 톤 (rgba(255, 244, 79, ...))
- **Fade-in-up**: 페이지 로드 시 순차적 등장
- **호버 효과**: 테마 카드 상승 효과, 메뉴 항목 배경 변화
- **사이드 메뉴**: translateX 슬라이드 (0.3s)
- **텍스트 그림자**: 가독성 향상

## 브라우저 지원

- Chrome (최신 버전)
- Firefox (최신 버전)
- Safari (최신 버전)
- Edge (최신 버전)
- 모바일 브라우저 (iOS Safari, Chrome Mobile)

## 향후 개발 권장사항

1. **스피커/세션 상세 페이지**
   - 각 세션별 상세 정보 및 발표자 프로필
   - 모달 또는 별도 페이지로 구현

2. **다국어 지원**
   - 영어 버전 추가
   - i18n 라이브러리 통합

3. **인터랙티브 맵**
   - 제주도 비오토피아·디아넥스호텔 위치 지도
   - Google Maps 또는 Naver Maps API 연동

4. **소셜 미디어 통합**
   - SNS 공유 버튼
   - 실시간 해시태그 피드

5. **참가 신청 기능** (필요 시)
   - 백엔드 API 연동
   - 결제 시스템 통합

## 접근성 (Accessibility)

### 현재 구현
- 시맨틱 HTML 구조
- Alt 텍스트 (이미지)
- 충분한 색상 대비
- 키보드 내비게이션 (햄버거 메뉴)

### 개선 필요
- ARIA 레이블 추가
- 스크린 리더 지원 강화
- 포커스 상태 시각화 개선

## 라이선스

© 2026 Korea Biotech CEO Forum. All rights reserved.

## 문의

- **Email**: koreabiotechceoforum@gmail.com

---

**마지막 업데이트**: 2026-02-01  
**버전**: 6.4 (상세 프로그램 업데이트 및 Day 3 표기 수정)
