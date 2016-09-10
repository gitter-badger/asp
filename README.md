#ASIMP
####A Simple Package

[![Join the chat at https://gitter.im/nodejs_asimp/forum](https://badges.gitter.im/nodejs_asimp/forum.svg)](https://gitter.im/nodejs_asimp/forum?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
>The ASIMP Is A ToolTip For Better JS.

[![https://gitter.im/nodejs_asimp/Lobby](https://badges.gitter.im/nodejs_asimp/Lobby.svg)](https://gitter.im/nodejs_asimp/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

REQUIRES NODEJS

[getIt](https://www.npmjs.com/package/asimp)

The ASIMP Is Pretty Easy, Just you need a simple
walk through, to use it tools.

>>>>The browser support coming soon...

####isInBase
The `isInBase` Is A Math Tool.

That Will check is a number is able to devide by another number?

returns (TRUE or FALSE)

It's Syntax Is
>asimp=require('asimp');
>
>asimp.isInBase(numberA,numberB);
>
>//NumberA / NumberB

####hasFloat
The `hasFloat` Is A Math Tool.

That Will check has a number got floating number?

returns (TRUE or FALSE)

It's Syntax Is
>asimp=require('asimp');
>
>asimp.hasFloat(number)

####splitArray
The `splitArray` Is A Javascript Tool.

It Will split The Array:

['abc','cba'] split _b_ will be [['a','c'],['c','a']]

returns Array

It's Syntax Is
>asimp=require('asimp');
>
>asimp.splitArray(ArrayToSplit,KeyWord);

####splitArrayToString
same as `splitArray` but returns String.

It's Syntax Is
>asimp=require('asimp');
>
>asimp.splitArrayToString(ArrayToSplit,KeyWord);

####getYear
Will Gets The Number Of Year, Created Becuase `new Date().getYear();` will return 116 for 2016

returns Number;

It's Syntax Is
>asimp=require('asimp');
>
>asimp.getYear(RealLifeYear,Number);
RealLifeYear = true or false, depending on convertation method(to JS Year=false,To Normal Year=true);

####manyFloat
The `manyFloat` Is A Math Tool.

It will Return A list Of Array:

 1. How Many Number Of Floating Number
 2. Number With No Floating point
 3. It's Input

It's Syntax Is
>asimp=require('asimp');
>
>asimp.manyFloat(Number);

####arrayToString
The `arrayToString` Is A Javascript Tool.

It's a alternative + pro edition of `Array.toString()`

returns String

It's Syntax Is
>asimp=require('asimp');
>
>asimp.arrayToString(Array,StringToPutBetweenEach);
e.g asimp.arrayToString(['a','b'],'&') will return a&b

####match
It's a alternative of `String.match()` + `arrayToString(Array,'&')

`It's Syntax Is
>asimp=require('asimp');
>
>asimp.match(String, Regex);

# copyright (C) 14ul
