---
layout: single
title: "깃허브 페이지 만들기(2)"
classes: wide
toc : true
toc_sticky: true
categories:
  - 깃허브 페이지 만들기
tags:
  - minimal Mistakes
  - github pages
---

# 깃허브 페이지의  헤더 메뉴 구성하기  
## 1. About 페이지 
깃허브 페이지의 헤더 메뉴 구성은 `_pages` 폴더를 만들고 메뉴에 들어갈 내용의 파일을 작성합니다. 우선, `_data` 폴더의 navigation.yml 파일을 열고 아래와 같이 수정합니다. About 메뉴를 만들고 링크를 설정 후 `_pages` 폴더에 about.md 파일을 작성하면 됩니다.    
  
```
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

![image](https://user-images.githubusercontent.com/47412229/193764827-fa333cb2-02d0-481e-9680-569fd6e3d48a.png)

about.md 파일을 만들때, `permalink: /about/` 추가해야, 링크가 연결됩니다.  

## 2. Tags 페이지  
Tag 헤더 메뉴 또한 `_data` 폴더의 navigation.yml 파일을 열고 아래와 같이 수정합니다.

