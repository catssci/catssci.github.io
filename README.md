# TG's ML Blog

추천 시스템과 NLP, LLM을 다루는 기술 블로그입니다.

## 🔗 블로그 주소
[https://catssci.github.io](https://catssci.github.io)

## 🛠 Tech Stack
- Jekyll + minimal-mistakes theme
- GitHub Pages

## 📁 구조
```
├── _config.yml          # 사이트 설정
├── _posts/              # 블로그 포스트
├── _pages/              # 정적 페이지 (About, Categories 등)
├── _data/               # 네비게이션 등 데이터
└── assets/images/       # 이미지 파일
```

## ✍️ 새 글 작성법
1. `_posts/` 폴더에 `YYYY-MM-DD-제목.md` 형식으로 파일 생성
2. 상단에 YAML front matter 작성:
```yaml
---
title: "글 제목"
excerpt: "요약"
date: YYYY-MM-DD
categories:
  - 카테고리명
tags:
  - 태그1
  - 태그2
toc: true
toc_sticky: true
---
```
3. Markdown으로 본문 작성
4. commit & push

## 📝 카테고리
- `Recommendation` : 추천 시스템
- `NLP` : 자연어처리
- `LLM` : 대규모 언어모델
- `MLOps` : ML 운영/인프라
- `Blog` : 블로그 관련

## 로컬 실행
```bash
bundle install
bundle exec jekyll serve
```
http://localhost:4000 에서 확인
# catssci.github.io
