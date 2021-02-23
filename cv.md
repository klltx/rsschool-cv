# CV

Svetashov Konstantin

## Contacts
1. [VK](https://vk.com/id221961828)

## Personal information
I want to work a lot and learn new technologies in IT

## Skills
* Java
* SQL
* JavaScript
* HTML & CSS
* Git

## Code examples
```
function squareDigits(num){
  let res = '';
  while(num > 0){
    res += Math.pow(num % 10, 2) + ' ';
    num = Math.floor(num / 10);
  }
  return Number(res.split(' ').reverse().join(''));
}

function fizzbuzz(n)
{
  if(n < 1) throw new RangeError("");
  let res = [];
  for(let i = 0; i <= n; i++){
    if(i % 15 == 0) res[i] = "FizzBuzz";
    else if(i % 5 == 0) res[i] = "Buzz";
    else if(i % 3 == 0) res[i] = "Fizz";
    else res[i] = i;
  }
  res.splice(0, 1);
  return res;
}
```

## Level of English
English level grade - B1
