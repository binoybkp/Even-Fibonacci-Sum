# Project Euler - Even Fibonacci Numbers

Sum of even Fibonacci terms not exceeding 4,000,000.

**Answer: 4613732**

## Run

```bash
python solution.py
```

## Test solution using below file

```bash
pytest test_solution.py
```

## Approach

Iterate through the Fibonacci sequence, adding each even term to a total. Stop once a term exceeds the limit. Uses two variables to avoid storing the full sequence
(used c as third valiable for keeping track of 'a' value, we can avoid this variable if we update a&b togethor, I kept it for simplicity).
