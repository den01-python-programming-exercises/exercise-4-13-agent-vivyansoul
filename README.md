[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=4414973&assignment_repo_type=AssignmentRepo)
# Exercise 4.13 Agent

The exercise template defines an Agent class, having a first name and last name. A `printout` method is defined for the class that creates the following string representation.

```python
bond = Agent("James", "Bond")
bond.printout()
```

```plaintext
My name is Bond, James Bond
```

Remove the class' `printout` method, and create a `def __str__(self)` method for it, which returns the string representation shown above.

The class should function as follows.

```python
bond = Agent("James", "Bond")

print(bond)

ionic = Agent("Ionic", "Bond")
print(ionic)
```

```plaintext
My name is Bond, James Bond
My name is Bond, Ionic Bond
```
