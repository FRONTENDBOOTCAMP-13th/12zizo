# **12간지**팀 - TAING

## 팀 소개

| **이름** | **역할** | **담당 기능(화면)** |
| --- | --- | --- |
| 엄현욱 | 스크럼 마스터 | 랜딩 페이지, 메인 페이지, 인덱스, 애니메이션 |
| 김지연 | 팀원 | 메인 페이지 배너, 메인 페이지, 접근성 관리, 리드미 |
| 이진현 | 팀원 | 로그인, 회원가입, 아이디 찾기, 메인 페이지, 모달, 검색 페이지 |
| 우영찬 | 팀원 | 프로필 페이지, 비밀번호 찾기, 검색 페이지, 메인 페이지, 툴팁 |

## 프로젝트 개요

- 프로젝트명: TAING UI 제작
- 기간: 2025.03.14 ~ 2025.03.25
- 팀원: 엄현욱, 우영찬, 이진현, 김지연
- 목표: 효율적인 협업과 지속 가능한 코드 작성하기!
    - 목표1: 버전 관리 습관 기르기
    - 목표2: 반응형 웹 디자인 구현하기
    - 목표3: 팀 소통 및 피드백 문화 강화
    - 목표4: UI 접근성 향상
    - 목표5: 문서화 작업 강화

## 기술 스택

- **Frontend**: HTML5, TailwindCSS, Vite, JavaScript
- **문서화**: MarkDown
- **협업툴**: GitHub, Discode, Notion
- **디자인&개발도구**: Figma, Visual Studio Code

## 프로젝트 구조

```html
root
├── public
│   └── font/                 # 폰트 파일, 파비콘.svg 저장
├── src
│   ├── assets/               # svg, webp 같은 이미지 파일
│   ├── components/           # 재사용 가능한 컴포넌트
│   ├── pages/                # 구현할 페이지 파일
│   ├── md/                   # 개인별 회고 파일
│   ├── main.js               
│   └── style.css             
├── .gitignore               
├── index.html                # HTML 진입점
├── package.json              
├── package-lock.json        
├── README.md                 # 프로젝트 설명 문서
└── vite.config.js            # Vite 설정 파일
```

## 프로젝트 기획

1. 개발 환경 세팅
    - Vite 환경 세팅
    - TailwindCSS설정 및 적용
    - 프로젝트 구조 설계 및 파일 생성
2. 컴포넌트 제작
    - Header , Footer
    - Button, Input
    - 이미지 캐러셀
    - 검색, 모달
3. 페이지 구현
    - 랜딩 페이지
    - 프로필 페이지
    - 메인 페이지
    - 로그인 페이지
    - 회원가입 페이지

## 협업 방식

1. 이슈를 등록한 후, 해당 작업을 위한 브랜치를 생성
2. 기능을 개발 후, Pull Request 작성
3. 코드 리뷰 후 필요한 수정 사항을 반영하고 병합

## Git commit 컨벤션

| 이모지 | 태그 | 설명 |
| --- | --- | --- |
| 🎉 | Init | 초기 설정 |
| 🎨 | Feat | 기능 추가, 변경 |
| 🔥 | Remove | 파일이나 코드 삭제 |
| 📝 | Docs | README.md, JSON 파일 등 문서 수정 및 라이브러리 설치 |
| 💄 | Style | CSS 등 사용자 UI 디자인 변경 |
| ♻️ | Refactor | 코드 리팩토링 |
| 🧪 | Test | 테스트 코드 추가, 삭제, 변경 등 |
| 🐎 | CI | CI/CD 관련 설정 및 수정 |
| 🐳 | Chore | 패키지 매니저 설정 등 운영 코드 변경이 없는 경우 |

## 배포환경

- 배포 환경 : Netlify
- 배포 URL : https://taing-ui-project-12zizo.netlify.app/