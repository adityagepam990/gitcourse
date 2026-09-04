# Syntax for Headlines:
Also, Headline level 1
======================

## Headline level 2
-------------------

### Headline level 3
#### Headline level 4
##### Headline level 5
###### Headline level 6
-----------------------

# Special Styles
--------
**bold**
__bold__

*italic*
_italic_

--strike throughv1--
----
~~strikethroughv2~~

> Quotation

--- 
Horizontal Rule
*** 
Asterisks 
____ 
Underscores 
---------------------
# Links
---
https://www.linkedin.com
> Better to use [Website](https://www.linkedin.com "LinkedIn"] this website
[LinkedIn]
[learning][1]
[linkedin]: https://wwww.linkedin.com
[1]: https://www.linkedin.com/learning

----
# Images
---
![Fruit bowl](https://www.californiastrawberries.com/rainbow-fruit-salad/)
There are other ways. **Find out how to link images while in repo**

===
# Code Insertion
***
```python
def romantoInt(s: str) -> int:
  roman_map = {'I': 1, 'V': 5, 'X': 10, 'L': 50, 'C': 100, 'D': 500, 'M': 1000}
  total = 0
  length = len(s)

  for i in range(length):
    if i+1 < length and roman_map[s[i]] < roman_map[s[i+1]]:
      total -= roman_map[s[i]]
    else:
      total += roman-map[s[i]]
  return total
```
## *Example Usage*
***
```python
print(romantoInt("III"))
print(romantoInt("LVII"))
print(romantoInt("MCMXCV"))
```
*****


