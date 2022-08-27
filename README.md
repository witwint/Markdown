# Header
---
# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6
```markdown
# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6
```
<br><br>

# 이텔릭체,두껍게,취소선
---
*이텔릭체*
**두껍게**
***둘다***
~~취소선~~
<u>언더바</u>
```markdowm
*이텔릭체*
**두껍게**
***둘다***
~~취소선~~
<u>언더바</u>
```
<br><br>

# 리스트
---
1. 순서필요
1. 순서필요
	- 순서필요없음
    - 순서필요없음
- 순서필요없음
- 순서필요없음

- 순서필요없음에 사용가능한거
	
    - 대쉬
    * 별표
    + 더하기

```markdown
1. 순서필요
1. 순서필요
	- 순서필요없음
    - 순서필요없음
- 순서필요없음
- 순서필요없음

- 순서필요없음에 사용가능한거
	
    - 대쉬
    * 별표
    + 더하기
```
<br><br>
# 링크
---
[GOOGLE](https://google.com)

[NAVER](https://naver.com "네이버링크설명")

```markdown
[GOOGLE](https://google.com)

[NAVER](https://naver.com "네이버링크설명")
```
<br><br>
# 코드강조
---


```python
print("Hello World!")
```
```markdown
`3개 python
print("Hello World!")
`3개
```
<br><br>

# 표
---
| 값 | 의미 | 기본값 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |

값 | 의미 | 기본값
---|:---:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 **자신**을 기준으로 배치 |
`absolute` | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
`fixed` | **브라우저 창**을 기준으로 배치 |

```markdown
| 값 | 의미 | 기본값 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |

값 | 의미 | 기본값
---|:---:|---:
`static` | 유형(기준) 없음 / 배치 불가능 | `static`
`relative` | 요소 **자신**을 기준으로 배치 |
`absolute` | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
`fixed` | **브라우저 창**을 기준으로 배치 |
```
<br><br>

# 인용문
---
인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요!
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3

```markdown
인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요!
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
>>> 중중첩된 인용문 3
```
<br><br>
# html
---
원시 html 사용가능
<ul>
  <li>il태그 사용</li>
  <li>il태그 사용</li>
  <li>il태그 사용</li>
</ul>
<span hidden> 히든 </span> 숨긴태그

```markdown
<ul>
  <li>il태그 사용</li>
  <li>il태그 사용</li>
  <li>il태그 사용</li>
</ul>
<span hidden> 히든 </span> 숨긴태그
```
<br><br>
# 수평선
---
---
(Hyphens)

***
(Asterisks)

___
(Underscores)

```markdown
---
(Hyphens)

***
(Asterisks)

___
(Underscores)
```
<br><br>

# 줄바꿈
---
  
줄바꿈 기본적으로 enter로 줄바꿈이 지원 안되는경우 스페이스바 두번이 br 태그로 치환됨 또는 그냥 br태그 사용
