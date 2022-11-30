![Logo-nav](https://s3.ap-south-1.amazonaws.com/kalvi-education.github.io/front-end-web-development/Kalvium-Logo.png)

# Kalvium Lab | Create a functionality

## Task: 
Your task is to create a functionality which can identify whether a number is present in the given array or not.
If it is present, then it should return the index of the array of that number.

## Starter code

Inside `app.js` file -> `arrayOfNumbers` and `itemToSearch` will be already given to you.

### Progression 1:

create a constant `NEG_INF` with -1000000 value, and a function `createPop`

### Progression 2: 

add 3 variables to `createPop()` : title, currIndex, check
1. title -> it holds the value of h3 element. (you have to create h3 tag and store it in title variable)
2. currIndex -> assign `NEG_INF` to this variable
3. check -> assign `false` to this variable

### Progression 3: 

create a function `find` (inside createPop function only).
Inside this function -> check whether the given item is present in the array or not, if it is present then assign currIndex to the index at which the item is present, and give check a true value.

### Progression 4: 

return a function (can be anonymous) -- must be inside `createPop()`.
Inside this function, call `find()` --> by calling this function --> you will get the updated currIndex and check value.
Use these updated values of `currIndex` and `check`, in order display the following :
1. If the element is present in the given array -> then display -> `The item is present and is at index ${currIndex}`
2. Else, display --> `The item is not present and is at index ${currIndex}`



Happy Coding Kalvium ❤️
