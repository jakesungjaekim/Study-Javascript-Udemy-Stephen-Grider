## Running Code in the console
1. Chrome Open
2. cmd+Option+J

## Introducting Numbers

#### Primitive Type [원시유형]

##### Number

- 양수,음수,소수,정수 ... 
- Simple Operation 가능 ( + , - , * , / , % , **), 띄워쓰기는 연산에 영향을 주지 않는다.
- 우선 순위 적용 ( * , / > + , -)
```js
4 + 2 //6
4 - 2 //2
4 * 2 //8
4 / 2 //2 
4 % 2 //0 
2 ** 3 //8
9 - 3 * 2 // 3
(9 - 3) * 2 // 12
```
##### NaN & Infinity

```js
0/0 // NaN
NaN + 5 // NaN
1/0 // infinity
-1/0 // -infinity
```

##### Numbers Quiz
```js
1.5 + 1.5 * 2 // 4.5
(10%6) ** 2 // 16
200 + 0/0 // NaN
```

## Variables & Let
변수는 라벨을 붙인 것과 같습니다. 값을 저장합니다. 변수는 업데이트할 수 있습니다.
JS에서 변수를 저장할 때 예약어(let, document ...)들은 피해야합니다.
작명은 camleCase를 사용하는 것이 좋습니다.(국제컨벤션)
let 을 통해 선언했다면, let으로 재 선언할 수 없습니다.
```js
let apple = '애플'
let apple = 'apple' // Error
apple = 'apple' // Update
apple // 'apple'

```

```js
let someName = value;
someName // value
let age = 72;
age // 72

let hens = 4
let roosters = 2

hens + roosters // 6

hens = hens - 1
hens // 3

age = 18;
age // 18

let avgRating = 9.7;
avgRating // 9.7
```

## Unary Operator (단항연산자)
```js
let score = 0;
score = score + 10;
score // 10
score += 1;
score // 11
score += 10;
score // 21

score -= 100;
score // -79
score = 150
score // 150

let bonusMult = 3

score *= bonusMult;
score // 450

let counter = 0;
counter++
counter // 1
counter++
counter // 2
counter++
counter // 3
counter++ 
counter // 4
counter--
counter // 3
```

## Introducing Const 
const로 선언한 변수는 Update 할 수 없습니다.

```js
const age = 17;
age = age + 1 // error

const peopleCount = 10

let peopleCount = 3 // error
```

## The legacy of Var
옛날에 변수를 선언하던 방법, var
최근에는 호이스팅때문에 사용하지 않는다.

```js
var eggs = 12
eggs // 12

eggs++
eggs // 13

eggs = 0;
eggs // 0
```

## Variables Quiz

```js
let eggCount = 42
eggCount + 2
eggCount // 42

const rating = 7.5 
rating = 8 //error

let wind_speed = 76
wind_speed += 5
wind_speed--;
wind_speed // 80


```

