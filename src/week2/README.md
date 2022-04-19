## Week 2 - 
## Week Challenges

## Monday
### 1. [Is Palindrome?](https://www.codewars.com/kata/57a5015d72292ddeb8000b31)
```
function isPalindrome(line) {
    line = line.toString();
    let result = false;
    if(line.length === 1) return result = true;
    let middle = Math.ceil(line.length/2)
    let line1 = "";
    let line2 = "";
    if(line.length%2 == 0){
        line1 = line.slice(0,middle)
        line2 = line.slice(middle)
        line2 = line2.split("").reverse().join("")
    }else{
        line1 = line.slice(0,middle-1)
        line2 = line.slice(middle)
        line2 = line2.split("").reverse().join("")
    }
    
    line1 === line2 ? result = true : result
    console.log(line1+"+"+line2)
    return result

  }
```
## Tuesday
### 1. [Multiple of Index](https://www.codewars.com/kata/5a34b80155519e1a00000009)
```
```

## Wednesday
### 1. [Well of Ideas](https://www.codewars.com/kata/57f222ce69e09c3630000212)
```
```

## Thursday
### 1. [Decode the Morse code](https://www.codewars.com/kata/54b724efac3d5402db00065e)
```
```


## Week links
1. [BEM](http://getbem.com/introduction/)
2. [Radium](https://formidable.com/open-source/)
3. [Styled Components](https://styled-components.com/)
4. [React Bootstrap](https://react-bootstrap.github.io/)
5. [FLexboxFroggy](https://flexboxfroggy.com/)

## Example
1. [Styling](https://github.com/corecodeio/upskilling-styling-example)
