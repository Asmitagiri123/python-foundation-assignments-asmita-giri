# Day 10: Comprehensions, Iterators, Generators & Functional Programming

## Topics Covered

- Loops & Control Flow
- Python Collections : Lists, Dictionaries, Sets, and Nested Dictionaries
- Comprehensions : List comprehension, Dictionary comprehension, Generator expressions
- Data Processing & Built-in Functions : sum(), len(), max(), sorted(), isinstance(), range()
- Dictionary Operations & Practical Programs : CRUD operations, .items(), .values(), user input, and menu-based programs.


## Exercises

1. Batch Processor
2. Retry Simulation
3. Clean Numeric Values
4. Sales List Analysis
5. Dataset Comparison
6. Student Score Dictionary
7. Nested Order Summary
8. Stretch: Contact Book Menu

## How to Run

```bash
python exercise-01-batch-processor.py
```

## What I Learned

- Using range() with the modulo operator is a simple way to do something every few steps, like showing a checkpoint after every third batch
- while loops with break are great for retry situations, since you can stop as soon as something works instead of always looping a fixed number of times
- isinstance() helps you check if a value is actually the type you expect, which is really handy when a list has a mix of good and bad data
- List comprehensions can do the same thing as a loop with an if condition, just in one shorter line, and it starts to feel natural after using it a few times
- Set operations like union, intersection, and difference make it really easy to compare two groups and see what's shared or different between them
- Dictionary comprehensions work just like list comprehensions but build key-value pairs instead


## Challenges Faced

- Had to think a bit more carefully about the retry exercise, since putting break in the wrong place would either skip an attempt or run one extra time
- Got confused between max(student_scores) and max(student_scores, key=student_scores.get) at first, since the first one just compares names alphabetically instead of actual scores
- Forgot that sets don't keep a fixed order, so the output looked slightly different each time I ran the same code, which threw me off until I understood why
