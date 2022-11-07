# Title (replace with your title)

Regex Module

## Summary

Summary
Matching an Email – /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)

Extra 
- [OR Operator](#or-operator)
- [Flags](#flags)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

An anchor is case sensative and will represent either the beggining of a string or the ending of a line. It will determing the position of the string to be matched. 

### Quantifiers

A quantifier will tell the amount of letter, number or charecters belonging in the desired output. for example if i have "win alot" with a quantifier of 3 i will recieve a match with either "win" or "alo."

### Character Classes

A character class is a specific class set by square brackets to recieve an individual return. example [5] will have to come back as a number. 

### Grouping and Capturing

The grouping construct puts together like strings to then be broken up and captured. Typically grouping would hold will hold two different categories of capturing and non capturing. The captured are similar sequences for for reuse while the opposite remains true for non-capturing. 

### Bracket Expressions

these are charecters set into square brackets that are needing to be matched. It can be seen as on outline for what kind of chararecters should be accepted. 

### Greedy and Lazy Match

Greedy - matching with as many possible arrangements with given instruction as possible.

Lazy Match - matching with as little arrangements when possible

Extra

### OR Operator

The OR operater is a logic understood by regex that will match with either a number or character. 

### Flags

A flag lookes through the entire string to find all applicable matches.

### Boundaries

The beginning and the ending of a phrase making a match possible. 

### Back-references

Back-references refer to groups captured prior in the same expression. 

### Look-ahead and Look-behind

Look-ahead helps add to what is to come and Look-behind helps add after what is there. 

## Author

McLee0218

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
