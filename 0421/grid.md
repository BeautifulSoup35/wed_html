안에있는 구성요소
부모를 그리리드(grid)로 설정하기
div으로 설정

grid란
행의 갯수와 열의 갯수를 설정해 위치를 선정시킨다다

```
<div class = "container">

//열 갯 수수        grid-template-columns:  100px 200px 300px;

```

갯수가 정적이 아니라 동적으로 바뀔대 행의 갯수를 어떻게 조정할까

```
        grid-template-columns: 100px 200px; //고정된 열
        grid-auto-row: 100px ;// 자동인 행부분

        grid-template-columns: 1fr 1fr 1fr; //비율 1:1:1

        grid-template-columns: 1fr 1fr 1fr 1fr 1fr 1fr;
    ->  grid-template-columns: repeat(2, 1fr);



```

#grid 레이아웃 사용하기 grid - 3

```
display: grid;
grid-auto-rows: minmax(100px, auto);//최소 100에서 나머지는 auto로로
```

#grid-4

```
        gap: 20px 50px;
//행과 열열
```

#grid - 6
위치 조정정

```
        grid-column: 1 / 4; 1번 부터 4번
        grid-column: 1 / 2; 1번부터 2번
        grid-column: 1 / -1; 처음부터 끝까지지


```

#responsive

```
@media screen{

      }

          display: block;//원래 실행되는대로로
```
