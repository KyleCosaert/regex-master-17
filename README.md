# Regex Tutorial Starter Code

Regular expressions are a powerful tool for searching and manipulating text. They allow you to define patterns of characters that can match specific strings. In this tutorial, we will be explaining the regular expression `/^\w+@[a-zA-Z_]+?\.[a-zA-Z]{2,3}$/` which is commonly used to match email addresses. We will be breaking down each component of the regex and explaining what it does.

## Summary

The regular expression `/^\w+@[a-zA-Z_]+?\.[a-zA-Z]{2,3}$/` is used to match email addresses. It has several components that define the pattern to be matched. The regex starts with the caret ^ which matches the start of a line, followed by one or more word characters \w+, which matches any alphanumeric character or underscore. This is followed by an at symbol @, and then a string of one or more alphabetic characters and underscores `[a-zA-Z_]+?`, which matches the domain name. The ? at the end makes the expression non-greedy, meaning it will match the shortest possible string. Next, a period `\`. is used to match the period character in the domain name, followed by two or three alphabetic characters `[a-zA-Z]{2,3}` that represent the top-level domain (TLD) such as .com or .net. Finally, the regex ends with the dollar sign $, which matches the end of a line.

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
The `/^\w+@[a-zA-Z_]+?\.[a-zA-Z]{2,3}$/` regex is composed of the following components:

### Anchors
The caret ^ and dollar sign $ are used to define the start and end of a line in the regular expression. In this regex, the caret ^ matches the beginning of the line, and the dollar sign $ matches the end of the line.

### Quantifiers
The plus sign + is used as a quantifier in this regex to indicate that the previous character or group should match one or more times. The \w+ matches one or more word characters, and `[a-zA-Z]{2,3}` matches two or three alphabetic characters.

### OR Operator
The vertical bar | is used as an OR operator in regular expressions, allowing you to match one of two options. However, it is not used in this regex.

### Character Classes
Character classes are used to match a set of characters in a single position of a string. The regular expression `@[a-zA-Z_]+?\.` matches the at symbol @ followed by one or more alphabetic characters and underscores.

### Flags
Flags modify the behavior of a regular expression. However, they are not used in this regex.

### Grouping and Capturing
Grouping and capturing allow you to create sub-patterns within a regular expression that can be used later. However, they are not used in this regex.

### Bracket Expressions
Bracket expressions are used to match a single character from a set of characters. However, they are not used in this regex.

### Greedy and Lazy Match
The question mark `?` is used in this regex to make the expression non-greedy, meaning it will match the shortest possible string. The `[a-zA-Z_]+?` matches one or more alphabetic characters and underscores, but stops matching as soon as it finds the next period character ..

### Boundaries
Boundaries are used to match a position between characters, rather than matching the characters themselves. However, they are not used in this regex.

### Back-references
Back-references allow you to reference a previously matched group within the same regular expression. However, they are not used in this regex.

### Look-ahead and Look-behind
Look-ahead and look-behind are used to match characters based on what comes before or after them, without including the preceding or following characters in the match. However, they are not used in this regex.

## Author

I am Kyle Cosaert, a future software developer. If you have any questions or comments for me please visit my github. https://github.com/KyleCosaert