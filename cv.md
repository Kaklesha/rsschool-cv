#KIRILL KORNILOV

### Student Software Engineer
---
 __Contact information:__

 *Phone:* 89878034723

 *E-mail:* k-korni1ov@yandex.ru

*Discord:* kaklesha#4387

---

#### About Me

When I was learn in college  It begin to think about that am i want to do? 
But i don't find answer to this day
Finally I choose to close competencies of related areas 

---

#### Skills and Proficiency:

⋅⋅*SQL
⋅⋅*C#
⋅⋅*CSS, HTML5
⋅⋅*Git

---

#### Education

I finished college in the Saratov city
and joined at university 3 years ago.
Now I study at Yuri Gagarin State Technical University of Saratov.

---

#### Code example:

An isogram is a word that has no repeating letters, consecutive or non-consecutive. Implement a function that determines whether a string that contains only letters is an isogram. Assume the empty string is an isogram. Ignore letter case.

*Solve:*

```javascript
function isIsogram(str1) {
  
    let str=str1.toLowerCase();
  if(str=="") return true;
    let isTrue=false;
    let i=0;
  for (let char of str) {
    i=0;
    k=0;
      isTrue=true;

        while(i<str.length){
            if( char==str[i]){            
                console.log(char+" = "+str[i]);
                k++
            };           
            i++;
        }
       if(k>=2){
        isTrue=false;       
           break;
       }
      }        
       return isTrue;
} 
```

#### Languages

⋅⋅*English - elementary 
⋅⋅*Russian - Native
