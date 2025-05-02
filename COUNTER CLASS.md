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
reg no:212223070023
name:Saran Krishna P S
class Counter:
    def __init__(self):
        self.count = 0

    def increment(self):
        self.count += 1

    def get_count(self):
        return self.count

c = Counter()
c.increment()
c.increment()
c.increment()
print("Counter value:", c.get_count())

```

### OUTPUT
![image](https://github.com/user-attachments/assets/1c377940-c615-4734-8134-110cc8c43fe2)


### RESULT
thus the program is executed successfully.
