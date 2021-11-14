# Reg-ex Tutorial 
Reg-ex



## Summary

Regex is a string of text. The Regex matches fragments.  


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
Anchors cause for a match or fail depending on how the string is created.  These anchors are  ^ $ /A \Z \z \G \b \B 
<ul> 
<li> <b> ^ </b>Must start at the beging of the string </li>
<li> <b> $ </b> This match must occur at end of string or before a new line (\n)</li>
<li> <b>\A </b> This match must pass at the begining of the string </li>
<li> <b>\Z </b>this match must pass at the end of the string or before the end of the line /n</li>
<li>  <b> \z</b> This match happens at the end of the string </li>
<li> <b> \G </b> This match has to occur at the point where the previous match ended </li>
<li> <b> \b </b> This match happens at a boundary between an alphanumeric or nonalphanumeric </li>
<li> <b> \B </b> The match happens at the \b boundary</li>
</ul>

### Quantifiers
A quantifer specifies how many instances of the previous element must be present in the input string
### OR Operator
The OR operator is a grouping expression.  The syntax is as follows (this|that)
### Character Classes
A character class defines a set of characters. 
### Flags

### Grouping and Capturing
<ul>
<li> <b>matched subexpressions </b> reg-ex pattern that use parentheses within the reg-ex <ol><li> <b> 1</b> Uses a backreference construct within the reg-ex using the syntax \num, where num is the ordinal number of the subexpression</li>
<li> <b> 2 </b> The matched subexpression is backreferenced construct using the syntax \k < name > or \k < number > </li>
<li> <b> 3 </b> </li>
<li> <b>4  </b> </li></ol> </li>
<li> <b> Named Matched Subexpression</b> A reg-ex pattern illustrates how numbered and named groups can be referenced. The syntax is as follows (? < name >subexpression) or (? 'name' subexpression) </li>
<li> <b> Balancing Group Defintions</b> A balanceing group definition deletes the previous defined group.  Syntax as follows (?< name1-name2 >subexpression)
or:
(?'name1-name2' subexpression) </li>
<li> <b>Noncapturing Groups </b> The group construct does not capture the substring that is matched by a subexpression (?:subexpression)  </li>
<li> <b> Group Options</b></li>
<li> <b> Zero-width positive lookahead assertions</b></li>
<li> <b> Zero-width negative lookahead assertions </b></li>
<li> <b> Zero-width positive lookbehind assertions </b></li>
<li> <b> Zero width negative lookbehind assertions</b></li>
Atomic Groups 
</ul>

### Bracket Expressions
Square brackets match what is within the string ie [D] will find the `D` within the string. 

### Greedy and Lazy Match

### Boundaries
match postitions by using the \b 
### Back-references
A backreference allows a previous matched subexpression to be identified later in the same expression. 
### Look-ahead and Look-behind
Look-ahead asserts that what follows the current postions. /n 
llok-behind asserts that what precedes the current position. 
## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)

## Citations 
Resreached used in this assignment was. 

https://docs.microsoft.com/en-us/dotnet/standard/base-types/regular-expression-language-quick-reference#quantifiers

http://www.rexegg.com/regex-boundaries.html#anchors

https://webagility.com/posts/the-basics-of-regex-explained