# Truncate at Wordbreak - Javascript
Truncates a String at the last word break, with the option to append text to the final String - JavaScript

Variables:

str - The original String you want truncated
len - The max length the final, truncated string can be (this takes into account the appended text)
append - Any optional text you would like to append after you truncate str.

Notes:

If text cannot be truncated (the len isn't long enough to reach the first space (with or without your appended text), the function will return the original string. 
