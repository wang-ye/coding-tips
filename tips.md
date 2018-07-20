## String Splitting
If you want to split a string by all the possible delimiters, just call
```python
your_str.split()
```
without any parameters.

If you want to split based on multiple delim, for example ',', ':' and ' ', then call
```python
import re
filter(None, re.split(',|:| ', your_str))
```