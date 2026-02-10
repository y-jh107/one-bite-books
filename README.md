# 📚 One Bite Books

이 프로젝트는 개인 창작물이 아닌,  
**인프런 강의 「한입 크기 Next.js」의 Page Router 파트를 학습하며 따라 만든 실습 프로젝트**입니다.

프런트엔드는 강의에서 설명하는 Next.js Page Router 구조를 그대로 구현하였고,  
서버는 **강의에서 제공된 API 파일을 수정 없이 그대로 사용**했습니다.

본 레포지토리는 강의 내용을 단순히 따라치는 데서 그치지 않고,  
**실제 배포 환경에서 발생하는 설정 문제와 구조를 직접 경험하고 정리하는 것**을 목표로 합니다.

---

## 📖 Reference

- 강의명: 한입 크기 Next.js
- 강의 링크  
  https://inf.run/AfmqK

---

## ✨ Features

- 전체 도서 목록 조회
- 추천 도서 목록 분리 표시
- 도서 클릭 시 상세 페이지 이동
- Next.js Page Router를 활용한 페이지 라우팅
- REST API를 통한 서버 데이터 연동

---

## 🗂️ Repository Structure

    one-bite-books
    ├─ client               # Frontend (Next.js Page Router 실습)   
    ├─ server/              # Backend API (강의 제공 코드)
    └─ README.md

---

## 🚀 Live Demo (Production)

Frontend
- 배포 수정 중에 있습니다.
---

## 🛠 Tech Stack

Frontend
- Next.js (Page Router)
- React
- TypeScript
- CSS Modules

Backend
- NestJS
- TypeScript
- Prisma
- REST API  
  (강의에서 제공된 서버 코드 그대로 사용)

Database
- Supabase (PostgreSQL)

Dev / Infra
- Git & GitHub
- Vercel

---

## 🔧 Local Development

Frontend 실행

    cd client
    npm install
    npm run dev

Backend 실행

    cd server
    npm install
    npm run dev

---

## 📌 Purpose of This Repository

- Next.js Page Router 구조 학습
- 강의 예제를 실제 배포 환경까지 연결
- Vercel 배포 과정 이해
- 프런트엔드 / 서버 분리 배포 경험

---

## 📎 Notes

- 본 프로젝트의 UI 및 기능 구성은 인프런 강의 「한입 크기 Next.js」의 내용을 기반으로 합니다.
- 이 레포지토리는 데이터베이스 설계보다는 Next.js 페이지 라우팅 구조와 Vercel 배포 과정을 이해하는 것을 목표로 합니다.
- 데이터베이스 스키마 및 초기 데이터셋은 강의에서 제공된 코드를 그대로 사용했습니다.
- 백엔드 서버 또한 강의 제공 파일을 수정 없이 사용했습니다.
- 외부에 공유할 때는 Production 도메인만 사용합니다.
- Preview URL은 내부 테스트 및 개발 확인 용도로만 사용합니다.

---

## 🙌 Author

학습 및 배포 정리  
https://github.com/y-jh107
