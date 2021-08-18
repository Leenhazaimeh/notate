# Automation

# Python Regular Expression
Regular Expressions, often shortened as regex, are a sequence of characters used to check whether a pattern exists in a given text (string) or not.
If you've ever used search engines, search and replace tools of word processors and text editors - you've already seen regular expressions in use.

They are used at the server side to validate the format of email addresses or passwords during registration, used for parsing text data files to find, replace, or delete certain string, etc.

You will start with importing re Python library that supports regular expressions Then you will see how basic/ordinary characters are used for performing matches Next, you'll learn about using repetitions in your regular expressions

you have to import this module with the help of import:

`import re`

# Wild Card Characters: 
## Special Characters
Special characters are characters that do not match themselves as seen but have a special meaning when used in a regular expression.

For simple understanding, they can be thought of as reserved metacharacters that denote something else and not what they look like.

But before you do, the examples below make use of two functions namely: search() and group().

. A period. Matches any single character except the newline character.