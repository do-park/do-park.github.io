---
layout: post
title:  "[웹 크롤링] This version of ChromeDriver only supports Chrome version 83"
date:   2020-04-25

---

<p class="intro"><span class="dropcap">웹</span>크롤링을 공부하기 위해 selenium이 필요했고, chromedriver를 설치했는데 다음과 같은 에러가 발생했다.</p>

`This version of ChromeDriver only supports Chrome version 83`

- 에러의 원인: 현재 사용중인 chrome의 버전과 chromedriver의 버전이 맞지 않는 경우 발생
- 해결: 현재 사용중인 chrome의 버전과 동일 버전의 chromedriver 설치



### Chrome 버전 확인

크롬 우측 상단의 [메뉴 > 도움말 > Chrome 정보]에서 확인 가능



### ChromeDriver 설치

https://chromedriver.chromium.org/downloads

상단의 chromedriver 사이트에서 Chrome 버전에 맞는 driver를 설치한 후, 사용하고자 하는 파일이 있는 폴더로 이동

나의 경우에는 Chrome은 81 버전을 사용중이었고, ChromeDriver는 83 버전을 사용중이었다.

```bash
$ chromedriver --version
```

설치 후에는 상단의 명령어를 총해 chromedriver의 버전을 확인할 수 있다.