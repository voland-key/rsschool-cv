# Anton Smirnov
### System Engineer

---
### Contacts

**Phone:** +7 (812) 438-00-60
**E-mail:** 3704156@gmail.com

---
### Personal Summary

Starting my career as a computer science teacher in 2000 at the public school #495 in St. Petersburg, Russia, I taught the basics of programming languages such as Pascal, Delphi and some web technologies such as the basics of HTML and CSS. After 2 years I changed my line of work to a sales manager of computer components in the largest store of my city.

In 2005 I graduated from the institute with a specialization in “computer-aided design of radio-electronic devices”. In 2012 I changed my specialization from sales to system administration and started to study server software such as mail servers, sip-telephony and others. Also in 2014, I started working on a project that helps medical centers organize their business processes. While working on it, I started learning JS, jQuery, MySQL, and the PHP stack.

Currently, I am working on two different projects in the logistics software field and I need to learn programming tools like Git and in this course I am updating my knowledge to keep up to date.

---
### Skills and Profiency

Constantly work with Linux based software: 

+ [Proxmox](https://proxmox.com) and ESXi
+ [Zimbra NE](https://zimbra.com) servers 
+ [Zentyal](https://zentyal.org) domain-controllers
+ [Issabel PBX](https://issabel.org) sip servers
+ [OPNsense](https://opnsense.org) and [RouterOS](https://mikrotik.org) based routers    
+ VPN software such as IPSec, Wireguard, OpenConnect and other

Programming skills: 
+ JavaScript with jQuery framework
+ HTML and Bootstrap 5 CSS framework
+ MySQL, PostgreSQL
+ Redis
+ PHP 5.0++ as backend

---
### Code example:

**Find the odd int [KATA from CODEWARS](https://www.codewars.com/kata/54da5a58ea159efa38000836/train/javascript):**
Given an array of integers, find the one that appears an odd number of times.
There will always be only one integer that appears an odd number of times.
Examples:
[7] should return 7, because it occurs 1 time (which is odd).
[0] should return 0, because it occurs 1 time (which is odd).
[1,1,2] should return 2, because it occurs 1 time (which is odd).
[0,1,0,1,0] should return 0, because it occurs 3 times (which is odd).
[1,2,2,3,3,3,4,3,3,3,2,2,1] should return 4, because it appears 1 time (which is odd). 

```javascript
function findOdd(A) {
  const uniqueArray = []
  var res = 0
  // generate unique array
  A.forEach(item => {
      if (!uniqueArray.includes(item)) {
          uniqueArray.push(item)
      }
  })
  // count length of entries unique array in A array
  uniqueArray.forEach(item => {
    let idx = A.indexOf(item),
        indices = [];
    while (idx != -1) {
      indices.push(idx);
      idx = A.indexOf(item, idx + 1);
    }
    // if it ODD - then return
    if (indices.length % 2 > 0) { 
      res = item 
    }
    
  });
```
---
### Courses

- HTML, CSS, Bootstrap Tutorials on the [W3S](https://w3schools.com)
- MDN web docs at [Mozilla](https://developer.mozilla.org)
- RS Schools Course "JavaScript/Front-end. Stage 0 (in progress)

----
### Languages

- English - Intermediate
- Russian - Native
