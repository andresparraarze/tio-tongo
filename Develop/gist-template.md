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
They are used to comminucate the amount of characters that is expected to be received, these specify how many instances of a group, character class or just a character have to be present in order to fin a match, these will try to match as many as possible, the characters '+?{}' when they are located on regular expressions they work as quantifiers and the '?' is dictating the expression to be matched, we use the operaton to distingish the format we will use.

### OR Operator
This is defined with the element '|', this indicates that the value can be any of the components that it has next to it.

### Character Classes
These are components that tell us what we should expect according to what we put inside '[]' that will be expected to be received. 

### Bracket Expressions
These look and match for any character that is located in the square brackets an example to this would be [yY] [eE] [sS] which would look and match yes and YES.

### Greedy and Lazy Match
In this case a greedy match tries to catch an element as much as possible meanwhile the lazy match tries to get the element in a very small amount of tries, the lazy quantifier is expressed as '?' and we can make it greedy by adding one more '?'

## Author
This would be Andres Parra Arze from Bolivia - github name andresparraarze