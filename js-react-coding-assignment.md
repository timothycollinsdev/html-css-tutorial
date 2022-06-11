# JavaScript and React JS Coding assignment

## Q. 1
Write a JavaScript program to check two given numbers and return true if one of the number is 50 or if their sum is 50

> Answer:
```js
function test50(x, y) 
{
  return ((x == 50 || y == 50) || (x + y == 50));
} 
```

## Q. 2
Which value does x have after execution of the following code?
```js
let x = 3;
x++;
x = x * 2;
x--;
```
> Answer: 7

## Q. 3
Write a function `addWithSurcharge` that adds two amounts with surcharge. For each amount less than or equal to `10`, the surcharge is `1`. For each amount greater than `10`, the surcharge is `2`.
> Answer: 
```js
function addWithSurcharge(a, b) {
  let surcharge = 0;
  if (a <= 10) {
    surcharge = surcharge + 1;
  } else {
    surcharge = surcharge + 2;
  }
  if (b <= 10) {
    surcharge = surcharge + 1;
  } else {
    surcharge = surcharge + 2;
  }
  return a + b + surcharge;
}
```

## Q. 4
Enter the correct ReactDOM method to render the React element to the DOM.
```js
ReactDOM.`{your-answer}`(myElement, document.getElementById('root'));
```
> Answer: `render`

## Q. 5
Complete this component which uses properties

```js
function Person(`{answer-one}`) {
  return <h1>Hi, I'm {`{answer-two}`.name}!</h1>;
}

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(<Person name="Jesse"/>);
```
> Answer: `props` for both the answers 
