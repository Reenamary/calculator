A simple string-based calculator implemented in Ruby on Rails. 
It parses a string input containing numbers and delimiters, then returns the sum of the numbers.

1. Handle Multiple Numbers
   Supports any number of comma-separated numbers:
   ```Enter 1,2,5 to get 8
2. Support for Newline as Delimiter
    Supports newlines as delimiters:
    ```Enter 1\n2,3 to get 6
3. Support for Custom Delimiters
    Allows custom delimiters defined at the start of the string:
    ```Enter //;\n6;2;4 to get 12
4. Negative Numbers Throw an Exception
    Throws an exception for negative numbers:
    ```Enter 1,-2,3 to get "Negative numbers not allowed: -2"
