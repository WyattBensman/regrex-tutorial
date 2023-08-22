# regrex-tutorial

A deep-dive on how to validate email addresses using the email regrex pattern.

## Summary

The regrex regular expression for matching an email simplifies the process of validating & matching email addresses. This pattern appears as: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

### Anchors

Anchors specify the position of a match in the input string.

The anchors that appear in this expression are the '^' & the '$'. The '^' appears at the start of the expression making sure that match occurs at the beginninig of the email address. The '$' appears at the end of the expression and ensures that match ends with the domain portion of an email.

### Quantifiers

Quantifiers coontrol how many times a preceding element can occur.

The quantifiers in the email regrex is the '+' and the '{2, 6}'. The '+' allows the preceding characters to appear one or more times before the '@' symbol. The '{2, 6}' tells us that the domain extentsion must be between 2 & 6 charcters.

### OR Operator

The OR operator, '|', allows you to match two alternatives.

The OR operation is not used inside in the email regrex.

### Character Classes

Chracter Classes help define a set of characters able to match at a position.

The Character Classes used in the email regrex is the: [a-z0-9_\.-] and [\da-z\.-] character classes to help specify what characters are approriate to use.

### Flags

Flags are used to modify the expressions behavior of searching.

Flags are not used when dealing with the email regrex.

### Grouping and Capturing

Grouping & Capturing is a way to have multiple characters treated as a single unit.

Grouping & Capturing is utilized when using parentheses '()'. In the email regrex, there are three different grouping scenarios: username, domain name & the domain extension.

### Bracket Expressions

Bracket Expressions are used in the email regrex to specify valid characters.

### Greedy and Lazy Match

Greedy matching in regular expressions tries to match as much text as possible while still allowing the entire pattern to match. Lazy Matching matches as little as possible, while still allowing the overall pattern to match.

Greedy matching is added by default & matches as much as possible while still allowing the entire pattern to match.

Lazy Matching is not used in the email regrex.

### Boundaries

Boundaries in regular expressions are used to specify the edge of a word or non-word entity.

Boundaries are not used in the email regrex.

### Back-references

Back-references in regular expressions allow you to match the same text that was previously matched by a capturing group.

Back-references are not needed in the email regrex.

### Look-ahead and Look-behind

These assertions in regular expressions enable you to check if a pattern is either followed by or preceded by another pattern, without including the latter in the match.

Look-ahead and Look-behind is not used in the email regrex.

## Author

Wyatt Bensman
Email: Wyattbensman5@gmail.com
GitHub Repository: https://github.com/WyattBensman
