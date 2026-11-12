# Bug reports for exercise1.py

Line: 3
Problem: is_even: it returns True for odd numbers (like 1, 3, 5) because it checks n % 2 == 1, but the docstring says it should be true for even numbers. For even numbers, n % 2 should be 0.
Example: is_even(4) returns False, expected True.
Fix: return n % 2 == 0

Line: 8
Problem: rectangle_area: it returns the sum of width and height, but the docstring says it should return the area, which is width times height.
Example: rectangle_area(4, 5) returns 9, expected 20.
Fix: return width * height

Line: 12
Problem: double: it returns n + 2, but the docstring says it should return twice the number, i.e., n * 2.
Example: double(5) returns 7, expected 10.
Fix: return n * 2
