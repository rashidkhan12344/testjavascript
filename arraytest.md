#### // Array Questions

## Question 1

## Create an array with three elements and print out the second element.

```
let array = [2, 4, 6];
array = array[1];
console.log(array);
```


## Question 2
 ## Create an array with five elements and print out the length of the array.

```
let array = [2, 3, 5, 6, 7];
array = array.length;
console.log(array);
```

## Question 3
## Create an array with four elements and print out each element using a for loop.

```
let array = [2, 4, 6, 8];
for (let i = 0; i < array.length; i++) {
console.log(array[i]);
}
```

## Question 4
## Create an array with six elements and print out each element using a forEach loop.

```
let array = [2, 3, 5, 6, 7, 9];

array = array.forEach(number);

function number(num) {
{
console.log(array);
}
}
```

## Question 5
## Create an array with three elements and add a fourth element to the end of the array.

```
let array = [2, 4, 6];
array.push(8);
console.log(array);
```

## Question 6
## Create an array with four elements and remove the second element.

```
let arr = [2, 4, 3, 6];
arr.splice(1, 1);
console.log(arr);
```

## Question 7
## Create an array with five elements and remove the last element.

```
let array = [2, 4, 6, 8, 10];
array.pop();
console.log(array);
```

## Question 8
## Create an array with three elements and check if the array includes a specific value.

```
let arr = [1, 2, 3];
let newArr = arr.includes(3);
console.log(newArr);
```

## Question 9
## Create an array with four elements and sort the array in ascending order.

```
let arr = [1, 3, 5, 2];
let newArr = arr.sort(test);
function test(a, b) {
return a-b;
}
console.log(newArr);
```

 ## Question 10
## Create an array with five elements and sort the array in descending order.

```
let arr = [1, 3, 5, 2];
let newArr = arr.sort(test);
function test(a, b) {
return b - a;
}
console.log(newArr);
```

 ## Question 11
## Create two arrays, concatenate them and print out the resulting array.
```
let arr1 = [5, 6, 8];
let arr2 = [3, 5, 9];
let newarr = arr1.concat(arr2);
console.log(arr1);
console.log(arr2);
console.log(newarr);
```

## Question 12
## Create an array with three elements and convert it to a string.
```
let array = [3, 4, 7, 5];
console.log(array.toString());
```

## Question 13
## Create an array with four elements and reverse the order of the elements.
```
let array = [3, 5, 7, 9];
array.reverse();
console.log(array);
```

## Question 14
## Create an array with five elements and find the index of a specific value.
```
let arr = [1, 2, 3, 4, ];
arr.indexOf();
console.log(arr);
```

## Question 15
## Create an array with six elements and slice the array to create a new array with the first three elements.
```
let array = [3, 5, 7, 9, 12, 15];
array2 = array.slice(0, 3);
console.log(array);
console.log(array2);
```

## Question 16
## Create an array with six elements and use the map method to double each element.
```
let array = [2, 4, 6, 8, 10.12];
ans = array.map(doublenumber);
function doublenumber(num) {
return num \* 2;
}
console.log(ans);
```

## Question 17
## Create an array with four elements and use the while loop to calculate the sum of all elements.
```
let i = 0;
let arr = [3, 4, 5, 6];
let sum = 0;
while (i < arr.length) {
sum = sum + arr[i];
i++;
}
console.log(sum);
```

## Question 18
## Create an array with five elements and use the filter method to return only the even numbers.
```
let array = [12, 3, 20, 5, 14];
even = array.filter(evennumber);

function evennumber(num) {
return num % 2 === 0;
}
console.log(even);
```

## Question 19
## Create an array with three elements and use the join method to concatenate the elements with a dash (-) separator.
```
let array = [3, 5, 8];
ans = array.join("-");
console.log(ans);
```

## Question 20
## Create two arrays with three elements each and use the concat method to combine them into a new array.
```
let arr = [1, 2, 3];
let arr1 = [4, 5, 6];
let newArr = arr.concat(arr1);
console.log(newArr);
```