# Exp.No:30  
## COUNTER CLASS

---

### AIM  
To write a Python program to create a `Counter` class that can increment the value of a counter.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Counter` class.**
   - Initialize the `current` variable with 0.
3. **Define the `increment()` method** to increment the value of `current` by 1.
4. **Define the `value()` method** to return the current value of `current`.
5. **Define the `reset()` method** to reset the `current` value back to 0.
6. **Create a `counter` object** of the `Counter` class.
7. **Call the `increment()` method** three times to increment the counter.
8. **Call the `value()` method** and print the result to show the current counter value.
9. **End the program.**

---

### PROGRAM

```
class Cat:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    def info(self):
        print(f"I am a cat. My name is {self.name}. I am {self.age} years old.")
    def make_sound(self):
        print("Meow")
class Cow:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    def info(self):
        print(f"I am a Cow. My name is {self.name}. I am {self.age} years old.")
    def make_sound(self):
        print("Moo")
cat1 = Cat("Kitty", 2.5)
cow1 = Cow("Fluffy", 4)
for animal in (cat1, cow1):
    animal.make_sound()
    animal.info()
    animal.make_sound()
```

### OUTPUT
<img width="801" height="264" alt="{6E9476EC-56EE-4DD2-BD08-0930AFC42893}" src="https://github.com/user-attachments/assets/c9fcfcb9-69f4-4dd8-93fd-cac606c0f957" />

### RESULT
Thus, the python code is written and executed successfully
