# 프로그램

- 프로그램은 자료구조와 알고리즘으로 이루어진다.

## 자료구조

- 자료구조는 데이터가 어떤 구조로 저장되고 어떻게 사용되는지를 나타낸다.
- 가장 단순한 자료구조는 변수
- 다른 자료구조는 배열

### 세 개의 데이터 평균

- 변수

```javascript
let a = 87;
let b = 70;
let c = 100;

let average = (a + b + c) / 3;
```

- 배열

```javascript
let arr = [87, 70, 100];

let average = 0;

for (let i = 0; i < arr.length; i++) {
  average += arr[i];
}

average /= arr.length;
```

- 데이터를 변수에 저장하는지, 배열에 저장하는지에 따라서 처리방법이 달라지는데 즉 자료구조에 따라서 처리 방법이 달라진다.

🔎 변수와 배열이 저장된 모양도 다르고 사용 방법도 다르기 때문 🔎

### 네 개의 데이터 평균

- 변수

```javascript
let a = 87;
let b = 70;
let c = 100;
let d = 55;

let average = (a + b + c + d) / 4;
```

- 배열

```javascript
let arr = [87, 70, 100, 55];

let average = 0;

for (let i = 0; i < arr.length; i++) {
  average += arr[i];
}

average /= arr.length;
```

- 변수를 추가하고 계산하는 코드도 수정해야하지만 배열은 데이터만 넣으면 된다.
- 자료구조에 따라서 처리 방법이 달라질 뿐 아니라 코드가 더 단순해 질 수도 있다.
