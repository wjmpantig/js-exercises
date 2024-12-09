# js-exercises

Use the filename indicated


## beepbop.js

**Description:**

The program must accept 1 input (n) that is a number and then loop through (n) times starting from 0 .
- If n is even - print `beep (n)`
- If n is odd - print `bop`
- limit input from 0 to 30

**Notes:** Research how to validate that the string is a number

**Usage:** node beepbop.js [input]

Example

```bash
> node beepbop.js 5
beep 0
bop
beep 2
bop
beep 4
bop
> node beepbop.js test
Error: input "test" is not a number
> node beepbop.js 31
Error: input must be 0-30
```

## box.js

**Description:**
The program must accept 1 input(n) that is a number and then make a box using `#` character with (n) size

valid numbers: 1-10
**Usage:** node box.js [input]

Example

```bash
> node box.js 5
#####
#   #
#   #
#   #
#####
> node box.js 6
######
#    #
#    #
#    #
######
```

## palindrome.js

**Description:**
The program must accept 1 input that is a string and determine if that word is a palindrome

a palindrome is a word or phrase that is spelled the same backwards and forwards

[Wikipedia](https://en.wikipedia.org/wiki/Palindrome)


**Usage:** node paindrome.js [input]

```bash
> node paindrome.js racecar
"racecar" is a palindrome!
> node paindrome.js "taco cat" #use quotes to put 1 string in arguments
"taco cat" is a palindrome!
> node paindrome.js wayne
"wayne" is NOT a palindrome!
> node paindrome.js "Was it a car or a cat I saw?" #use quotes to put 1 string in arguments
"Was it a car or a cat I saw?" is a palindrome!
```

## x.js

**Description:**
The program must accept 1 input(n) that is a number and then make an X using `#` character with (n) size

valid numbers: 1-10
**Usage:** node x.js [input]

Example

```bash
> node x.js 5
#   #
 # #
  #
 # #
#   #
> node x.js 6
#    #
 #  #
  ##
  ##
 #  #
#    #
```

## mario`.js

**Description:**
The program must accept 1 input(n) that is a number and then make a stair shape using `#` character with (n) size

valid numbers: 1-10
**Usage:** node mario.js [input]

Example

```bash
> node mario.js 5
    #
   ##
  ###
 ####
#####
> node mario.js 6
     #
    ##
   ###
  ####
 #####
######
```