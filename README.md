# divisibility

A simple way to check if a number is divisibile by another number in JavaScript!

Usage is easy as long as the number you want to check divisibility by is less than 1000.

## Usage

Simply call the appropriate function. Want to check if a number is even?

    var divisibility = require("divisibility");
    var isThreeEven = divisibility.isDivisibleByTwo(3);  // false
    var isFourEven = divisibility.isDivisibleByTwo(4);  // true

Need to check against a bigger number? No problem!

    var divisibility = require("divisibility");
    var check = divisibility.isDivisibleByThreeHundredAndSixtyTwo(362);  // true
    var check2 = divisibility.isDivisibleByFourHundredAndSeventyEight(5);  // false
    var check3 = divisibility.isDivisibleByTwelve(13);  // falseb

## Bug reports

This package contains no bugs and is production-ready!
