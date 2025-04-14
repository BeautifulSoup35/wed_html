오늘 강의
display: flex;
화면크기가 달라진다고 해서 모션이 달라지진 않는다

정렬방식 변경
```
#opt1 {
        flex-direction: row;-> 왼쪽에서 오른쪽으로 정렬
      }
      #opt2 {
        flex-direction: row-reverse;-> 오른쪽에서 왼쪽으로 정렬
      }
      #opt3 {
        flex-direction: column; -> 위애서 아래
      }
      #opt4 {
        flex-direction: column-reverse;-> 밑에서 위로
      }
```
```
flex-wrap: wrap;//길 경우 두 줄로 내림 -> 내가 조절한 화면 비율을 해당안됨
flex-wrap: nowrap;

justify-content: center;//옵션에서 됨
        align-content: right;//옵션에서 안됨 왜??
```
      
