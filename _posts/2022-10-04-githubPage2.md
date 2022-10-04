---
layout: single
title: "깃허브 페이지 만들기(2)"
classes: wide
toc : true
toc_sticky: true
tags:
  - minimal Mistakes
  - github pages
---

# 깃허브 페이지의  헤더 메뉴 구성하기  
깃허브 페이지의 헤더 메뉴 구성은 `_pages` 폴더를 만들고 메뉴에 들어갈 내용의 파일을 작성합니다. 우선, `_data` 폴더의 navigation.yml 파일을 열고 아래와 같이 수정합니다. About 메뉴를 만들고 링크를 설정 후 `_pages` 폴더에 about.md 파일을 작성하면 됩니다.    
  
```md
  # main links
  main:
  # - title: "Quick-Start Guide"
  #   url: https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/
  - title: "About"
    url: /about/
  # - title: "Sample Posts"
  #   url: /year-archive/
  # - title: "Sample Collections"
  #   url: /collection-archive/
  # - title: "Sitemap"
  #   url: /sitemap/
```
