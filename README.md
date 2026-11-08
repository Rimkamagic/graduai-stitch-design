# GraduAI — Academic Intelligence UI

대학생의 수강 신청, 시간표 관리, 졸업요건 확인을 돕는 학사 관리 서비스의 UI/UX 프로토타입입니다. Google Stitch로 만든 화면 시안과 디자인 시스템을 담고 있습니다.

> 이 저장소는 **프론트엔드 화면 시안**입니다. 실제 로그인, 데이터 저장, AI 추천 기능은 포함되어 있지 않습니다.

## 미리보기

내가 만든 Stitch 프로젝트는 아래 링크에서 확인할 수 있습니다.

🔗 **[GraduAI Stitch 미리보기](https://stitch.withgoogle.com/preview/2166015438719883130?node-id=3102ed262b7a4334b5f4b397590e8386)**

## 주요 화면

- 학생 대시보드 및 주간 시간표
- 교과과정 편람과 졸업요건 분석
- AI 과목 추천 및 AI 시간표 비교
- 보관 시간표와 개인정보 관리
- 관리자 로그인, 학생·학사일정·수강정책 관리
- 공지사항, 백업/복구, 운영 현황, 시스템 로그, 관리자 계정 관리

## 실행 방법

각 화면은 독립적인 HTML 파일입니다. 원하는 화면 폴더의 `code.html` 파일을 브라우저에서 열면 됩니다.

```text
_1/code.html      학생 대시보드
_5/code.html      졸업요건 분석
ai_1/code.html    AI 과목 추천
ai_2/code.html    AI 추천 시간표 비교
_8/code.html      관리자 로그인
```

모든 화면을 웹 서버로 확인하려면 프로젝트 최상위 폴더에서 아래 명령을 실행한 뒤 표시되는 주소를 브라우저에서 여세요.

```bash
npx serve .
```

## 프로젝트 구조

```text
.
├── _1 ~ _18/              # 학생·관리자 화면별 HTML 및 스크린샷
├── ai_1/, ai_2/           # AI 기능 화면
└── academic_intelligence/
    └── DESIGN.md          # 색상, 타이포그래피, 컴포넌트 가이드
```

## 기술 요소

- HTML5
- Tailwind CSS CDN
- Google Fonts (Inter, Material Symbols)
- Google Stitch

## 디자인 시스템

디자인 토큰, 레이아웃 원칙, 색상과 컴포넌트 기준은 [academic_intelligence/DESIGN.md](./academic_intelligence/DESIGN.md)에서 볼 수 있습니다.
