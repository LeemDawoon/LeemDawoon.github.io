---
layout: post
title: "Window 에 jekyll 설정"  
categories: log
---

### 1. 루비 설치
- https://rubyinstaller.org/downloads/
- Ruby+Devkit 2.4.4-1 (x64)

### 2. 테마 다운로드  
- https://github.com/codeasashu/hcz-jekyll-blog

### 3. 테마구동에 필요한 루비 패키지 설치
- gem 은 파이썬의 pip 같은 것
~~~ console
> gem install bundler
> cd 프로젝트 경로
> bundle install
> jekyll serve
~~~