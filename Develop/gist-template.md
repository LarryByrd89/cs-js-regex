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
* `[0-9]` Indicates any number from 0-9.
* `[aeiou]` Indicates any vowel that is matched. 

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
Bracet expressions will provide a way to match a single character out of a range, but they are separated by a hyphen.
<br></br>
Examples of this includes:
* `[a-z]` Indicates any lowercase letter from a-z will match.
* `[0-9]` Indicates any number from 0-9.
* `[a-z0-9]` Indicates multiple ranges of numbers and letters will match.

### Greedy and Lazy Match
Greedy and Lazy matches involve quantifiers, which will determine the number of times a character or group of characters will repeat. Greedy and Lazy matches will manipulate these quantifiers by the amount of text they match.
<br></br>
Example of Greedy match is:
* `.*` Indicates they match any character zero or more times. It is eager to include as many characters as it can.
<br></br>
Example of Lazy match is:
* `.?` Indicates it will only match the first character in a string. It wants to match as few characters as possible.

### Boundaries
Boundaries can be used when you want to prevent unintended partial matches.
<br></br>
Examples of this includes:
* `\b` Indicates the position between a word, number, or symbol boundary at the start or the end.
* `\B` Indicates the position within a word, number, or symbol boundary.


### Back-references
Back-references will allow you to reference back to groups that have already been captured, and can match repetitive or duplicated patterns.
<br></br>
Examples of this includes:
* `(\w)` Indicates a single word character that has been captured.
* `(\b\w+\b)` Indicates a whole word that has been captured.
* `(\d{2})`Indicates two digits captured
* `(\d{2}):(\d{2}):(\d{2})` captures a time in the format HH:MM:SS
* `\1` Indicates to reference the first group captured.
* `\2` Indicates to reference the second group captured.
### Look-ahead and Look-behind
Without including them in the match, look-arounds define specific conditions that are in front of or behind the current position.
<br></br>
Examples of these include:
* `(?=...)` Indicates to look ahead
* `(?<!...)` Indicates to look behind

## Author

Laryn Myrick

Email: laryn.n99@gmail.com

GitHub: <a href = https://github.com/LarryByrd89>LarryByrd89</a>
