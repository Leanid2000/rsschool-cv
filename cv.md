# Mirankou Leanid
## Contacts
* **Location:** Gomel, Belarus
* **Phone:** +375 33 681-07-06
* **Email:** banrulit100000@gmail.com
* **GitHub:** Leanid2000
* **Discord:** Leanid Mirankou (@Leanid2000)
## About Me
I have recently become interested in the IT field. And I want to develop as a frontend developer. I quickly learn new knowledge. I like to learn new things.
## Skills
* HTML
* CSS
* Git, GitHub
* VS Code
* JavaScript (Basic), React (Basic)
## Code Example
Find the missing letter (KATA from CODEWARS)
Write a method that takes an array of consecutive (increasing) letters as input and that returns the missing letter in the array.

You will always get an valid array. And it will be always exactly one letter be missing. The length of the array will always be at least 2.
The array will always contain letters in only one case.
```
function findMissingLetter(array){
    let letters = 'abcdefghijklmnopqrstuvwxyz'.split('')
    let a = letters.indexOf(array[0].toLowerCase())
    let b = letters.slice(a,a+array.length)
    let c = b.filter(elem=>!array.includes(elem.toLowerCase())&&!array.includes(elem.toUpperCase())).join()
    return array[0]==b[0]?c:c.toUpperCase()
};
```
## Work Experience 
At the moment, I have no experience in the IT field
## Education
* **University:** Gomel State Technical University named after P.O.Sukhoi, **Specialization:** "Electric power systems and networks"
* **Courses:** self-study
## English
A1-A2
