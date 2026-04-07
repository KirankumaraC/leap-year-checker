# Leap Year Checker 🗓️

A simple Python program to check whether a given year is a leap year or not.
Description
This project determines whether a given year is a leap year based on standard leap year rules.
---
Leap Year Rules
A year is considered a leap year if:
* It is divisible by 4
* It is NOT divisible by 100, unless
* It is also divisible by 400
---
How to Run
```python
def is_leap_year(year):
    return (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0)

year = int(input("Enter a year: "))

if is_leap_year(year):
    print(f"{year} is a leap year!")
else:
    print(f"{year} is not a leap year.")
---
Example Output
```
Enter a year: 2024  
2024 is a leap year!
```
```
Enter a year: 2023  
2023 is not a leap year.

This project is free to use for learning purposes.
