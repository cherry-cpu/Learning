
---
# 2026-07-22 23:29 
# Basics

### Data Types
int, str, bool, float
```
age = 25                  # Integer (int)
price = 19.99             # Floating-point number (float)
name = "Alice"            # String (str)
is_active = True          # Boolean (bool)``
```
### Arithmetic Ops
+,-,/, * ,%
```
addition = 5 + 3          # Result: 8
division = 10 / 3         # Result: 3.3333... (always float)
floor_division = 10 // 3  # Result: 3 (drops decimal part)
modulus = 10 % 3          # Result: 1 (returns the remainder)
exponent = 2 ** 3         # Result: 8 (2 raised to the power of 3)

```
### Input & Output
print() , input()
```
# Output a message
print("Hello, World!") 

# Input always captures data as a string
user_input = input("Enter your name: ") 

# Type conversion turns strings into numbers
user_age = int(input("Enter your age: ")) 

```

---
# 2026-07-23 22:36

### Conditional Statements (Control Flow)
if, else, elif

```
score = 85
if score >= 90:
	print("Grade: A")
elif score >= 80:
	print("Grade: B")
else:
	print("Grade: C")
```

### Loops
for,while
```
# Prints numbers from 0 to 4
for i in range(5):
    print(i)

# Loops until a target value shifts
count = 0
while count < 3:
    print("Looping...")
    count += 1
```
