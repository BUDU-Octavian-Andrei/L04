# Bug reports for exercise2.py

Line: 8
Problem: is_valid_password: the docstring says "at least one digit", but the current code uses `any(c.isdigit() for c in password)`, which is correct, so no bug. However, upon closer inspection, the function is logically correct. But wait — the docstring says "at least 8 characters and at least one digit", and the code correctly checks both. There is no bug here.

Wait — rechecking: the function is correct. All conditions are properly checked. No bug found.

Line: 12
Problem: clamp: the docstring says "x, limited to the range from low to high", but the current code uses `max(low, min(x, high))`, which correctly ensures x is between low and high inclusive. This is correct. No bug.

No bugs found. The code matches the docstrings.

(No bug report needed.)
