## Week 1 - React
## Week Challenges
## Tuesday

### 1. [Ensure Question](https://www.codewars.com/kata/5866fc43395d9138a7000006)

```
function ensureQuestion(s) {
    let length = s.length-1;
    let char = s.charAt(length)
    char !== "?" ?  s=s+"?": s;
    
    return s;
}
```

### 2. [Reversed Words](https://www.codewars.com/kata/51c8991dee245d7ddf00000e)

```
function reverseWords(str){

    let orderStr = str.split(" ")
    let reversed = orderStr.reverse();
    let result = "";

    reversed.forEach((w) => {
         result += w+" ";
    })

    return result.trim();
  }
```


## Wednesday
### 1. [Smallest integer in array](https://www.codewars.com/kata/55a2d7ebe362935a210000b2)
```
class SmallestIntegerFinder {
  findSmallestInt(args) {
    
    return Math.min(...args);
  }
}
```

## Thursday
### 1. [Odd or Even](https://www.codewars.com/kata/5949481f86420f59480000e7)
```
```

## Week links
1. [Read about Strings](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/String)
2. [Read about "Ends With" function](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/String/endsWith)
3. [Read about concat options](https://masteringjs.io/tutorials/fundamentals/string-concat#:~:text=The%20%2B%20Operator,used%20to%20concatenate%20two%20strings.&text=You%20can%20also%20use%20%2B%3D,for%20a%20%3D%20a%20%2B%20b%20.&text=If%20the%20left%20hand%20side,hand%20side%20to%20a%20string.)
4. [Read about arrays](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Array)
5. [Read about numbers](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Number)
6. [Read about Math](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Global_Objects/Math)



