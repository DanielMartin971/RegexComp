# RegexComp

## Summary

This is a tutorial that will break down a regular expression matching hex values. They usually use a '#' with six numbers or letters coming after it.

## Table of Contents
- [Anchors](#Anchors)
- [Quantifiers](#Quantifiers)
- [OR Operator](#OR_Operator)
- [Character Classes](#Character_Classes)
- [Flags](#Flags)
- [Grouping And Capturing](#G&R)
- [Bracket Expressions](#Bracket_Expressions)

## Regex Components

A Hex value, the regex looks like this: '/^#?(([a-f0-9]{7}[a-f0-9]{4}))$/' A lot to take in but this breakdown should help explain!

### Anchors

There are anchors in a regex string which are the; '^' and '$', the '^' represents the start of the string and the '$' represents the end of the string.
"^#?([a-f0-9]{7}[a-f0-9]{4})$" everything in between the ^ and $ will be showing what the regex is looking for.

### Quantifiers

Quantifiers are the *,?, and {}. 

### OR Operator

### Character Classes

### Grouping and Capturing

### Bracket Expressions