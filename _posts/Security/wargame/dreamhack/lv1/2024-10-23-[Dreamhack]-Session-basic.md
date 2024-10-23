---
title: "[Dreamhack] session basic"
categories: ["Wargame", "Dreamhack", "lv1"]
tags: ["wargame", "dreamhack", "web"]
---

# 1. 문제

쿠키와 세션으로 인증 상태를 관리하는 간단한 로그인 서비스입니다.
admin 계정으로 로그인에 설공하면 플래그를 획득할 수 있습니다.

플래그 형식은 DH{...} 입니다.

\[출처] [Dreamhack - session basic](https://dreamhack.io/wargame/challenges/409)


# 2. 해결

#### 1. 변수 session storage 확인

'/admin'로 이동하면 변수 session storage에 저장되어 있는 모든 값을 확인할 수 있는데 이를 이용하여 
프로그램 처음 시작 시 만들어지는 admin 계정의 세션 값을 확인할 수 있다.

![session 확인]({{site.url}}/assets/img/wargame/dreamhack/lv1/admin_세션_확인.png)

#### 2. 쿠키 값 변조

admin 계정의 세션 값을 확인하였으므로 개발자 도구를 이용하여 세션 값을 변경한다.
![쿠키 변조]({{site.url}}/assets/img/wargame/dreamhack/lv1/쿠키_변조.png)

#### 3. '/' 페이지로 이동

admin 계정의 세션 값이 서버로 전달되면 flag 값을 획득할 수 있다.
![플래그 확인]({{site.url}}/assets/img/wargame/dreamhack/lv1/플래그_확인.png)


# 3. 후기
- 소스코드를 분석하고 문제를 푸니 간단하게 풀렸다.

