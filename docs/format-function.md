# Format function

The `format()` helper function merges values into a literal string template, without the need for messy string concatenation.

`Example:`

```python
medicine = "Paracetamol"
dosage = 5
duration = 4.5

# 3 different examples

instructions = '{} - Take {} ML by mouth every {} hours'.format(medicine, dosage, duration)
print(instructions)

instructions = '{2} - Take {1} ML by mouth every {0} hours'.format(medicine, dosage, duration)
print(instructions)

instructions = '{medicine} - Take {dosage} ML by mouth every {duration} hours'.format(medicine = Paracetamol, dosage = 10, duration = 6)

print(instructions)

# Output:
Paracetamol - Take 5 ML by mouth every 4.5 hours
4.5 - Take 5 ML by mouth every Paracetamol hours
Paracetamol - Take 10 ML by mouth every 6 hours
```

## f-strings

The format() function is powerful and flexible. You can achieve the same functionality, with less typing, by using formatted string literals, also known as f-strings.

`example:`

```python
name = 'World'
message = f"Hello, {name}."
print(message)

count = 10
value = 3.14
message = f"Count to {count}.  Multiply by {value}."
print(message)

# Output:
Hello, World.
Count to 10.  Multiply by 3.14.
```

## Reference

[Format () function](https://docs.microsoft.com/en-us/learn/modules/python-format-strings/4-exercise-format-function)
