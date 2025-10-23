# 김예은의 포트폴리오 (Github pages 웹 사이트)

김예은의 포트폴리오 페이지입니다. Hugo Blox Academic CV 테마와 Tailwind CSS v4를 기반으로 커스터마이징합니다. 소개, 이력, 프로젝트, 금융 IT 역량, 수강 강의, 연락하기의 콘텐츠를 제공합니다.

* **Live (KO)**: <https://yeeuneey.github.io/>
* **Live (EN)**: <https://yeeuneey.github.io/en/>
* **배포 파이프라인**: [.github/workflows/deploy.yml](.github/workflows/deploy.yml)

---

## ✨ 주요 특징 및 구현 내용
* **히어로 & 이력서 섹션** — content/{ko,en}/_index.md
  * Swiper 슬라이더(layouts/_partials/slider.html - 현재는 _index.md 내부에 스크립트 포함)와 custom-hero 클래스(assets/css/custom.css)로 메인 페이지 상단 슬라이더 및 자기소개 섹션의 배경 이미지, 오버레이, CTA 버튼 스타일을 강화했습니다.
  * CV 다운로드 버튼은 static/uploads/resume.pdf 와 static/en/uploads/resume.pdf 파일을 각 언어 페이지(content/{ko,en}/authors/admin/_index.md의 button 설정)에서 링크하여 제공합니다.
* **프로젝트 카드 뷰** — content/{ko,en}/projects/*/index.md
  * 8-puzzle·AB_Omok·CookieRun·DB 등 4개 프로젝트(content/{ko,en}/projects/)를 카드(article-grid 뷰) 및 상세 페이지로 구성했습니다.
  * 각 프로젝트 상세 페이지(index.md) 내 Front matter의 links를 통해 GitHub 저장소 링크를, 본문 내 HTML을 통해 보고서 PDF 다운로드 링크(.hb-btn 스타일 적용)를 제공합니다.
* **기술·과목 매핑 섹션** — content/{ko,en}/tech/, content/{ko,en}/related-courses/
  * 메인 페이지(_index.md)의 collection 블록에서 design.view: showcase를 사용하여 금융 IT 핵심 기술과 연관 과목을 좌우 배치 카드(layouts/partials/views/showcase.html)로 연결했습니다.
* **Chart.js 평가 시각화** — content/{ko,en}/courses/*/*.md
  * 각 과목 상세 페이지 내 마크다운에 <canvas> 태그와 <script> 블록을 직접 포함하여 Chart.js를 이용, 평가 비율을 원형 차트로 시각화했습니다.
* **연락처 & 소셜 링크** — content/{ko,en}/contact/index.md
  * Google Maps iframe으로 지도 정보를 표시하고, Font Awesome 아이콘을 사용하여 이메일·전화·GitHub·Discord·Instagram 링크를 제공합니다.
* **스타일 커스터마이징** — assets/css/custom.css
  * 다크/라이트 모드 스타일 조정, 슬라이더 및 히어로 섹션 오버레이, 네비게이션 바 호버 효과, 카드 그림자 및 호버 효과, 본문 텍스트 양쪽 정렬(.article-container p 등), 버튼(.hb-btn) 호버 효과 등을 직접 정의했습니다.
* **다국어 및 네비게이션** - config/_default/menus.{ko,en}.yaml, config/_default/languages.yaml, i18n/
  -한국어(기본)와 영어 2개 국어를 지원하며, 6개 메인 메뉴와 하위 메뉴(연구, 강의 하위)를 구성했습니다. UI 텍스트는 i18n/ 파일에서 관리합니다.
* **SEO(검색 엔진)** — config/_default/params.yaml, static/googlef2929d6ee638ba1a.html
  * 사이트 제목(hugo.yaml), 설명, 키워드, Open Graph 대표 이미지(params.yaml 내 marketing.seo)를 설정하고, Google Search Console 소유권 확인 파일(static/google*.html)을 추가했습니다.
* **Pagefind 검색 기능** - config/_default/params.yaml, .github/workflows/deploy.yml
  * Hugo Blox 테마의 Pagefind 검색 기능을 활성화 (params.yaml 내 features.search)하여 사이트 내 콘텐츠 검색을 지원합니다.
  * GitHub Actions 배포 과정에 Pagefind 인덱싱 단계 (pagefind --source 'public')를 포함하여, 배포 시 자동으로 최신 콘텐츠 기반의 검색 인덱스를 생성합니다.
* **자동 배포** - .github/workflows/deploy.yml
  * GitHub Actions를 사용하여 main 브랜치 푸시 시 Hugo 빌드, Pagefind 인덱싱, GitHub Pages 배포를 자동화했습니다.

---

## ✅ 구조

```
├─ assets/                 # Tailwind CSS v4 커스텀 스타일, JS 스니펫 등
│  └─ css/custom.css       # 전역 테마/오버레이/버튼/정렬 유틸리티
├─ content/                # 다국어 콘텐츠 루트 (ko, en)
│  ├─ _index.md            # 랜딩 페이지(슬라이더·바이오 구성)
│  ├─ authors/admin/       # 프로필 데이터 및 아바타
│  ├─ projects/<slug>/     # 4개 대표 프로젝트 + PDF 보고서 링크
│  ├─ courses/
│  │  ├─ completed/<학기>/ # 수강 완료 과목 카드 + Chart.js 평가 차트
│  │  └─ current/3-2/      # 현재 수강 중인 과목 정리
│  ├─ tech/<slug>/         # 금융 IT 핵심 기술 카드(Unsplash 캡션 포함)
│  ├─ related-courses/<slug>/# 기술과 연결되는 교과목 카드
│  ├─ experience.md        # 활동 이력/스킬/언어 섹션
│  └─ contact/index.md     # 지도, 연락처, 소셜 링크
├─ layouts/
│  └─ partials/views/*.html # showcase·outline 카드 뷰 (템플릿 활용)
├─ static/
│  ├─ media/               # 배너, 슬라이더, 공유용 이미지, 로고, 아이콘
│  ├─ uploads/             # 이력서·프로젝트 보고서 PDF
│  └─ google*.html         # 검색 콘솔 소유권 검증 파일
├─ config/_default/
│  ├─ menus.{ko,en}.yaml   # 다국어 메뉴 및 서브 메뉴 구조
│  ├─ params.yaml          # 다크모드·SEO·헤더·파비콘 설정
│  └─ languages.yaml       # 기본 언어, 콘텐츠 디렉터리 매핑
├─ .github/workflows/      # GitHub Actions (배포 자동화 등)
├─ hugoblox.yaml           # Hugo Blox 템플릿 및 모듈 버전
└─ package.json / pnpm-lock # Tailwind CLI 및 빌드 의존성
```

--- 

## 🛠️ 콘텐츠 구조 및 코드 설명

### 1. 설정 파일 (config/_default/)

* hugo.yaml: Hugo 사이트 기본 설정 (사이트 제목, URL, 기본 언어 등)입니다.
* languages.yaml: 다국어(ko, en) 설정하였습니다.
* menus.*.yaml: 언어별 네비게이션 메뉴 구조를 정의합니다.
* module.yaml: Hugo Blox 테마 모듈을 로드합니다.
* params.yaml: 테마 상세 설정하였스비다.
  * appearance: 다크/라이트 모드, 테마 색상(teal).
  * marketing.seo: 검색 엔진 최적화를 위한 사이트 설명, 키워드, 대표 이미지 경로 설정하였습니다.
  * features.search: Pagefind 검색 기능 활성화 (provider: pagefind, enable: true)하였습니다.
  * header.navbar: 로고, 검색 아이콘, 테마/언어 선택 아이콘 표시를 설정하였습니다.

### 2. 콘텐츠 (content/)

* 언어별 디렉토리 (`en/`, `ko/`)로 구분됩니다.
* 각 디렉토리 내부는 페이지 종류별(authors, courses, projects, tech 등)로 구성됩니다.
* `authors/admin/_index.md`: 사이트 소유자(본인)의 프로필 정보를 마크다운 형식으로 작성합니다 (이름, 소속, 관심분야, 학력, 경력, 기술 스택, 자기소개 등).
* `courses/`: 수강했거나 수강 중인 강의 정보를 담고 있습니다. `completed/` 와 `current/` 로 나뉘며, 학기별 디렉토리(`1-2/`, `2-1/`, ...) 안에 각 과목 `.md` 파일이 있습니다. 각 과목 파일에는 강의 목표, 담당 교수, 교재, 평가 비율(Chart.js 사용), 주차별 내용 등이 포함됩니다.
* `projects/`: 수행한 프로젝트 정보를 담습니다. 각 프로젝트 디렉토리 안의 `index.md` 파일에 프로젝트 설명, GitHub 링크, 사용 기술 태그, 보고서 PDF 다운로드 링크 등이 포함됩니다.
* `tech/`: 주요 기술 스택(AI, 클라우드, 보안, 웹서비스 등)에 대한 설명을 담고 있습니다.
* `related-courses/`: `tech/` 에서 설명한 기술들과 관련된 수강 과목들을 연결하여 보여줍니다.
* `_index.md`: 각 섹션의 메인 페이지 역할을 하며, 하위 콘텐츠 목록을 보여주는 방식을 설정합니다. 메인 페이지(`content/ko/_index.md`, `content/en/_index.md`)에는 Swiper 라이브러리를 사용한 이미지 슬라이더 코드가 포함되어 있습니다.

### 3. 레이아웃 (`layouts/`)

* Hugo가 콘텐츠를 HTML 페이지로 렌더링하는 방법을 정의하는 템플릿 파일들입니다.
* `_partials/views/`: 콘텐츠 목록을 보여주는 방식(view)에 대한 템플릿 조각들이 있습니다.
    * `showcase.html`: 이미지와 텍스트 설명을 좌우로 배치하여 보여주는 템플릿입니다 (Tech, Related Courses 섹션에서 사용).
    * `outline.html`: 과목 목록을 카드 형태로 간략하게 보여주는 템플릿입니다 (Courses 섹션에서 사용).
* `partials/hooks/head-end/`: HTML `<head>` 태그 끝에 추가될 코드를 정의합니다. `github-button.html`은 GitHub 버튼 스크립트를 로드합니다.

### 4. 에셋 및 정적 파일 (`assets/`, `static/`)

* `assets/css/custom.css`: 기본 테마 스타일을 덮어쓰거나 추가하는 사용자 정의 CSS 코드입니다. 슬라이더, 히어로 섹션 배경, 네비게이션 바, 카드 스타일 등 다양한 시각적 요소를 커스터마이징합니다.
* `static/media/`: 웹사이트 전반에 사용되는 이미지 파일들이 저장됩니다 (슬라이더 이미지, 페이지 배너, 로고 등).
* `static/uploads/`: 다운로드 가능한 파일들이 저장됩니다 (이력서 PDF, 프로젝트 보고서 PDF 등).
* `static/googlef2929d6ee638ba1a.html`: 구글 사이트 소유권 확인을 위한 HTML 파일입니다.

### 5. 자동화 (`.github/workflows/`)

* `deploy.yml`: GitHub Actions 워크플로우 파일입니다. `main` 브랜치에 코드가 푸시되면 자동으로 Hugo 사이트를 빌드하고 GitHub Pages로 배포하는 과정을 정의합니다. Node.js 설정, Hugo 설치, pnpm을 이용한 의존성 설치, Hugo 빌드, Pagefind 검색 인덱스 생성, 결과물 업로드 및 배포 단계를 포함합니다.
* `import-publications.yml`: `publications.bib` 파일이 변경되면, 이를 마크다운 파일로 변환하여 `content/publication/` 디렉토리에 저장하고 Pull Request를 생성하는 워크플로우입니다. Python과 `academic` 라이브러리를 사용합니다.

### 6. 기타 파일

* `package.json` / `pnpm-lock.yaml`: Node.js 프로젝트 설정 및 의존성 관리 파일입니다. 주로 Tailwind CSS 관련 패키지를 관리합니다.
* `.gitignore`: Git 버전 관리에서 제외할 파일 및 디렉토리 목록입니다 (빌드 결과물, Node.js 모듈 등).
* `LICENSE.md`: 프로젝트 코드의 라이선스 정보 (MIT).
* `i18n/`: 국제화(다국어) 지원을 위한 텍스트 번역 파일입니다 (`en.yaml`, `ko.yaml`).

---

## 🤝 기여하기

개선 제안이나 버그 리포트는 언제나 환영합니다. Issues 탭을 통해 알려주세요.

---

## 📄 라이선스

코드와 템플릿 변경 사항은 MIT 라이선스(`LICENSE.md`)를 따르며, 텍스트·이미지 등 콘텐츠 저작권은 김예은에게 있습니다.