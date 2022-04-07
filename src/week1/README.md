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

## Week links



