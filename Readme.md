
## Initialize the typescript project
```
npx --package typescript tsc --init
```

## compile the typescript files
```
npx --package typescript tsc
```

## Run the typescript compiled file
```
node filename // filename without extension
```

## example
```
let lname;
 lname = 'jon';
 let n=lname.toUpperCase();
//lname = 10;
console.log(n)

let age;
age = 25;
console.log(age)
let config;
config = true;
console.log(config)
let isvalid = true;
console.log(isvalid)


let emplist =["santish","santol","street",2];
console.log(emplist);
let numList;
numList = [1,2,3,4,5];
let results = numList.filter((num)=> num >2);
console.log(results);
let myresults = numList.filter((num1)=> num1 >= 2);
let result = numList.find((num)=> num =2);
let emp = emplist.find((emp)=> emp ==="santish");
console.log(emp);
let sum = numList.reduce((acc,num)=> acc+num);
console.log(emp);
console.log(sum);
```
## Add example
```
function add(num1:number,num2:number):number
{
    return num1 +num2;
}
console.log(add(12,12));
```
## Add example single line
```
const add = (num1:number,num2:number):number => num1+num2;
console.log(add(92,12));
```
## Subtract example

```
function sub(num1:number,num2:number):number
{
    return num1 -num2;
}
console.log(sub(22,21));
```
## Add three number
```
 function add3(num1:number,num2:number,num3?:number):number
    {
   return num3 ? num1+num2+num3 :num1+num2;
    }
    console.log(add3(10,20));
```
## Add three number one line
```
const add3e = (num1:number,num2:number,num3?:number):number =>
  num3? num1 + num2 + num3:num1 +num2;
```
## add more numbers
```
    function add2(num1:number,num2:number,...num3:number[]):number{
        return num1 + num2 + num3.reduce((a,b)=> a + b,0);
    }
    let numbers = [1,2,3,4,5];
    console.log(add2(2, 4, ...numbers));
```

## Generic methods
```
   function getItems<T>(items:T[]):T[] {
        return new Array<T>().concat(items);
    }
      let numbers = [1,2,3,4,5];
        let concatResult = getItem<number>(numbers);
   ```
