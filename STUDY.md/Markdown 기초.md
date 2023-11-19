# Markdown 기초
Markdown 이란 마크업 언어의 일종
## 제목 (heading)
제목은 **#** 통해 표현한다.

#의 갯수로 제목의  레벨을 표현 가능하며 1~6까지 사용할 수 있다.

# H3
## H4
### H5
#### H6
##### H7
###### H8

## 문단 (Paragraphs)
문단입니다.
엔터 한번으로는 줄이 안바뀝니다.

엔터 두번이 되어야 줄이 바뀌고,   
다음 문단으로 인식합니다.

## 줄바꿈
새로운 문단이 아닌, 문단 내부에 엔터를 추가하고 싶다면   
공백 두개와 함께 해주면 줄이 바뀝니다.

## 글 강조
- 굵은 글씨를 표현하고 싶다면 별을 두개(**별을 두개**) 넣어주세요.
- 기울인 글씨는 별 하나(*별 하나*)로 만들 수 있습니다.
- 굵으면서 기울은 글씨는 별이 세개 (***별이 세개***) 필요합니다.

## 인용문
아래는 인용문을 나타냅니다.

> A quotation is the repetition of a sentence, text that someone has said or written.

## 목록
- 순서를 가진 목록
    1. 일어나기
    2. 세수하기
    3. 컴퓨터 켜기
    4. 코딩

- 순서가 없는 목록
    - JAVA
    - Python
    - JavaScript

- 하위 목록
    - 백준
    - 프로그래머스


## 코드
마크다운에서 코드를 표현하고 싶다면, `print("Hello World")` 라고 써봅시다.

만약에 정말 만약에 백틱을 써야한다면 `` ` `` 처럼 해주면 됩니다.

여러줄의 코드를 표현하고 싶다면, 세개의 백틱을 활용할 수 있습니다.
```
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello JAva!!!");
    }
}
```
아래코드는 java 코드입니다.
```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello JAva!!!");
    }
}

```

## 가로줄

아래는 가로줄로 표현됩니다.

---
내용을 구분할 때 유용합니다.

## 링크
가장 간단한 링크 생성법입니다. <https://www.naver.com>

문구에 링크 추가  
[네이버](https://www.naver.com)라는 글귀에 네이버 링크를 달았습니다.

## 이미지 
이미지는 아래처럼 넣어줄 수 있습니다.
![컴퓨터 이미지](computer.png)

웹이미지도 넣어줄 수 있습니다.
![Java](https://upload.wikimedia.org/wikipedia/commons/thumb/7/79/Spring_Boot.svg/120px-Spring_Boot.svg.png)


