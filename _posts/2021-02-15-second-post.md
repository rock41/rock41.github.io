---
title: "MarkDown 표기법 따라하기"
excerpt: "GitHub Blog 사용을 위한 MarkDown 표기법 공부"

categories:
 - Blog
tags:
 - markdown
last_modified_at: 2021-02-15T23:37:00
---

기본적인 텍스트 표기 방식이다.
마크다운은 줄바꿈을 인식하지 않는다.  

줄바꿈을 하기 위해서는 라인 끝에 스페이스를 2번  
표기해야 한다.

여러가지 강조 표시가 존재한다. 첫번째로 *single asterisks*,
두번째로 _single underscores_, 세번째로 **double asterisks**,
네번째로 __double undersocres__, 다섯번째로 ~~cancelline~~가 있다.

# This is a H1   
## This is a H2   
### This is a H3   
#### This is a H4   
##### This is a H5   
###### This is a H6   

> This is a blockqute.   

> This is a first blockqute.   
>> This is a second blockqute.   
>>> This is a third blockqute.   

1. 봄   
2. 여름   
3. 가을   
4. 겨울   

* 과자   
 * 라면   
  * 사탕   


+ 과자   
 + 라면   
   + 사탕   

- 과자   
 - 라면   
  - 사탕   


```java
public static void main() {
  int y = 1000;
}
```   

- 링크 표시법 : [Title](link)
[Google 페이지 링크](https://google.com)   

<https://google.com>   

이미지 삽입   
![](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg)   
![](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg){: .align-center}   
![키보드 사진](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg "내 키보드 사진"){: .align-center}   

표 내용 중앙 정렬   
| 항목 | 가격 | 개수 |
|:---:|:----:|:----|
| 라면 | 800원 | 10개 |
| 과자 | 900원 | 20개 |

표 내용 좌측 정렬-중앙 정렬-우측 정렬   
| 항목 | 가격 | 개수 |
|:----|:----:|----:|
| 라면 | 800원 | 10개 |
| 과자 | 900원 | 20개 |


