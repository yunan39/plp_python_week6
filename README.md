# plp_python_week6
Week 6 Assignment
Python Week 6 Assignment
safe_tools.py: Implements robust utility functions (`safe_divide`, `safe_number`, and `get_field`) protected by try/except blocks to handle errors gracefully without crashing.

Reflection
An `if` check cannot catch an error like converting `"abc"` to an integer on its own because executing `int("abc")` directly raises a `ValueError` and crashes the program *before* any conditional check can evaluate it. Try/except blocks are required to safely catch the runtime exception after it occurs.
