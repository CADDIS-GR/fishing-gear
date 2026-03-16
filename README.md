# 🎣 플라이 타잉 소품 및 장비 아카이브

> 관리형낚시터(저수지)에서의 플라이 낚시를 위한 타잉 소품과 장비 리뷰 모음

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-success)](https://caddis-gr.github.io/fishing-gear/)
[![HTML](https://img.shields.io/badge/HTML-100%25-orange)](https://github.com/CADDIS-GR/fishing-gear)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

## 📋 프로젝트 소개

플라이 낚시를 사랑하는 낚시인을 위한 타잉 소품 및 장비 리뷰 아카이브입니다. 실제 사용 경험을 바탕으로 한 상세한 리뷰와 팁을 제공합니다.

### 🌐 웹사이트 보기
**👉 [https://caddis-gr.github.io/fishing-gear/](https://caddis-gr.github.io/fishing-gear/)**

## ✨ 주요 기능

- 🎨 **깔끔한 카드 디자인** - 브랜드별 색상으로 구분된 시각적 레이아웃
- 🔍 **실시간 검색** - 브랜드, 제품명으로 빠른 검색
- ⭐ **평점 시스템** - 5점 만점 별점 평가
- 📱 **반응형 디자인** - 모바일, 태블릿, PC 모두 지원
- 📊 **통계 대시보드** - 전체 리뷰 수, 브랜드 수, 평균 평점 표시

## 📦 리뷰 목록

### SA SONAR
- **Sink 25 Cold Manual v2** 🆕 - 한터지 바닥권 풀싱킹 서브 라인으로 재정의. 10~12m 단거리 투입 프로토콜 + 정지수 수렴 분석 ⭐⭐⭐⭐⭐
- **Sink Manual (KR)** - SA SONAR 싱크 라인 매뉴얼 (한글) ⭐⭐⭐⭐⭐
- **Sink Manual (EN)** - SA SONAR 싱크 라인 매뉴얼 (영문) ⭐⭐⭐⭐⭐
- **STILLWATER CLEAR EMERGER TIP** - 특별한 이머저 전용 라인 소재 ⭐⭐⭐⭐⭐

### 현장 가이드
- **싱킹 플라이라인 드레싱 완전정복** - 종일 싱킹라인 사용 시 발생하는 뻣뻣함 해결 가이드. 립밤부터 303 Aerospace까지 현실적인 드레싱 솔루션 ⭐⭐⭐⭐⭐

### RIO
- **Elite Sub-Surface CamoLux WF5I** - 카모 패턴 인터미디어트 싱킹 라인. 맑은 수질 중층 스텔스 공략 ⭐⭐⭐⭐⭐
- **Elite Technical Trout WF4F** - 가볍지만 멀리 날아가는 예술적 턴오버. Vision Onki 3100-4 조합 ⭐⭐⭐⭐⭐

### Vision
- **Ultimate Finesse** - Vision Onki 3100-4 + Hardy Marquis LWT 조합 ⭐⭐⭐⭐⭐

### Paradigm
- **Bouglé Gold** - T&T Paradigm 590-4 + Hardy Bouglé 3 1/4 ⭐⭐⭐⭐⭐

### Loon Outdoors
- **Deep Soft Weight** - 미세 수정 조절용 텅스텐 점토 웨이트 ⭐⭐⭐⭐⭐

### TMC
- **Prismatic Thread** - 빛 반사 특징이 뛰어난 특수 스레드 ⭐⭐⭐⭐

### Rio
- **Parabolic Sink Line** - U프로파일의 플라잉 라인 소재 ⭐⭐⭐⭐⭐

## 🗂️ 폴더 구조

```
fishing-gear/
├── index.html          # 메인 페이지
├── README.md           # 프로젝트 설명
└── reviews/            # 리뷰 HTML 파일들
    ├── sink25cold_manual_v2.html          # 🆕 Sink 25 Cold Manual v2
    ├── flyline_dressing_guide.html
    ├── RIO_Elite_CamoLux_WF5I_Review.html
    ├── RIO_Elite_Technical_Trout_WF4F.html
    ├── Vision_Onki_Ultimate_Finesse.html
    ├── Paradigm_Bouglé_Gold.html
    ├── 251219-Loon_Outdoors_Deep_Soft_Weight.html
    ├── 251224-TMC_Prismatic_Thread.html
    ├── 260108_sonar_sink_manual.html
    ├── 260108_sonar_sink_manual_EN.html
    ├── SA_SONAR_STILLWATER_CLEAR_EMERGER_TIP_Line.html
    └── Parabolic_Sink_Line.html
```

## 🚀 로컬에서 실행하기

```bash
# 저장소 클론
git clone https://github.com/CADDIS-GR/fishing-gear.git

# 폴더로 이동
cd fishing-gear

# 브라우저로 index.html 열기
# 또는 로컬 서버 실행
python -m http.server 8000
# http://localhost:8000 접속
```

## 📝 새 리뷰 추가하는 방법

### 1단계: 리뷰 HTML 파일 생성
```bash
# reviews 폴더에 새 HTML 파일 생성
cd reviews
cp 기존파일.html 새파일.html
```

### 2단계: 내용 수정
- 제품명, 브랜드, 설명 수정
- 상세 리뷰 작성
- 이미지 추가 (선택사항)

### 3단계: index.html 업데이트
메인 페이지의 카드 그리드에 새 카드 추가:

```html
<div class="gear-card bg-white rounded-2xl shadow-lg overflow-hidden">
  <div class="p-6">
    <div class="flex items-start justify-between mb-4">
      <span class="px-3 py-1 bg-blue-100 text-blue-700 rounded-full text-sm font-medium">브랜드명</span>
      <span class="text-2xl">🎣</span>
    </div>
    <h3 class="text-2xl font-bold text-slate-800 mb-2">제품명</h3>
    <p class="text-slate-600 mb-4 text-sm">간단한 설명</p>
    <div class="flex items-center gap-2 mb-4">
      <span class="text-yellow-400">⭐⭐⭐⭐⭐</span>
      <span class="text-sm text-slate-500">(5/5)</span>
    </div>
    <a href="reviews/파일명.html" 
       class="inline-block w-full text-center px-4 py-2 bg-blue-600 text-white rounded-lg hover:bg-blue-700 transition">
      상세 리뷰 보기
    </a>
  </div>
</div>
```

### 4단계: GitHub에 업로드
```bash
git add .
git commit -m "Add new review: [제품명]"
git push origin main
```

## 🎨 기술 스택

- **HTML5** - 구조
- **Tailwind CSS** - 스타일링
- **Vanilla JavaScript** - 검색 기능
- **GitHub Pages** - 호스팅

## 📊 통계

- **전체 리뷰**: 12개
- **브랜드 수**: 6개
- **평균 평점**: ⭐ 4.9/5.0
- **최근 업데이트**: 2026년 3월

## 🌟 최신 리뷰

### Sink 25 Cold Manual v2 (2026.03) 🆕
한터낚시터 3/14 세션 51마리 데이터를 바탕으로 Sonar Sink 25 Cold의 포지션을 전면 재정의. "버티컬 지깅 독립 운용"(v1)에서 **바닥권 풀싱킹 체계의 서브 라인**으로 진화. 정지수에서 플로팅 러닝라인도 결국 침하된다는 수렴 메커니즘 분석, 10~12m 단거리 + 추가 카운트 투입 프로토콜, 그리고 제조사(SA)와의 문의를 통해 확인한 "의도된 용도 vs 낚시대장의 실전 용도" 비교까지 담았습니다.

**핵심 변경점 (v1 → v2):**
- 📍 **포지션**: 독립 운용 → Titan 3D 메인 운용 후 발앞 집중 패턴 확인 시 투입
- 🎯 **캐스팅**: 장거리 → 10~12m 단거리 + 추가 카운트
- 📐 **근거**: 정지수 수렴 메커니즘 + 수직 상승각 기하학적 분석
- 😄 **에피소드**: SA 공식 답변 — "이 라인은 보팅 호수 협곡 지깅용입니다"

> 참고 (v1): [260108_sonar_sink_manual.html](https://caddis-gr.github.io/fishing-gear/reviews/260108_sonar_sink_manual.html)

---

### 싱킹 플라이라인 드레싱 완전정복 (2026.03)
종일 싱킹라인만 쓰다 보면 반나절 후 라인이 뻣뻣해진다. 전용 드레싱은 구하기 어렵고, 그래서 찾아낸 현실적인 해답들. 립밤(0원)부터 303 Aerospace Protectant(~17,000원), Loon Sink Fast(직구)까지 — 소수성 실리콘 원리와 함께 싱킹라인 드레싱의 모든 것을 정리한 현장 가이드.

**핵심 결론:**
- 🫦 **립밤** — 풀 싱킹라인 현장 즉석 드레싱 (비용 0원, 주머니 상시 비치)
- 🚗 **303 Aerospace Protectant** — 플로팅/싱크팁 라인 관리 (국내 구매 ~17,000원)
- 🏆 **Loon Sink Fast** — 싱킹라인 전용 정품 (직구 끼워넣기 ~$9)
- ⛔ **Armor All** — 절대 사용 금지 (PVC 코팅 장기 손상)

---

### RIO Elite Sub-Surface CamoLux WF5I (2026.03)
카모 패턴으로 물속에서 라인의 존재감을 낮추는 인터미디어트 싱킹 라인. Scott Centric 690-4 + CamoLux WF5I 조합으로 맑은 수질 중층 스텔스 공략에 특화된 세팅입니다.

**주요 특징:**
- 🎯 1.5~2ips 인터미디어트 싱킹 — 수심 2~6ft 중층 정밀 공략
- 🌿 카모 컬러링(올리브/다크그린) — 맑은 수질 스텔스 효과
- 🔗 ConnectCore Plus 저신축 코어 — 중층에서도 어신 감지 용이
- 🎣 30ft 짧은 헤드 — 최소 폴스 캐스팅으로 빠른 재투척 가능
- 📍 Hang Marker(20ft) — Hang & Re-cast 타이밍 시각적 확인

---

### RIO Elite Technical Trout WF4F (2026.02)
가볍지만 멀리 날아가고, 턴오버는 예술이다. Vision Onki 3100-4 (10ft #3) + RIO Elite Technical Trout WF4F 조합으로 마이크로 님핑과 드라이 플라이 프레젠테이션에 적합한 피네스 세팅입니다.

**주요 특징:**
- 🎯 49ft 롱 헤드의 탁월한 라인 컨트롤 & 멘딩 성능
- 🎣 Vision Onki 3100-4와의 좋은 궁합
- ✨ 예술적인 턴오버 — 리더 끝까지 에너지 전달
- 💫 마이크로 님핑 & 드라이 플라이 모두 적합

## 🤝 기여하기

이 프로젝트는 개인 아카이브이지만, 제안이나 피드백은 환영합니다!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 연락처

- GitHub: [@CADDIS-GR](https://github.com/CADDIS-GR)
- 프로젝트 링크: [https://github.com/CADDIS-GR/fishing-gear](https://github.com/CADDIS-GR/fishing-gear)

## 📄 라이선스

이 프로젝트는 개인 사용을 위한 것입니다.

---

<div align="center">

**🎣 플라이 낚시를 사랑하는 모든 이들에게 🎣**

Made with ❤️ by CADDIS-GR

</div>
