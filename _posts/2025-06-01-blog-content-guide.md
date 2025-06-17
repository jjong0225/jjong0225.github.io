---
layout: post
title: "블로그 가이드"
date: 2024-05-01 00:32:13
description: this is what included tabs in a post could look like
tags: formatting code
categories: sample-posts
tabs: true
---


# al-folio 블로그 마크다운 활용 가이드

이 문서는 al-folio(Jekyll) 블로그의 `_posts` 폴더에 저장된 다양한 샘플 글들의 마크다운 문법, 코드, 이미지, 표, 인용구 등 실제 활용 예시를 한 곳에 정리한 가이드입니다.

---

## 1. 제목과 본문
```markdown
# 대제목(H1)
## 소제목(H2)
### 더 작은 제목(H3)
본문 내용은 이렇게 작성합니다.
```

## 2. 리스트
```markdown
- 순서 없는 리스트
  - 하위 항목
- 또 다른 항목

1. 순서 있는 리스트
2. 두 번째 항목
```

## 3. 코드 블록
```markdown
```python
print("Hello, world!")
```
```

## 4. 인라인 코드
```markdown
`코드처럼 보이는 텍스트`
```

## 5. 이미지 삽입
```markdown
![이미지 설명](../assets/img/sample.jpg)
```

## 6. 링크
```markdown
[al-folio GitHub](https://github.com/alshedivat/al-folio)
```

## 7. 인용구
```markdown
> 이것은 인용구입니다.
```

## 8. 표(Table)
```markdown
| 헤더1 | 헤더2 |
|-------|-------|
| 셀1   | 셀2   |
| 셀3   | 셀4   |
```

## 9. 수식(MathJax)
```markdown
인라인 수식: $E=mc^2$

블록 수식:
$$
\int_0^1 x^2 dx = \frac{1}{3}
$$
```

## 10. 태그와 카테고리
```markdown
---
title: "글 제목"
date: 2024-06-01
categories: [blog]
tags: [태그1, 태그2]
---
```

---

이 가이드는 `_posts` 폴더의 다양한 샘플 글에서 실제로 사용되는 마크다운 문법과 활용 예시를 한 곳에 모은 것입니다. 새로운 글을 작성할 때 참고하시면 좋습니다.
