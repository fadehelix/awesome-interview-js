## Question: Explain how this function works
### Details:
- `field` parameter is a 2D array e.g. `[[1,0,0], [0,0,0], [0,0,0]]`
- funtion returns tuple with two elements e.g. `[1,0]`
```
const mineLocation = field =>
  (idx => [idx, field[idx].indexOf(1)])
  (field.findIndex(val => val.includes(1)));
```
Context: https://www.codewars.com/kata/reviews/528d9c38cc451c8fc900061a/groups/5ff705c6118f8e0001764f6a
