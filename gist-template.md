# Matching an email

A regular expression is a sequence of characters that match an email.

## Summary
In this tutorial we will be going over how to find matches in strings. We will be using the following regular expression:

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
We have three major components to a regular expression:

the first is to match the beginning of the email. 
^([a-z0-9_\.-]+)

The second is to match the @ in an email. 
@([\da-z\.-]+

The final part is to match the end of the email.
.([a-z\.]
### Anchors
The anchor of this regex is the first and final // this set the bound of the regex.

### Quantifiers
The quantifiers are used to specify how many times the regex should match.
In this case we are using [a-z0-9_\.-]+ to match the first part of the email. a-z any letter 0-9 any number 



### OR Operator
We are using the OR operator to match the second part of the email. The beginning of the email can use any letter or number combination.
### Character Classes
We have several character classes to use in our regex.
sequence of letters or number in the first third ie ([a-z0-9_\.-]+)

### Flags
We are not using flags in this tutorial.
### Grouping and Capturing
We aren't using grouping or capturing in this tutorial.
### Bracket Expressions
We have three braket expressions to use in our regex.
These braket expressions are used to create the three expected parts of an email address.
### Greedy and Lazy Match
At the beginning of the regex we are using the greedy match of a carrot ^ to grab any match of number or letter. 
### Boundaries
The boundaries we used are only the // at the begging and end of the regex.
### Back-references
There are no back references in this tutorial.
### Look-ahead and Look-behind
No look-ahead or look-behind in this tutorial.
## Author

Check out my github to get to know my projects. <a href="https://github.com/megwatson88"> Github </a>
