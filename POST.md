# Regex-ation Tutorial 

Regex is a regular expression or "rational expression" that specifies search patterns. This is used to find and replace the operations that are in the strings. Some capatibilities with certain languages will be Python, C, C++, Java, and Javascript all which work with Regex. It is a standard textual syntax for representing patterns for matching text. Regex originated in 1951  to describe regular languages that were not new to mathematical notations known as a regular event. Some common uses that Regex is used for is data validation, data scraping, data wrangling, simple parsing, the production of syntax highlighting systems and others. To Summarize, 

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

``` A Regex component is a syntax that specifies a pattern in a log file, this is configed by a WebTrend Analytic. These are useful for flexible and pattern matching, theere are basic elements which are   .   \ followed by a character   $   ^  []   |   (). As for Qualifying characters these make up   *   +   ? ```

### Anchors

``` An anchor in regex is a token that doesn't match any character, but says or asserts something about the string. Anchors don't match any character at all such as ^a to abc matches a. Where as ^b does not match abc. The reason anchors are important as if you have an input in a Perl script it is used to see if the user has entered an integer in order to determine a successful match ```

### Quantifiers

``` A quantifier in regex is an instance of a character, group or character class that is displayed as an input for a match to be made. These greedy quantifiers are used by .Net   *   +   ?   { n }   { n ,}   { n ,  m } Lazy Quantifier   *?   +?   ??   { n }?   { n ,}?   { n , m }? ```

### Grouping Constructs

``` Delineate a subexpression of the regular expression and capture its substring of that input. Grouping constructs can be utilized by matching a subexpression. Apply a quantifier to a subexpression that has multiple regular expressions. Subsexpression is return by Match.results and regex.replace. Retrieve subexpressions from Match.group and process seperately by match text. ```

### Bracket Expressions

``` A matching square bracket that shall match a specific set of single characters. It may also match a multi character collating element, based on a non empty set of list expressions. These brackets can either represent () or they can be [] ```

### Character Classes

``` Character classes in regex are a set of character enclosed within these square brackets. These character will match a single character from a given input string.  ```

### The OR Operator

``` The OR operator in Regex is to be able to match an expression or a character on the | side of its operator. ```

### Flags

``` An optional flag or pattern from regex is as follows g, i, m, u, s, y. This is used as a pattern to search and replace text as an object found in javascript, there are long syntaxes and short slashes that are used. These method patterns are also found with exec(), test(), match(), matchAll(), replace(), replaceAll(), search(), and split() for methods of String. ```

### Character Escapes

``` The regex that are considered character escapes are *, +, | anchors: ^, $ Others ., \. The \ is considered to be an escape code, that tells the software to restore is original meaning of its character. It is found useful for text files because it can manipulate the text string and search. This can be done with several dozen lines of code, its supported by Perl, Python PHP and Javascript, but is not as easy as most people may believe. ```

## Author

``` My name is Chase Olshen and I am from California I am a determined and motivated individual that is energized in the field of Technology doing Software Engineering. This is my Regex Tutorial for others to learn more about its uses. https://github.com/pcchase617 ```

