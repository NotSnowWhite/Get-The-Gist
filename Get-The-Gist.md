# Get-The-Gist

A quick guide to Regular Expressions - Matching an Hex Value

## Summary

In this gist, I will be explaining the functionality of each of the components in a regex code snippet. Regex (Regular Expressions) are a series of characters that define a pattern. Regex allows you to match results to more specific searches in your code. Basically, using regex, you can search for multiple instances of data instead of one particular occurrence.

The following example displays the regex for matching an Hex Value: /^#?([a-f0-9]{6}|[a-f0-9]{3})$/

Looks funky, yeah? Let's talk about it...

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

First, note that the beginning and end of the code snippet are denoted with a /. This is because Regular Expressions are literals and the slash represents the beginning and end of the full literal sequence you would like to specify.

Anchors are the ends of the line. They specify the position data in the sequence and they also go inside the //.
The anchors in the sequence to match the hex values are ^ and $. 
- ^ denotes the beginning of the line and stipulates that that which comes after it is the literal sequence.
- $ denotes the end of the line and stipulates that that which came before it was the literal sequence and it is now done.

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

With less than half a year of experience in coding and development, I've gained minor skills in JavaScript, HTML, CSS, Nodejs, MongoDB, and SQL. In order to continue to progress my skills and knowledge in the field, I have created this gist about regex. 

This marks the end of my first gist; thanks for reading. 

Check out my github below!
- [NotSnowWhite Github](https://www.github.com/notsnowwhite)

