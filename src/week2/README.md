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
### 1. [Well of Ideas](https://www.codewars.com/kata/57f222ce69e09c3630000212)
```
function well(x){
    let count = 0;

    x.forEach ((c) => {
        if(c === "good"){
            count += 1;
        }
    })
    
    ideas = ""
    if(count === 1 || count === 2){
        ideas = "Publish!"
    } else if (count > 2){
        ideas = "I smell a series!"

    }else {
        ideas = "Fail!"
    }
    return ideas;
}

```

## Wednesday
### 1. [React Manage Events](https://www.codewars.com/kata/5a8319f257c562ede8000037)
```
```

## Thursday
### 1. [React Santa Wish List](https://www.codewars.com/kata/5a9ecd89fd5777e0790001ea)
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
