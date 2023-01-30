# Regex Phone Number Tutorial

Have you ever heard of regular expressions(regex)? If not, then today you will have the oppurtunity to learn about what regex is and how you can break it down into sections to better understand the purpose of a regular expression.

## Summary

Below is how to create a regular expression for a phone number.
```
/(?:(\+1[ -])\(?(?<areacode>\d{3})\)[ -]?(\d{3})[ -]?(\d{4})/gm
```
At a first glance this might look confusing. So I am going to break this down for you.

## Table of Contents

- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

---

## Regex Components

Regex components are a sequence of characters that define the search pattern and there are multiple components of regex. To verify whether a given input is a valid phone number we need to match it with the following Regex to match a phone number id − 
```
/(?:(\+1[ -])

\(?(?<areacode>\d{3})\) [ -]?

(\d{3}) [ -]?

(\d{4})/gm"
```
The first Group represents the Country Code for the United States (+1).

The areacode Group represents the area code of the phone number.

The third Group represents the middle three digits of the phone number.

The fourth Group represents the last four digits of the phone number.

---

