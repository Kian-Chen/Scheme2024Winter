#   Regex

## Regular Expressions

Regular expressions are a sequence of characters that define a search pattern. They are used to match, locate, and manipulate text. In Python, regular expressions are implemented using the `re` module.

Here are some examples of regular expressions:

- `r"hello\s+world"`: Matches the string "hello world" with any number of spaces between "hello" and "world".
- `r"\d+"`: Matches one or more digits.
- `r"\w+"`: Matches one or more word characters (letters, digits, and underscores).
- `r"[\w\s]+"`: Matches one or more word characters or spaces.
- `r"[\w\s]+@[\w\s]+\.[\w]{2,3}"`: Matches an email address with a username, domain name, and top-level domain.


## Using Regular Expressions in Python

1. Import the `re` module:

```python
import re
```

2. Use the `re.search()` function to search for a pattern in a string:


```python
string = "The quick brown fox jumps over the lazy dog"
pattern = r"fox"
match = re.search(pattern, string)
if match:
    print("Match found:", match.group())
else:
    print("Match not found")
```

3. Use the `re.findall()` function to find all occurrences of a pattern in a string:


```python
string = "The quick brown fox jumps over the lazy dog"
pattern = r"\b\w{3}\b"
matches = re.findall(pattern, string)
print("Matches:", matches)
```

4. Use the `re.sub()` function to replace all occurrences of a pattern in a string with a new string:


```python
string = "The quick brown fox jumps over the lazy dog"
pattern = r"fox"
new_string = re.sub(pattern, "cat", string)
print("New string:", new_string)
```

## Resources

- [Email Regex](https://emailregex.com/)
- [Regex 101](https://regex101.com/)
- [Python Regular Expressions](https://docs.python.org/3/library/re.html)
- [Regular Expression HOWTO](https://docs.python.org/3/howto/regex.html)
- [Regular Expressions in Python](https://www.pythonforbeginners.com/regex/regular-expressions-in-python)