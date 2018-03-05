![USEDPOST](https://img.shields.io/badge/USES-HTML-green.svg?style=for-the-badge) ![USEDPOST](https://img.shields.io/badge/USES-GIT-orange.svg?style=for-the-badge) ![USEDPOST](https://img.shields.io/badge/USES-Javascript-blue.svg?style=for-the-badge)

# FizzBuzz using Javascript

The goal of Fizzbuzz is to introduce you to Test Driven Development (TDD) and also it is one of the first programs that someone writes when learning a new language.
So this is the implementation in Javascript.

## Specifications of Fizzbuzz
- The program can be passed a number.
- When passed a number that is a multiple of 3, the program returns the message 'Fizz'.
- When passed a number that is a multiple of 5, the program returns the message 'Buzz'.
- When passed a number that is a multiple of both 3 and 5, the program ignores the previous 2 rules and returns the message 'Fizzbuzz'.
- In all other cases, the program simply returns the given number.


## How to Play
First clone the directory to your local drive & navigate to the folder that contains the game, by doing the following:

```
$ git clone git@github.com:lunaticnick/makersacademy-mcw05-javascriptbuzz.git local_directory
$ cd local_directory
```

In order to play the game you will need to open ```SpecRunner.html``` located in root and then to use the developer console of your favourite browser.


Then you can start playing the game by using the following commands:


```
javabuzz = new Javabuzz()
Javabuzz {}

javabuzz.says(3)
"Java"

javabuzz.says(15)
"JavaBuzz"

javabuzz.says(5)
"Buzz"

javabuzz.says(2)
2
```
