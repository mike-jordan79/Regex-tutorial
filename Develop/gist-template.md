# RegEx Tutorial: linking a URL
A regex, or regular expression is lines of code that implements variables and allows the developer to pull info from a string. These lines can be adjusted based on the users needs. An example of this would be pulling text from 

## Summary

````/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/````
<br /> <br />

This regex should match urls from websites based on text, and is primarily used to verify information. There are five main capture groups, the anchors, the character classes, quantifiers, bracket expressions, and greedy and lazy matches. Translated, this should read in English as, “find a string of information that contains “https:// “ where the s is optional. The string must also have a token with randomized length of characters a-z. It should also follow with a token that contains 2-6 characters from a-z including dots. It may also contain a token that has a slash followed by numbers, spaces, letters, dots and/or dashes.” The beginning and ending slashes in the string represent the beg. and end of the string.


- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

## Regex Components

### Anchors
Anchors are used to tie the regex to an expression, so it does not appear as randomized characters. In this particular regex, the symbols ^ and $ show the beginning and end of this string. 
<br /> <br />
````^(https?:\/\/)?```` and ````*\/?$````
### Quantifiers

### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

My name is Mike Jordan, and I am studying to become a softeare engineer. I hope to graduate from this class on November 17th, and enter the software engineering field. I am excited to continue learning and growing as an engineer. 
