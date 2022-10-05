---
layout: single
title: "깃허브 페이지 만들기(3)"
classes: wide
toc : true
toc_sticky: true
categories:
  - 깃허브 페이지 만들기
tags:
  - minimal Mistakes
  - github pages
---

# 1. TOC(Table of ContentsPermalink) 설정하기

TOC 기능은 문서의 제목을 목차로 표시해 주며 오른쪽 사이드에 적용됩니다. 설정 방법은 `_posts` 폴더에 있는 적용하고 싶은 파일(.md)을 아래와 같이 편집하면 됩니다.  

```
---
layout : single
title : "TOC 설정 방법"
toc : true
toc_sticky : true
---

# TOC 목차 만들기  
TOC 목차를 만드는 과정입니다.

## 1. toc : true  
설정 방법은 간단합니다. `toc : true` 를 문서에 추가하면 됩니다.

## 2. toc_sticky : true  
`toc_sticky : true` 설정은 TOC 목차를 고정하는 역할을 합니다.

# 3. 마무리  
`#` 을 이용하여 문서의 제목을 작성할 때, 이 부분들이 TOC 목차에 표시됩니다. 
```

![image](https://user-images.githubusercontent.com/47412229/193985548-9e2cf8fe-645a-4cb8-a0b1-ac29e926b698.png)

## 1-1. TOC 제목 변경하기  

TOC의 기본 제목은 "On This Page"이다. TOC의 제목을 변경하는 방법은 `toc_label : "목차" `를 추가하면 됩니다.  

```
---
layout : single
title : "TOC 설정 방법"
toc : true
toc_label : "목차"
toc_sticky : true
---
```  

![image](https://user-images.githubusercontent.com/47412229/193987787-e6e76fbe-e043-421a-9d80-4099b00c7fae.png)  
  
  
# 2. 댓글 기능 추가하기  

utterances는 깃허브 앱(github issue에 사용)으로 깃허브 계정만 있으면 사용할 수 있습니다. 또한, 마크다운 문법을 사용하여 댓글 작성이 가능합니다. 특히, 플랫폼을 변경해도 기존 댓글을 그대로 가져올 수 있습니다.  

## 2-1. github에 새로운 repository를 생성합니다.(댓글을 위한 repo)  
`blog-comments`라는 이름으로 repo를 생성하고 https://github.com/apps/utterances 사이트로 이동합니다. utterances 앱을 install 버튼을 클릭하여 설치를 진행합니다. Only select repositories를 클릭하고 "(github 계정)/blog-comments" 선택합니다. (예, kig29kig/blog-comments) 사이트 하단의 install 버튼을 클릭하여 설치를 종료합니다.  `_config.yml` 파일을 아래와 같이 편집합니다.  

![image](https://user-images.githubusercontent.com/47412229/194020125-2b81a787-ee33-40d4-81ed-28a98bab859a.png)

##  2-2. 댓글 기능 블로그에 적용하기  
 



  





