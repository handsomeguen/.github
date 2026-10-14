<div align="center">

# 🏘️ handsomeguen

**글을 쓰고 마을을 꾸미는 블로그, Blogville을 만드는 팀이에요.**

[![Blogville](https://img.shields.io/badge/Blogville-운영_중-4c9a2a?style=flat-square)](https://unqiuepcg.java21.net)
[![Code](https://img.shields.io/badge/code-blogville-181717?style=flat-square&logo=github)](https://github.com/handsomeguen/blogville)
[![Docs](https://img.shields.io/badge/docs-명세·spec-181717?style=flat-square&logo=github)](https://github.com/handsomeguen/docs)

</div>

---

## 🏡 대표 프로젝트 · Blogville

> 티스토리처럼 글을 쓰는 블로그에, 도트(픽셀아트) 마을과 캐릭터 키우기를 더한 서비스예요.

| | |
|---|---|
| 🌐 서비스 | https://unqiuepcg.java21.net |
| 💻 코드 | https://github.com/handsomeguen/blogville |
| 📚 문서·명세 | https://github.com/handsomeguen/docs |

**주요 기능**

- ✍️ 에디터로 글쓰기(표·동영상·사진), 2단계 카테고리, 위젯, 다크 모드, 블로그 커버·강조색
- 👥 가입하면 블로그가 자동으로 생기고 `/@주소`로 바로 열림, 이웃·댓글·공감·알림
- 🔥 인기 글, RSS, 공유 미리보기, 📈 관심 종목 위젯
- 🏘️ 도트 마을: 집 꾸미기, 농사, 낚시, 옷 가게·미용실, 친구 마을 놀러 가기
- 🛠️ 관리자 페이지와 버그·문의 접수

## 🧰 기술 스택

**Frontend / Backend**

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tiptap](https://img.shields.io/badge/Tiptap-1a1a1a?style=flat-square)
![better-auth](https://img.shields.io/badge/better--auth-333333?style=flat-square)

**Database**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black)

**DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

## ⚙️ 이렇게 개발해요

- **Git Flow**: `feature → develop → release → main` 순서로 PR을 거쳐 배포
- **브랜치 보호**: main·develop은 PR과 자동 검사(`check`, 화면 테스트 `e2e`)를 통과해야 합쳐짐
- **무중단 배포**: main에 합치면 GitHub Actions가 도커 이미지를 만들고, nginx 블루-그린 전환으로 끊김 없이 배포
- **명세 먼저**: GitHub Spec Kit으로 기능마다 spec → plan → tasks를 쓰고 구현

## 📦 저장소

| 저장소 | 내용 |
|---|---|
| [blogville](https://github.com/handsomeguen/blogville) | 서비스 소스 코드 (Next.js) |
| [docs](https://github.com/handsomeguen/docs) | 요구사항 명세서와 기능별 spec (Spec Kit) |
