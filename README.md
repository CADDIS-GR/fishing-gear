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

### Vision
- **Ultimate Finesse** - Vision Onki 3100-4 + Hardy Marquis LWT 조합 ⭐⭐⭐⭐⭐

### Paradigm
- **Bouglé Gold** - T&T Paradigm 590-4 + Hardy Bouglé 3 1/4 ⭐⭐⭐⭐⭐

### Loon Outdoors
- **Deep Soft Weight** - 미세 수정 조절용 텅스텐 점토 웨이트 ⭐⭐⭐⭐⭐

### TMC
- **Prismatic Thread** - 빛 반사 특징이 뛰어난 특수 스레드 ⭐⭐⭐⭐

### SA SONAR
- **Sink Manual (KR)** - SA SONAR 싱크 라인 매뉴얼 (한글) ⭐⭐⭐⭐⭐
- **Sink Manual (EN)** - SA SONAR 싱크 라인 매뉴얼 (영문) ⭐⭐⭐⭐⭐
- **STILLWATER CLEAR EMERGER TIP** - 특별한 이머저 전용 라인 소재 ⭐⭐⭐⭐⭐

### Rio
- **Parabolic Sink Line** - U프로파일의 플라잉 라인 소재 ⭐⭐⭐⭐⭐

## 🗂️ 폴더 구조

```
fishing-gear/
├── index.html          # 메인 페이지
├── README.md           # 프로젝트 설명
└── reviews/            # 리뷰 HTML 파일들
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

- **전체 리뷰**: 8개
- **브랜드 수**: 5개
- **평균 평점**: ⭐ 4.9/5.0
- **최근 업데이트**: 2026년 1월

## 🌟 최신 리뷰

### Vision Onki - Ultimate Finesse (2026.01)
부드럽고 섬세한 피네스피싱의 완성. Vision Onki 3100-4 (10ft #3) + Hardy Marquis LWT #4 조합으로 소프트 해클 웨트와 마이크로 님핑에 최적화된 세팅입니다.

**주요 특징:**
- 🎯 10피트 #3 시스템의 정교함
- 🎣 Rio Elite Technical Trout 라인과의 완벽한 조화
- ✨ 라이트박스 이미지 뷰어 기능
- 💫 모던과 클래식의 만남

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
