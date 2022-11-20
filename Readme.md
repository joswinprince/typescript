
## Initialize the typescript project
```
npx --package typescript tsc --init
```

## compile the typescript files
```
npx --package typescript tsc
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
# Add example
```
function add(num1:number,num2:number):number
{
    return num1 +num2;
}
console.log(add(12,12));
```
