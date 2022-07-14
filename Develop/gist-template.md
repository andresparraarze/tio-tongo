# Tutorial Matching a hex value, regex

These are patterns that tend to be used to create character combinations which are then matched in strings, usually the 'not' is expressed as '^'. As an example 'a' which is match lowercase 'a' if it is displayed as '^a' it would mean 'dont match lowercase a'

## Summary

/^#?([a-f0-9]{6}|[a-f0-9]{3})$/, I will be describing components that are used to match hex values, colors can be described as hexadecimals which can give the exact color to a computer, creating more accuracy, this is usually a six digit code that starts with a # sign and this defines these colors that can be used for styling on a computer device or program.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors
These are used to get a match of a position such as between, before or after characters, $ matches after the last character in a string, an example wwould be 'c$' which is matching in abc, but a$ doesnt match, the '^' matches the posititon before the first character of the string, so the example would be '^a' in abc matches a, but '^b' doesnt matchg since 'b' cant be matched after the start of a string.

### Quantifiers

### OR Operator

### Character Classes

### Bracket Expressions

### Greedy and Lazy Match

## Author
This would be Andres Parra Arze from Bolivia - github name andresparraarze