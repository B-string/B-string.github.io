---
layout: post
categories: ["Jekyll"]
title: "[Jekyll] FrontMatter 설정하기"
tags: ["Jekyll", "FrontMatter"] 
---

# 목차

1. 프론트매터?
2. 프론트매터 설정

---

# 1. 프론트매터?
마크다운 문서에서 메타데이터(metadata) 역할을 하도록 만들어진 특별한 규칙으로 메타데이터를 이용하여 파일을 검색하고 분류할 수 있는 것처럼 프론트매터를 통해 마크다운 문서를 검색하고 분류하는데 활용할 수 있다.


# 2. 프론트매터 설정
프론트매터는 YAML 형식으로 작성되며 사전에 정의된 변수를 통해서 값을 설정하거나 사용자 정의 변수를 직접만들어 사용할 수 있다.

```md
---
layout: post
categories: [Git, Jekyll] # category, categories 배열을 통해서 카테고리의 깊이를 설정할 수 있다.
title: 카테고리 페이지 만드는법
---
```

참고: [Jekyll-FrontMatter](https://jekyllrb.com/docs/front-matter/)



