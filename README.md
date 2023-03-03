# RegexComp

## Summary

This is a tutorial that will break down a regular expression matching hex values. They usually use a '#' with six numbers or letters coming after it.

## Table of Contents
- [Anchors](#Anchors)
- [Quantifiers](#Quantifiers)
- [OR Operator](#OR)
- [Character Classes](#Character_Classes)
- [Flags](#Flags)
- [Grouping And Capturing](#G&R)
- [Bracket Expressions](#Bracket_Expressions)

## Regex Components

A Hex value, the regex looks like this: '/^#?(([a-z0-9]{6}|[a-z0-9]{3}))$/' A lot to take in but this breakdown should help explain!

### Anchors

There are anchors in a regex string which are the; '^' and '$', the '^' represents the start of the string and the '$' represents the end of the string.
-'^#?([a-z0-9]{6}|[a-z0-9]{3})$' everything in between the ^ and $ will be showing what the regex is looking for.

### Quantifiers

-?([a-f0-9]{6}|[a-f0-9]{3})
Quantifiers are *,?,+, and {}. The * and + will allow for matching 0 or more times. The ? only allows for matching 0 or 1 times. The {} allows for matching an exact amount of times. In the example above with the ? in there, we are only looking for one match or none!

### OR Operator

-'[a-z0-9]{6}|[a-z0-9]{3}' 
The (A.K.A. a straight line) '|' in the middle is representing that it will be 6 characters or 3 OR Operators in our example: this allows the user to match either the expression on the left or the right of the straight line | positioned in between the two expressions.

### Character Classes

-'/^#?([a-z0-9]{6}|[a-z0-9]{3})$/' 
The character class here is a-f0-9. The character class is a set of characters that is enclosed within the brackets. The a-f tells the range the hex code uses, meaning the code can begin with any letter between 'a though f'. Also the hex code has 0-9 attached after the f, which also allows the hex code to begin with any digit from '0 to 9'.

### Grouping and Capturing

-'([a-z0-9]{6}|[a-z0-9]{3})' 
The '()' groups the expression between them. The grouping treats multiple characters as a single unit. This can be useful when gathering information using any programming language. This data will be made out in the form of an array. Values can be accessed using an index on the result of the match. The end string anchor $ is used when spliting the groups.

### Bracket Expressions

-'[a-z0-9]' 
Bracket expression is a regex that will match a pattern of characters; alphabetic, numeric, and special characters defined within the brackets. The bracket '[]' expression indicates matching a string that has any lower case character between a-z or any integer between 0-9.

## Author

My name is Daniel and I'm currently enrolled in a full stack web development class. The main goals I have are to excel in the languages currently studying consisting of; React, NodeJS, Javascript, API knowledge, and MySQL. I'm hoping my skills will be used someday in a company and becoming a asset to that place that takes me in!

Github: DanielMartin971

Email: DanielMartin971337@gmail.com
