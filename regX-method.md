# Matching an Email

I have developed a tutorial that briefly explains how a regular expression, Regex, work. In this tutorial we are going to be looking at matching an Email.

## Summary

For this walk through tutorial we are going to be looking at this example below:

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

This expression is used to validate the structure of an email address. One or two lines of code can handle a wide variety of parameters and can easily be tweaked as needed.

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

All regular expressions share the same starting `^` and ending `$` anchor of a string. There are other achors that can be used provided below:

* `^` By default and in multiline mode, the match must occur at the beginning of the line or string.
    * `\A` Is also used as a starting anchor for a string but it can't support multi line mode.

* `$` By default and in multiline mode, the match must occur at the end of the line/string or before `\n` in a line/string.
    * `\Z` Is also used at the end of a string or before `\n` at the end of the string but ignores multi line option.
    * `\z` The match must occur at the end of the string **ONLY**. Unlike `\Z` and `$` this doesn't match `\n` at the end of a string.

Word Boundary `\b` and Non-word Boundary `\B`:

* `\b` The match has to occur on a boundary between a word character and a non-word character. (Word characters consist of alphanumeric characters and underscores)
* `\B` This is the opposite of the `\b` anchor, it specifies that the match must not occur on a word boundary.

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

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
