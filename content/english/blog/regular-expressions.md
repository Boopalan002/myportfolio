---
title: Regular Expressions
date: 2022-05-03T09:39:50.256Z
image: https://miro.medium.com/max/1400/0*IsFD2Blt1CG9iHTk
description: Regular Expressions are used for pattern matching (or) string matching.
---
#### Regular Expressions are used for pattern matching (or) string matching.

* regular expression ("regex"): a description of a pattern of text
   - can test whether a string matches the expression's pattern
   - can use a regex to search/replace characters in a string
* regular expressions occur in many places: 
   - supported by JavaScript, PHP, and other languages 
   - many text editors (TextPad) allow regexes in search/replace

---
**Expressions**|**Description**
:-----:|:-----:
[abc]|a, b or c
[^abc]|any character except a, b, c
[a-z]|a to z
[A-Z]|A to Z
[a-zA-Z]|a to z, A to Z
**[0-9]**|**0 to 9**

---

**Quantifiers**|**Description**
:-----:|:-----:
[  ]?|occurs 0 or 1 time
[  ]+|occurs 1 or more times
[  ]*|occurs 0 or more times
[  ]{n}|occurs n times
[  ]{n,}|occurs n or more times
**[  ]{y,z}**|**occurs at least y times but less than z times**

---

**Meta characters**|**Description**
:-----:|:-----:
\d|[0-9]
\D|[^0-9]
\w|[a-zA-Z\_0-9]
**\W**|**[\^w]**

---

### Examples

1. Mobile number start with 8 or 9 and total digits = 10 
   - ***[89][0-9]{9}***
2. First character uppercase, contains lower case alphabets, only one digit allowed in between 
   - **[A-Z][a-z]*[0-9][a-z]***
3. Email ID 
   - ***[a-zA-Z0-9_\-\.]+[@][a-z]+[\.][a-z]{2,3}***