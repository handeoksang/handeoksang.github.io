---
title:  "github.io 블로그 시작하기"
excerpt: "GitHub Blog 서비스인 github.io 블로그 시작하기로 했다."

categories:
  - Blog
tags:
  - Blog
last_modified_at: 2024-04-17T08:06:00-05:00
---

GitHub Blog 서비스인 github.io 블로그 시작하기로 했다.
GitHub Blog 서비스의 이름은 Pages이다.

Pages가 다른 블로그 플랫폼 보다 편한 것 같아서 마음에 든다.
다른 사람들도 같이 많이 사용했으면 좋겠다는 생각이 든다.

YFM에서 정의한 제목을 이중 괄호 구문으로 본문에 추가할 수 있다.
이 글의 제목은 {{ page.title }}이고
마지막으로 수정된 시간은 {{ page.last_modified_at }}이다.  

--------
텍스트 줄바꿈  
기본적인 텍스트 표기 방식이다.  
마크다운은 줄바꿈을 인식하지 않는다.  

줄바꿈을 하기 위해서는 라인 끝에 스페이스를 2번    
표기해야 한다.  
  
여러가지 강조 표시가 존재한다. 첫번째로 *single asterisks*,  
두번째로 _single underscores_, 세번째로 **double asterisks**,  
네번째로 __double underscores__, 다섯번째로 ~~cancelline~~가 있다.  
  
# This is a H1  
## This is a H2  
### This is a H3  
#### This is a H4  
##### This is a H5  
###### This is a H6  
인용문을 사용할때는 > 블럭 인용 문자를 사용하면, 단계별 깊이를 지원한다.  
> This is a blockqute.  
> This is a first blockqute.  
>> This is a second blockqute.  
>>> This is a third blockqute.  

정렬 목록
1. 봄
2. 여름
3. 가을
4. 겨울 
 
비정렬 목록
* 과자
  * 라면
    * 사탕
+ 과자
  + 라면
    + 사탕
- 과자
  - 라면
    - 사탕

코드 인용
```
function test() {
  console.log("notice the blank line before this function?");
}
```
코드 인용(언어 별 문법 하이라이트)
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

```c
int main() {
  int y = SOME_MACRO_REFERENCE;
  int x = 5 + 6;
  cout << "Hello World! " << x << std::endl();
}
```

```cpp
int main() {
  int y = SOME_MACRO_REFERENCE;
  int x = 5 + 6;
  cout << "Hello World! " << x << std::endl();
}
```
```python
s = "Python syntax highlighting"
print s
```
모두 수평선을 만드는 여러가지 표기법이다.
* * *
***
*****
- - -
---------------------------------------


- 링크 표시법 : [Title](link)  
[Google 페이지 링크](https://google.com)
주소 직접 표시법  
<https://google.com>

이미지 삽입  
![](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg)  
![](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg){: .align-center}  
![키보드 사진](https://devinlife.com/assets/images/bio-photo-keyboard-small.jpg "내 키보드 사진"){: .align-center}  

표 만들기  
표 내용 중앙 정렬    

| 항목 | 가격 | 개수 |  
|:---:|:----:|:----|  
| 라면 | 800원 | 10개 |  
| 과자 | 900원 | 20개 |  


표 내용 좌측 정렬-중앙 정렬-우측 정렬  

| 항목 | 가격 | 개수 |
|:----|:----:|----:|
| 라면먹자 | 800,000,000원 | 1000,000,000개 |
| 과자먹으면 | 9000,000원 | 200,000개 |

표 내용 좌측 정렬-좌측 정렬-좌측 정렬   
 
| 항목 | 가격 | 개수 |
|:----|:----|----|
| 라면먹자 | 800,000,000원 | 1000,000,000개 |
| 과자먹으면 | 9000,000원 | 200,000개 |

