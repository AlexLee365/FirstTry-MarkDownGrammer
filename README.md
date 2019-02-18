# Markdown 문법 사용 및 정리
***

## Markdown 이란?
웹에서 글을 쓰는 사람들을 위해 텍스트를 HTML로 변환해주는 툴
읽기쉽고 쓰기편한 순수한 텍스트 형식으로 글 작성 후 HTML 로 변환

***

## 헤더사용
### 헤더3
#### 헤더4
##### 헤더5
###### 헤더6

***

## 글자체변경

*이탈릭체사용*
_이탈릭체 사용_

**볼드체사용**
__볼드체사용__

강조하고싶을때 **강조** 이렇게사용

***

## 번호, 목록 매기기
1. 하나
2. 둘
3. 셋

### 과일
- 사과
  - 빨간색
  - 아침에 먹는게 좋음
- 바나나
  - 노란색
  - 길쭉함
- 포도
  - 파란색
  - 알맹이
  
### 작업목록을 완료.비완료 로도 구분 가능
- [x] 1차 계획 (완료됨)
- [ ] 2차 계획 (비완료)

***
 


## 타인의 말을 인용할 시
> There is no reason not to follow your heart. 너의 마음의 뜻을 안 따라갈 이유가 없다
> -Steve jobs

***

## 코드 입력 시 (인용 시) 가시화하는 방법
1. 네 칸 들여쓰기 하기     
  if (isAwesome){
  return true
  }
    
2. 코드 펜싱
    
```
if (isAwesome){
  return true
}
```
    
3. 구문 강조 (언어를 포함시켜 작성)
```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

***

## 테이블 만들기
table1 | table2
-------|-------
content1 | content2
content3 | content4

***

## 취소 선
~~이 글은 삭제함~~

***

## URL 자동링크
http://www.github.com/

***

## 그림이모티콘 사용
:laughing:
:smiley:
:kissing_heart:

***

## 이미지사용
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
