# A Regex Walkthrough

This is a tutorial for beginners who are not familiar with using regular expressions (also known as regex) in the development field. The focus of this tutorial will be how to understand the regex pattern for verifying hex color values.

## Summary
In web design, the color values are used to represent specific colors and use letters and numbers to define the particular color. These are referd to as hex color codes. Regex codes are used to verify text or strings matches the hex color codes by making sure they are wirtten correctly.


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
Regex uses the following tools listed below to manipulate strings. They will function to define the search pattern to match a text.

### Anchors
The anchors will target positions within the text where the match should occur.
<br></br>
Examples of this would include:
* `$` Indicates the end of a line.
*  `^` Indicates the start of a line.

### Quantifiers
Quantifiers will define the number of times a character will appear.
<br></br>
Examples of this would include:
* `*` Indicates 0 or more.
* `?` Indicates 0 or 1.
* `+` Indicates 1 or more.
* `{}` Indicates an exact occurance.

### OR Operator
The OR operator will match patters on the left or right.
<br></br>
Example of this would include:
* `|` This allows you to specify alternative patterns.

### Character Classes
Character classes will match a set of characters to a specific position.
<br></br>
Examples of this would include:
* `[0-9]` Indicates any number.
* `[a-z]` Indicates any lowercase letter.

### Flags
Flags will be added toward the end of a regex pattern.
<br></br>
Examples of this includes:
* `i` Indicates the pattern is case insensitive.
* `g` Indicates a global search.

### Grouping and Capturing
Grouping & capturing will literally group characters together or capture matched text for a later use.
<br></br>
Example of this includes:
* `()` 
### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind
Without including them in the match, look-arounds define specific conditions that are in front of or behind the current position.
<br></br>
Examples of these include:
* `(?=...)` Indicates to look ahead
* `(?<!...)` Indicates to look behind
## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)