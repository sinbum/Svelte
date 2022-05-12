------------------------------------------------
[heropy svelte practice](https://heropy.blog/2019/09/29/svelte/)

# Svelte Core API

## 라이프 사이클  
  5개의 생명주기, 컴포넌트가 연결되고 해제되는 컴포넌트의 생명주기.  
  1. onMount, onDestroy, beforeUpdate, afterUpdate
  2. tick
  3. 라이프 사이클 모듈화
## 기본 보간
  1. 원시 HTML
  2. 디버그
## 반응성
  1. 할당
  2. 반응성 구문
  3. 사용 패턴  
## 클래스와 스타일
  1. 속성 바인딩
    - 사용 패턴
  2. 스타일 유효범위와 전역화
  3. @kyfrmaes 전역화
## 요소 바인딩
  1. 일반 요소
  2. 입력 요소  [링크](https://svelte.dev/repl/3aca814fe08e49f08a42a7db3baed19a?version=3.29.4)
      input.type : text,number,range,checkbox,checkbox,checkbox/group(다중선택)  
      textarea/value  
      select : option
  4. 편집 가능 요소
## 조건 블록 [랑크](https://svelte.dev/repl/7d2cffd5f49a4b279cfe720c96f51798?version=3.29.4)
  1. 사용 패턴
## 반복 블록  [링크](https://svelte.dev/repl/b1f53749f8014e9c82fb8ea7d5d26825?version=3.29.4)
  1. key
  2. 사용 패턴  
기본,순서별,아이템 고유화(key),빈 배열 처리(else),구조 분해 (destructuring),2차원 배열, 나머지 연산자(Rest), 객체 데이터

## 키블록 [링크](https://svelte.dev/repl/454f0523049045e39dd647bac3c5fe05?version=3.31.0)
  

## 비동기 블록 [링크](https://svelte.dev/repl/6f025fe7d28441c9a8267a6be38ea8f9?version=3.29.4)
[OMDb API키 발급](http://www.omdbapi.com/)
  1. 대기(pending)   : '이행'하거나 '거부'되지 않은 초기 상태
  2. 이행(fulfilled) : '연산'이 성공적으로 완료됨
  3. 거부(rejected)  : '연산' 거부
  
    
  
  
  


 
