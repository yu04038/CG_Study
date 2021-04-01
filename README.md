# 컴퓨터 그래픽스 공부


### 최근 수정 : 21/04/01
#### postscipt에도 스택이 존재한다. 
* count
>스택의 깊이를 스택의 맨 위에 올려둔다. 예를 들어 스택의 맨 밑에서부터 0, 1, 2, 3, 4가 들어있다고 가정한다면, 5가 스택의 맨위에 올라오게 된다.
  
* clear
>스택의 모든 데이터를 제거한다.

* pop
>가장 최근에 넣었던 값을 뺀다.

* dup
>스택의 가장 위의 객체를 복사하여 스택에 추가시킨다.
  
* stack, pstack
>스택 확인!

* ==
>해당 값을 꺼내서 print. 단순히 display해주는 것이 아니라 기존 stack에 pop을 해서 보여주는 것이므로 stack에서는 값이 사라짐.


* exch
>스택 상위 2개의 요소의 위치가 교환된다.

* repeat
>스택에 반복해서 넣는다. ex) 5 {10} repeat -> 10 10 10 10 10

* for 문
> ex) 1 1 10 {} for -> 1부터 시작해서 10까지 1을 증가시키면서 스택에 집어넣기

* conditional statement
  - bool {...} if  
    > condition(bool) - eq, ne, gt, lt, ge, le  
      스택 맨위에 있는 두개를 비교한다.   
      <img src="conditional.png" width="300px" height="200px" title="px(픽셀) 크기 설정" alt="conditional statement"></img><br/>

  - bool {op1} {op2} ifelse
    > true일 경우 op1을 실행하고, false일 경우 op2를 실행한다.
