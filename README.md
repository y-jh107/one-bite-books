# 📚 One Bite Books – Frontend

이 프로젝트는 개인 창작물이 아닌,  
인프런 강의 「**한입 크기 Next.js**」의 Page Router 파트를 학습하며 따라 만든 실습 프로젝트입니다.

본 레포지토리는 **프런트엔드 전용 레포지토리**로,  
강의에서 설명하는 **Next.js Page Router 구조를 그대로 구현**하고  
분리된 백엔드 API 서버와 연동하여 동작합니다.

강의 내용을 단순히 따라치는 데서 그치지 않고,  
**프런트엔드 / 백엔드 분리 구조와 실제 배포 환경에서의 설정을 직접 경험하고 정리하는 것**을 목표로 합니다.

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
- Next.js Page Router 기반 페이지 라우팅
- REST API를 통한 서버 데이터 연동

---

## 🗂️ Repository Structure

```
one-bite-books-page-router
├─ src/ Frontend source code
├─ public/
├─ package.json
└─ README.md
```

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

Dev / Infra

- Git & GitHub
- Vercel

---

## 🔧 Local Development

```
npm install
npm run dev
```

API 서버는 별도의 백엔드 레포지토리에서 실행하거나,  
배포된 Production API 서버를 사용합니다.

---

## 🔗 Backend Repository

백엔드 서버는 별도의 레포지토리로 분리되어 관리됩니다.

https://github.com/y-jh107/one-bite-books-server

---

## 📌 Purpose of This Repository

- Next.js Page Router 구조 학습
- 프런트엔드 중심의 프로젝트 구조 정리
- 백엔드 서버 분리 및 API 연동 경험
- Vercel 기반 프런트엔드 배포 과정 이해

---

## 📎 Notes

- 본 프로젝트의 UI 및 기능 구성은 인프런 강의 「한입 크기 Next.js」의 내용을 기반으로 합니다.
- 이 레포지토리는 데이터베이스 설계보다는 **Next.js 페이지 라우팅 구조와 프런트엔드 배포 흐름**을 이해하는 것을 목표로 합니다.
- 백엔드 서버 및 데이터베이스 스키마는 강의에서 제공된 코드를 기반으로 하며, 본 레포지토리에는 포함되어 있지 않습니다.
- 외부 공유 시에는 **Production 도메인만 사용**합니다.
- Preview URL은 내부 테스트 및 개발 확인 용도로만 사용합니다.

---

## 🙌 Author

학습 및 프런트엔드 배포 정리  
https://github.com/y-jh107
