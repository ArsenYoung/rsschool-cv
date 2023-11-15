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

I have great work experience in IT industry, which counted more than 7 years. At the beginning of my career I worked as analyst in small and big companies and showed myself as a reliable and problem-solving employee. One year ago I decided to change my career way and retrain to developer. I started my education with studying computer science and backend-development, but then I switched on frontend-development because it more interesting for me than backend-development. Now I'm studying in RS School, improving my knowledge about frontend-development and developing my own freelance projects.

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
## Code Examples
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
__2020 - 2022 Sberbank__

Worked in develop team with HR-recruitment project PULSE as a release-manager and a scrum-master. Improved release frequency for 40%. Helped to reorganize work processes for team using modern Scrum practices, as a consequence of which team productivity was grown for 50% and quality of code was grown for 30%.

**2018 - 2020 Sberbank**

Worked as an analyst and an engeneer with HR-recruitment project based on cloud platform SAP Success Factors. Developed and upgraded companies reqcruitment proccesses, due speed of hiring applicants was grown for 40%.

**2015 - 2018 MigoGroup company (IT consulting)**

Worked as an intern analyst on several projects based on SAP HCM platform.

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
