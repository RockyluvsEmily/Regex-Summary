# Regex Summary

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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
Anchors are used to match specific positions in a string. The most common anchors are the caret ^ (matches the start of a line) and the dollar sign $ (matches the end of a line).

Example: ^Start of line$

### Quantifiers
Quantifiers specify how many times a preceding element should occur in a regex pattern. They can be used to match characters or groups of characters multiple times.

Example: \d{3}-\d{4}

### Grouping Constructs
Grouping constructs allow you to group multiple characters together and apply operators or modifiers to them as a unit. They are often used to capture or extract specific portions of a match.

Example: (John|Jane) Doe

### Bracket Expressions
Bracket expressions, also known as character classes, are used to specify a set of characters that you want to match. They allow you to define a range of characters or a specific set of characters that should be matched.

Example: [A-Za-z0-9]

### Character Classes
Character classes are similar to bracket expressions and are used to match a single character from a specific set of characters. They provide shorthand notations to match common character sets like digits, letters, or whitespace.

Example: \w+

### The OR Operator
The OR operator, denoted by the pipe symbol |, allows you to specify multiple alternative patterns. It matches either the pattern on its left or the pattern on its right.

Example: cat|dog


### Flags
Flags modify the behavior of a regex pattern. They are added at the end of the pattern and can enable case-insensitive matching, global matching, and other options.

Example: /dog/gi

### Character Escapes

Character escapes are used to match characters that have special meanings in regex. By preceding a special character with a backslash \, you can match the literal character instead of its special meaning.

Example: \d{2}-\d{2}-\d{4}

## Author

Presented by Dewayne Cavendish 
https://github.com/RockyluvsEmily/Regex-Summary