# Arseniy Ostroumov
-----
## Junior Fronted Developer
-----
## Contact Information:

Phone: +995 599779442

E-mail: ostroum.am@gmail.com

Telegram: @molodoikio

Discord: @arseniy.ostroumov

-----
## Self-Introduction

-----
## Skills
* HTML5
* CSS3
* JavaScript Basics
* Python Basics
* Git, Github
* VSCode
* Adobe Photoshop
-----
## Code Eaxamples
*In this kata you have to implement a base converter, which converts positive integers between arbitrary bases / alphabets. Here are some pre-defined alphabets:*
```
var Alphabet = {
    BINARY:        '01',
    OCTAL:         '01234567',
    DECIMAL:       '0123456789',
    HEXA_DECIMAL:  '0123456789abcdef',
    ALPHA_LOWER:   'abcdefghijklmnopqrstuvwxyz',
    ALPHA_UPPER:   'ABCDEFGHIJKLMNOPQRSTUVWXYZ',
    ALPHA:         'abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ',
    ALPHA_NUMERIC: '0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ'
};

var bin = Alphabet.BINARY, 
    oct = Alphabet.OCTAL, 
    dec = Alphabet.DECIMAL, 
    hex = Alphabet.HEXA_DECIMAL,
    allow = Alphabet.ALPHA_LOWER, 
    alup = Alphabet.ALPHA_UPPER, 
    alpha = Alphabet.ALPHA, 
    alnum = Alphabet.ALPHA_NUMERIC;
```
*The function convert() should take an input (string), the source alphabet (string) and the target alphabet (string). You can assume that the input value always consists of characters from the source alphabet. You don't need to validate it.*
```
function convert(input, source, target) {
    let result = '';
    if (source.length == 10) {
        let number = parseInt(input);
        while (number != 0) {
            result += number % target.length;
            number /= target.length;
        }
        result = result.split("").reverse().join("");
    }
    return result;
}
```
-----
## Work Experience

-----
## Education
* 2015 - Graduated Moscow University of Programming and Informatic
* 2009 - Graduated Serpukhov Technical College
-----
## Courses
* Agile Scrum Master course
* Python basics course
* RS School «JavaScript/Front-end. Stage 0» Course
-----
## Languages
* Russian - native
* English - B2 (Upper-Intermediate)
