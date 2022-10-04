---
layout: #single
title: "깃허브 페이지 만들기"
toc : true
toc_sticky: true
tags:
  - minimal Mistakes
  - github pages
---

# Github pages 블로그 만들기
지킬(Jekyll)은 정적 사이트 생성기로 일반 텍스트를 정적 웹사이트 및 블로그로 변환합니다. Github Pages는 Jekyll을 기반으로 무료로 Gihub를 사용하여 사이트를 배포할 수 있습니다.  
[공식 홈페이지](https://jekyllrb.com/)   

***

# 지킬(Jekyll) 테마
Jekyll 테마는 다른 사용자들이 이미 구성해서 배포한 template이며, 많은 무료 template이 공개되어 있습니다. 무료 테마들 중에서 인기있는 Minimal Mistakes 테마를 적용해서 블로그를 만들어 봅시다.  

[Github minimal Mistakes 템플릿](https://github.com/mmistakes/minimal-mistakes)  

***

# 사전 작업
Github 계정이 있어야 합니다. Github에 대한 내용은 다시 준비하겠습니다. 우선은 구글 검색 등을 통해서 가입하고 진행하면 됩니다.  

***

# 1. minimal-mistakes 테마 적용하기
깃허브 레포(https://github.com/mmistakes/minimal-mistakes) 에 접속하여 우측 상단의 fork 버튼을 클릭합니다.  
fork한 repository 명칭을 **(본인의 github 계정이름).github.io** 로 변경합니다.  
예) kig2929kig.github.io     

![image](https://user-images.githubusercontent.com/47412229/193723245-d98ca65f-473a-48c3-94e2-a9fbf3aa533f.png)  

***

# 2. _config.yml 편집

## 테마 스킨
```md
minimal_mistakes_skin    : "air" # "air", "aqua", "contrast", "dark", "dirt", "neon", "mint", "plum", "sunrise"
```   
[테마 스킨 목록](https://mmistakes.github.io/minimal-mistakes/docs/configuration/#skin)  

![image](https://user-images.githubusercontent.com/47412229/193725023-1a717e25-393d-4ab9-af24-5d59e4102430.png)


## 사이트 설정

```md
# Site Settings
locale                   : "ko-KR"
title                    : "사이트 제목 표시줄"
title_separator          : "-"
subtitle                 : # site tagline that appears below site title in masthead
name                     : 이름 # "Your Name"
description              : 어마 무시한 웹 사이트 # "An amazing website."
url                      : "https://kig29kig.github.io" # the base hostname & protocol for your site e.g. "https://mmistakes.github.io"
baseurl                  : # the subpath of your site, e.g. "/blog"
repository               : "kig29kig/kig29kig.github.io" # GitHub username/repo-name e.g. "mmistakes/minimal-mistakes"
teaser                   : # path of fallback teaser image, e.g. "/assets/images/500x300.png"
logo                     : # path of logo image to display in the masthead, e.g. "/assets/images/88x88.png"
masthead_title           : # overrides the website title displayed in the masthead, use " " for no title
```   

![image](https://user-images.githubusercontent.com/47412229/193730602-e3dd7235-a825-481a-bb1a-3d6570bec9a0.png)  

name, description은 웹 사이트에 대한 정보를 입력하는 곳으로 실제 보여지는 웹사이트에서는 나타나지 않습니다.  

## 사이트 작성자  

```md
# Site Author
author:
  name             : "INGOO KANG"
  avatar           : "https://avatars.githubusercontent.com/u/47412229?v=4" # path of avatar image, e.g. "/assets/images/bio-photo.jpg"
  bio              :  "상처 많은 꽃잎들이 가장 향기롭다."
  location         : "Republic of Korea"
  email            : "kig2929kig@gmail.com"
  links:
    - label: "kig2929kig@gmail.com"
      icon: "fas fa-fw fa-envelope-square"
      # url: "mailto:kig2929kig@gmail.com"
    - label: "Website"
      icon: "fas fa-fw fa-link"
      # url: "https://your-website.com"
    - label: "Twitter"
      icon: "fab fa-fw fa-twitter-square"
      # url: "https://twitter.com/"
    - label: "Facebook"
      icon: "fab fa-fw fa-facebook-square"
      # url: "https://facebook.com/"
    - label: "GitHub"
      icon: "fab fa-fw fa-github"
      # url: "https://github.com/kig2929kig"
    - label: "Instagram"
      icon: "fab fa-fw fa-instagram"
      # url: "https://instagram.com/"

```


