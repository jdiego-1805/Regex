# Regex

Regex is a versatile tool for pattern matching and text manipulation, offering concise syntax and powerful features to search, extract, and validate specific patterns within text, enhancing data processing and analysis.

## Summary

This will go over how the "matching an HTML tag' regex and it's components are used so you can better understand them. `/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/`

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

The html tag uses (`^, and $`). The ^ by default must happen at the beginning of the string, and in multiline mode it must occur at the beginning of the line.

### Quantifiers

The different type of quantifiers that are on the html tags are the (`*, ?, and +`). The * means it is used to match 0 or more of the previous, ? matches 0 or 1 of previous, and the + matches 1 or more of the previous.

### Grouping Constructs

The groups that are used in the html tag are `(...)` that is used to capture groups in the enclosed pattern.

### Bracket Expressions

The (`[a-z]`) bracket expressions matches any lowercase letter between the specified element, in this case a-z.

### Character Classes

The character classes include (`\s`) which matches a whitespace character.

### The OR Operator

The (`|`) is the OR operator that separates alternative patterns.

### Character Escapes

The character escapes, (`\<, \/`), matches the literal character `<` and `/`.

## Author

Thank you for your time, if you want to go to the link, here it is. https://github.com/jdiego-1805/Regex/blob/main/Regex.md