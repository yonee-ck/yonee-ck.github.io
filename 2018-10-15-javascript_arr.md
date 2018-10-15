# JavaScript Array

## JavaScript 배열에 관한 정리

### 배열
---

* 배열 : 다른 자바스크립트 데이터 값을 하나의 목록으로 만든 것.
* 배열을 사용하는 이유 : 변수 1,000개를 따로 만든다는 것은 종이 한장에 한 가지 단어들만 적는 것.

```javascript
    var Arr = [1, 2, "삼"];
    Arr[5] = "육";
    Arr = [1, 2, "삼", undefined * 2, "육"];
    Arr[4] = undefined;
``` 
```javascript
    //* push 메서드 : 배열 뒷 부분에 원소 추가, 배열 길이 반환
    var Arr = [];
    Arr.push("오조");
    //1
    Arr.push("도레");
    //2
    Arr;
    ["오조", "도레"]
    Arr.length;
    //2
    
    //unshift 메서드 : 배열 시작 부분에 원소 추가(원래 원소들 색인이 뒤로 밀려 변경됨), 배열 길이 반환.
    Arr.unshift("고양이"); 
    //3
    Arr;
    //["고양이", "오조", "도레"]
```

