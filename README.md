# 📘 스마트 제품 설명서 앱 (User Guide App)

> **정하경 | 학사학위 졸업 작품 (2024)**

---

## 📖 프로젝트 개요

**‘스마트 제품 설명서 앱’**은 복잡한 종이 사용설명서를 대체하고,  
사용자가 **언제 어디서나 간편하게 전자 설명서를 검색 및 확인할 수 있는 모바일 서비스**입니다.  
각 제조사 홈페이지에 흩어진 PDF 설명서를 한곳에 모아 제공합니다.

---

## 🧩 개발 배경 및 문제 인식

| 문제점 | 해결 방안 |
|--------|------------|
| 기존 메뉴얼 검색의 복잡성 | 직관적인 인터페이스 제공으로 탐색 과정 최소화 |
| 종이 설명서의 훼손 및 분실 문제 | 디지털 기반 전자 설명서로 접근성 강화 |
| 글씨 크기, 검색 불편 등 사용자 경험 저하 | 모바일 UI/UX 최적화 및 AI 검색 기능 도입 |

---

## ⚙️ 주요 기능

- **회원가입 / 로그인**
- **제품 리스트 조회 및 상세 설명**
- **PDF 업로드 및 뷰어 기능**
- **AI 기반 설명서 검색 (OpenAI API)**
- **스크랩(즐겨찾기) 기능**
- **게시판 기능 (제품 관련 소통 공간)**

---

## 🏗️ 시스템 구성

| 구성 요소 | 설명 |
|------------|------|
| **Front-end** | Android Studio (Java, XML) |
| **Back-end** | PHP + MariaDB + phpMyAdmin |
| **크롤링/데이터 처리** | Selenium, Pandas |
| **AI 기능** | OpenAI API 활용 (AI Guide) |
| **IDE / 환경** | Visual Studio Code, Android Studio |

---

## 🧱 시스템 구조

```
[사용자]
   ↓
[안드로이드 앱] — (HTTP 통신) → [PHP 서버]
   ↓                                   ↓
[OpenAI API]                    [MariaDB + phpMyAdmin]
```

---

## 🖥️ 구현 예시

### 📱 앱 주요 화면
1. 로그인 / 회원가입  
2. 제품 리스트 및 상세 보기  
3. PDF 업로드 및 보기  
4. AI Guide 검색 기능  
5. 게시판 (사용자 커뮤니티)

---

## 💡 기대 효과

| 항목 | 기대 내용 |
|------|------------|
| **사용자 편의성 향상** | PDF 파일을 다운로드하지 않고도 바로 확인 가능 |
| **환경 보호** | 종이 사용설명서 사용 감소 |
| **정보 접근성 개선** | 최신 설명서를 쉽게 조회 가능 |
| **소통 강화** | 게시판을 통한 사용자 간 정보 공유 |

---

## 🧰 사용 기술

- **Language** : Java, PHP, Python  
- **Database** : MariaDB  
- **Frameworks / Tools** : Android Studio, phpMyAdmin, Selenium, Pandas  
- **API** : OpenAI API  
- **IDE** : Visual Studio Code

---

## 📽️ 시연 영상

> 📹 [시연 영상 링크 (추가 예정)]()

---

## 🧑‍💻 개발자 정보

| 항목 | 내용 |
|------|------|
| **이름** | 정하경 |
| **프로젝트 유형** | 학사학위 졸업작품 |
| **제작 연도** | 2024 |

---

## 🖼️ 앱 아이콘 이미지 출처
<img width="32" height="32" alt="free-icon-user-guide-5558175" src="https://github.com/user-attachments/assets/215f84ad-df35-4cc7-bc73-92741a5136ef" />

> 아이콘 제작자: [Freepik - Flaticon](https://www.flaticon.com/kr/free-icon/user-guide_5558175)

---

## 📊 발표 자료

프로젝트 발표용 PPT는 **미리캔버스(Miricanvas)**를 활용하여 제작함.

---

> © 2024. 정하경. All rights reserved.
