![](/rsschool-cv/myFoto.png)
## **Sergii Polushkin**        

#### Junior Frontend Developer
---
* __Date of Birth:__ 06.09.1985
* __Place of residence:__ Murcia, Spain
* __Phone number:__ +34 610 13 40 94
* __Email:__ seregapola@gmail.com
* __GitHub:__ [SergiiPol](https://github.com/SergiiPol)
* __Discord:__ d10gen(@sergiipol)
#### About Myself
___

I am excited about joining your highly qualified team as a developer. Currently, I am actively learning
the JavaScript programming language and the VUE framework. I believe that my personal qualities
and broad life experience would make me a great asset in this position and will help me in the rapid
development of the new specialty.
 

I find the work of a developer exciting. I believe it will broaden my horizons and will make me grow. 


I am a quick learner, and perfectly know how to organize myself. Also, I am sociable and will be glad
to work in a team of dedicated professionals. Besides, I have an analytical mindset, and I am ready
to take responsibility for my work and tasks.



#### **Education**
***
- *Master,*  **"Kharkiv State University of Feeding and Trade"** completed study in 2009
    - specialty **"Enterprise economy"**
    - qualification **"Economist"** 

 #### **Courses and seminars**
 ___
- **CS50** (YouTube course)
- **JavaScript** [on-line textbook](learn.javascript.ru)
- **RS School** Frontend (in the process of studying)

#### **Skills**
***
- ***HTML*** ( Markdown)
- ***CSS*** (Framework "Bootstrap", Preprocessor SCSS)
- ***JavaScript*** (ES6+,DOM) 
- ***Framework "Vue"***  (*basic knowledge*)
- ***GIT*** (*service GitHub*)
- ***VSCode*** (*editor*)
#### **Code examples**
>The input is a string str of digits. Cut the >string into chunks (a chunk here is a substring >of the initial string) of size sz (ignore the >last chunk if its size is less than sz).
>
>If a chunk represents an integer such as the sum >of the cubes of its digits is divisible by 2, >reverse that chunk; otherwise rotate it to the >eft by one position. Put together these modified >chunks and return the result as a string.

>If
>sz is <= 0 or if str is empty return ""
>sz is greater (>) than the length of str it is >impossible to take a chunk of >size sz hence >return "".
```
function revrot(str, sz){
    if (sz < 1 || sz > str.length) 
      return "";

    let a =Math.trunc(str.length/sz)*sz

    let c = str.slice(0, a);

    const newArray = [];
  for (let i = 0; i < c.length; i += sz) {
    newArray.push(str.slice(i, i + sz));
  }
const s= [];
  let n = newArray
    .map(function(num){
        if(num.toString().split('').reduce((s,num)=>s+num**3,0)%2===0){
            let a = num.split('').reverse().join('');
             return s.push(a);
          }
       else {
            let b = num.slice(1)+num[0];
            return s.push(b);
         }
    })

 return s.join("");
 
 }
```
#### **Languages**
___
- **Russian:**   C2 (Native)
- **Ukrainian:** C1 (Advanced)
- **Spanish:** B2 (Upper-Intermediate)
- **English:** A2 (Pre-Intermediate)