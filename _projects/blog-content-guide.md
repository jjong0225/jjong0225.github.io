---
title: "al-folio 블로그 컨텐츠 활용 가이드"
permalink: /projects/blog-content-guide/
date: 2024-06-01
---

# al-folio 블로그 컨텐츠 활용 가이드

이 문서는 al-folio(Jekyll) 테마에서 블로그, 프로젝트, 뉴스, 논문, 페이지 등 주요 컨텐츠를 어떻게 작성하고 활용하는지 간략히 정리한 가이드입니다.

## 1. 블로그 글 작성
- 위치: `_posts/`
- 파일명: `YYYY-MM-DD-title.md`
- 예시:
  ```markdown
  ---
  title: "블로그 글 제목"
  date: 2024-06-01
  categories: [blog]
  tags: [태그1, 태그2]
  ---
  본문 내용
  ```

## 2. 프로젝트 작성
- 위치: `_projects/`
- 파일명: `project-name.md`
- 예시:
  ```markdown
  ---
  title: "프로젝트명"
  permalink: /projects/project-name/
  date: 2024-06-01
  ---
  프로젝트 설명
  ```

## 3. 뉴스/공지 작성
- 위치: `_news/`
- 파일명: `news-title.md`
- 예시:
  ```markdown
  ---
  title: "뉴스 제목"
  date: 2024-06-01
  ---
  뉴스 내용
  ```

## 4. 페이지(About 등) 작성
- 위치: `_pages/`
- 파일명: `about.md`, `people.md` 등
- 예시:
  ```markdown
  ---
  title: "About Me"
  permalink: /about/
  ---
  자기소개 등 페이지 내용
  ```

## 5. 논문/출판물 관리
- 위치: `_bibliography/papers.bib`
- 예시:
  ```bibtex
  @article{sample2024,
    title={샘플 논문},
    author={홍길동 and 김철수},
    journal={Jekyll Studies},
    year={2024},
    doi={10.1234/jekyll.2024.001}
  }
  ```

## 6. 기타
- 이미지, 파일 등은 `assets/` 폴더에 저장
- 사이트 설정은 `_config.yml`에서 관리

---
이 가이드를 참고해 각 컨텐츠를 쉽게 추가/관리할 수 있습니다.
