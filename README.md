# github-collabo
# 🤝 GitHub Collabo Project

GitHub을 활용한 팀 협업 및 웹 페이지 제작 실습 프로젝트입니다.

---

## 📌 프로젝트 개요

팀원들과 Git 브랜치 전략 및 Pull Request(PR) 워크플로우를 활용하여 소개 및 문의 웹 페이지를 구축했습니다.

---

## 📂 파일 및 디렉토리 구성

```text
github-collabo/
├── about.html       # 회사 및 팀 소개 페이지 (비전, 핵심 가치, 미션 등)
├── contact.html     # 문의 양식 및 회사 연락처 안내 페이지
├── .gitignore       # Git 추적 제외 설정 파일
└── README.md        # 프로젝트 소개 및 협업 내역 문서
```

---

## 🌟 주요 기능 및 구현 내용

### 1. About 페이지 (`about.html`)
- **회사/팀 소개**: 팀의 비전과 미션 소개
- **핵심 가치**: 사용자 중심, 지속적인 협업 및 소통 등의 가치 명시
- **팀 연락처 정보**: 이메일, 전화번호, 주소 제공

### 2. Contact 페이지 (`contact.html`)
- **문의 접수 폼**: 이름, 이메일, 연락처, 문의 내용 입력 양식
- **회사 정보**: 오프라인 위치(서초구 고속터미널) 및 고객지원 연락처 표시

---

## 🛠️ 기술 스택

- **언어 및 마크업**: HTML5
- **버전 관리 및 협업**: Git, GitHub (Branch, Pull Request, Code Review)

---

## 🚀 협업 진행 내역 (Git & GitHub Workflow)

1. **브랜치 기반 개발**:
   - `AAA` 브랜치: `contact.html` 생성 및 문의 폼/회사 정보 구현
   - `BB` 브랜치: `about.html` 생성 및 팀 스토리/가치/소개 구현
2. **Pull Request & 병합**:
   - 각 브랜치 작업 후 GitHub PR 생성 및 상호 코드 리뷰 진행
   - `main` 브랜치로 순차적 병합 (Merge) 완료
3. **최신화 및 문서화**:
   - `main` 브랜치 최신 변경사항 동기화
   - 프로젝트 `README.md` 작성 및 정리

---

## 💻 실행 방법

1. 저장소를 클론(Clone)합니다:
   ```bash
   git clone https://github.com/gamgamgam25/github-collabo.git
   ```
2. 프로젝트 폴더로 이동하여 브라우저에서 웹 페이지를 엽니다:
   - `about.html` 또는 `contact.html` 파일을 더블 클릭하거나 브라우저로 드래그하여 실행합니다.