# Student Management System

수강생 정보, 출결, 진도 및 학습 기록을 한곳에서 효율적으로 관리하기 위한 웹 애플리케이션입니다.

## 기술 스택

- React 19
- Vite 8
- TypeScript
- Fluent UI React Components
- React Router
- TanStack Query
- React Hook Form + Zod
- Vitest + Testing Library + MSW
- CSS Custom Properties

## 폴더 구조

```text
src/
├── app/          # 앱 설정, Provider, 라우터
├── assets/       # 이미지 및 정적 파일
├── components/   # 공통 UI 컴포넌트
├── features/     # 기능별 모듈
├── hooks/        # 공통 커스텀 훅
├── lib/          # 외부 라이브러리 설정 및 유틸리티
├── mocks/        # MSW 핸들러와 목 데이터
├── pages/        # 라우트 단위 페이지
├── styles/       # 전역 스타일과 CSS 변수
├── test/         # 테스트 설정 및 공통 도구
├── types/        # 공통 타입 정의
└── main.tsx      # 애플리케이션 진입점
```
