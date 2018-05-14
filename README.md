# Front-end Developer Interview Tasks

This file contains tasks Front-End interview.

I hope, these tasks help fresh developers prepare to interview and for interviewer find potential candidates.

## Tasks on Number

1. Write a function `isPrime()`, which return `true` or `false` if number is prime.

  ```js
  console.log(isPrime(11)) // true
  ```

2. Write a function `factorial()`, which return factorial of the number passed to it.

  ```js
  console.log(factorial(4)) // 24
  console.log(factorial(7)) // 5040
  ```

3. Write a function `fibonacci()`.
    >The Fibonacci sequence is a series of numbers where a number is found by adding up the two numbers before it. Starting with 0 and 1, the sequence goes 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, and so forth. Written as a rule, the expression is xn = xn-1 + xn-2.

  ```js
  console.log(fibonacci(9)) // 21
  ```

4. Write a function `findNextSquare(sq)`, which return the square of the next number and -1, if  the square root of a number is not an integer
  ```js
  console.log(findNextSquare(144)) // 169
  console.log(findNextSquare(155)) // -1 because sqrt(155) = 12.44... (not integer number)
  ```

----

## Tasks on Array

1. Write functions `some()` & `every()` which work as functions `Array.prototype.some()` and `Array.prototype.every()`.

  ```js
  console.log(every([NaN, NaN, NaN], isNaN)) // true
  console.log(every([NaN, NaN, 4], isNaN)) // false
  console.log(some([NaN, 3, 4], isNaN)) // true
  console.log(some([2, 3, 4], isNaN)) // false
  ```

2. Write a function `groupItems()`, which returns an object with keys `even` & `odd` and values are arrays with corresponding numbers.

  ```js
  console.log(groupItems([100, 3, 4, 5, 1, 6, 7])) // { even: [100, 4, 6], odd: [3, 5, 1, 7] }
  ```

3. Write a function `reduce()`, which work as function `Array.prototype.reduce()`, and find sum in array `const items = [1,2,3,4,5,6,7,8,9]`

  ```js
  console.log(reduce(items)) // 45
  ```

4. Write a function that removes duplicate values from an array.

  ```js
  console.log(removeDuplicates([1, 3, 7, 1, 3, 9, 8, 7])) // [1, 3, 7, 9, 8]
  ```

5.  Write a function that returns the common values of two arrays.

  ```js
  console.log(commonValues([3, 4, 6, 3, 1], [5, 10, 7, 1, 3, 9, 8, 7])) // [3, 1]
  ```

6. Write a function that returns the distinct values of two arrays.

  ```js
  console.log(distinctValues([3, 4, 6, 3, 1], [5, 10, 7, 1, 3, 9, 8, 7])) // [4, 6, 5, 10, 7, 9, 8]
  ```

7. Write a function which creates an array with defined size and fills it with random values.

  ```js
  function generateArr(arrSize) {...}
  ```

8. Write your own implementation of Array.prototype.includes() method.

9. You have an array of arrays of unknown deep level. Create a `flatten` function which converts that array to flat array.

  ```js
  console.log(flatten([[1, 2], 5, [ [1], [ [2], [3], [4, 5, 6, 7] ] ], [6, 7]]))
  ```

10. Sort users by age in desc order (bigger is the first)

  ```js
  const users = [{ name: 'John', age: 10 }, { name: 'Peter', age: 12 }, { name: 'Serjio', age: 16 }]
  ```

----

