# Regex

## Summary

Regular expressions are sequences of characters that form a search pattern, primarily used for string matching and manipulation. Here's a basic regex snippet to get us started: `^([a-z0-9]{5,})$`. This pattern matches a string that starts and ends with 5 or more lowercase letters or numbers.

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
Anchors (`^`, `$`) are used to specify the start and end of a line. For example, `^text` matches any string that starts with "text".

### Quantifiers
Quantifiers (`*`, `+`, `?`, `{n}`, `{n,}`, `{n,m}`) specify how many instances of a character or group must be present for a match. For instance, `a{2,4}` matches "aa", "aaa", or "aaaa".

### OR Operator
The OR operator (`|`) allows for matching multiple patterns. For example, `cat|dog` matches "cat" or "dog".

### Character Classes
Character classes (`\d`, `\w`, `\s`, `.`) match specific types of characters. For example, `\d` matches any digit.

### Flags
Flags alter how the regex is processed. Common flags include case insensitive (`i`), global match (`g`), and multiline (`m`).

### Grouping and Capturing
Grouping (`()`) is used to combine parts of a regex and capture them for future use. For example, `(abc)+` matches one or more repetitions of "abc".

### Bracket Expressions
Bracket expressions (`[]`) match any one character from a set. For example, `[abc]` matches either "a", "b", or "c".

### Greedy and Lazy Match
Greedy quantifiers (like `*`) match as much as possible, while lazy quantifiers (like `*?`) match as little as possible.

### Boundaries
Boundaries (`\b`, `\B`) indicate word limits. `\bword\b` matches "word" when it's a whole word.

### Back-references
Back-references (`\1`, `\2`, etc.) refer to previously captured groups. For example, `(a)\1` matches "aa".

### Look-ahead and Look-behind
Look-ahead (`(?=...)`) and look-behind (`(?<=...)`) assertions specify a pattern that must follow or precede a match without including it in the match.

## Author

Bryan Tran [GitHub](https://github.com/iambryantran).
