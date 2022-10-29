# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

아무거나 쓰면 걍 문장이다
줄바꿈이 안되고 연속해서 출력된다.

# 줄바꿈(Line Breaks)

줄바꿈을 하는방법은  
띄어쓰기 두번을하면 된다.  
하지만 인식 못하는 환경이 있기 때문에
</br> br 태그를 직접 넣어주는게 좋다.

# 강조(Emphasis)

_양쪽에 _를 넣으면 이텔릭체가 된다_

**두껍게 하려면 아스테리크 두번 넣어주자**

**_이텔릭 + 두껍게_**

~~취소선~~

<u> 밑줄 </u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록(탭 두번을 하면 서브 항목으로 들어감)
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록 
1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록(탭 두번을 하면 서브 항목으로 들어감)
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com"> GOOGLE </a>

  같은거임 

[GOOGLE](https://google.com)

<a href="https://naver.com" title = "NAVER로 이동" target="_blank"> NAVER </a>

  같은거임, 새창에서 열기 _black 는 못씀.

[NAVER](https://naver.com "NAVER로 이동")

# 이미지(Images)

![HEROPY](https://avatars.githubusercontent.com/u/16679082?s=48&v=4)

링크까지 추가하려면

[![HEROPY](https://avatars.githubusercontent.com/u/16679082?s=48&v=4)](https://google.com)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어사전)
>> 인용문도 중첩가능
>>> 들어가는 구조

# 인라인(inline) 코드 강조

CSS에서 'background' 혹은 'background-image' 속성으로 요소에 이미지 삽입 가능

# 블록(block) 코드 강조
백픽? 물결표 등 
```html

<a href="https://naver.com" title = "NAVER로 이동" target="_blank"> NAVER </a>

```

```javascript
  function func() {
    var a = 'aaa';
    return a;
  }
```

```css
  .div { 
    background-color: red;
  }
```

```plaintext
 글자강조만 할때
```