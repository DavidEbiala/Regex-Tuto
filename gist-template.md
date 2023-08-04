# Title (replace with your title)

Introductory paragraph (replace this with your text)
In the tutorial, we will be discussing how we use a regex combination to verify and allow all possible letters and numbers within a Hexadeciemal value. A Hexadecimal, often abbreviated as "hex," is a numeral system with a base of 16. It uses sixteen distinct symbols to represent numbers: 0-9 for values 0 to 9 and A-F (or a-f) for values 10 to 15. In this system, each digit's value is determined by its position and weight. So, the lowest number in a hex is 0 while the highest is 'F' or 15.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

In this particular tutorial however, we will be discussing the regex (regular expression) for a hexadecimal and breakdown each of its components.
Below is the regex code for accepting every possible hexadecimal value.
Matching a Hex Value – [/^#?([a-f0-9]{6}|[a-f0-9]{3})$/]
We will discuss the anchors, the quantifiers, OR Operators, Character classes and flags in this tutorial.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components
A regex is considered a literal, it's a constant value that is assigned to constant variables, so the pattern must be wrapped in slash characters (/). If we examine the “Matching a Hexadecimal” regex, you'll see that this is true:
[/^#?([a-f0-9]{6}|[a-f0-9]{3})$/] 
Note: The '[]' brackets where added so the code could be better seen for the user.
### Anchors
Anchors are regex tokens which don't match any character, but rather it asserts something that is found about the given string or the matching procces. It can also assert an engine's current position. In this regex, there are two anchors which is the caret designated with the symbol '^' and the dollar sign designated with the symbol '$'. The Caret represents the beginning of a string or line. So in the given regex '[/^' indicates the regex line has started and everything to the right of it matters. Just as the caret represents the beginning or start of a line, the dollar sign represents the end of a line which would look like this '$/]'
### Quantifiers
Now we have quantifiers, quantifiers set the limits of the string that a regex matches. Normally it includes the minimum and maximum number of characters that a regex is looking for. Here our given regex has two quantifiers [/^#?([a-f0-9]{6}|[a-f0-9]{3})$/]. 6 characters or 3 characters depending on the OR operator.
### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
