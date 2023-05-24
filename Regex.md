# Regex

Introductory paragraph (replace this with your text)

## Summary

This will go over how the "matching an HTML tag' regex and it's components are used so you can better understand them. `/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/`

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

The html tag uses (`^, and $`). The ^ by default must happen at the beginning of the string, and in multiline mode it must occur at the beginning of the line.

### Quantifiers

The different type of quantifiers that are on the html tags are the (`*, ?, and +`). The * means it is used to match 0 or more of the previous, ? matches 0 or 1 of previous, and the + matches 1 or more of the previous.

### Grouping Constructs

The groups that are used in the html tag are (`[a-z]`) that is used to match a character from within a specified range.

### Bracket Expressions

### Character Classes

The character classes include (`\s`) which matches a whitespace character.

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
