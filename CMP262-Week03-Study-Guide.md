# CMP 262 – Data Science Programming

## Week 3 Study Guide: Lists and Tuples

Use this guide to review the main ideas from class before completing Week 3, Lab 1.

---

## 1. What Is a List?

A **list** stores multiple values in one variable.

Example:

```python
colors = ["red", "blue", "green"]
```

Lists use square brackets: `[]`.

Lists are **mutable**, which means their values can be changed after the list is created.

---

## 2. Accessing List Items

Each item in a list has an index.

```python
colors = ["red", "blue", "green"]
```

Indexes:

- `colors[0]` → `red`
- `colors[1]` → `blue`
- `colors[2]` → `green`

Python starts counting at **0**.

You can also use negative indexes:

- `colors[-1]` → last item
- `colors[-2]` → second-to-last item

---

## 3. List Slicing

Slicing allows you to get part of a list.

```python
numbers = [10, 20, 30, 40, 50]
```

Examples:

```python
numbers[0:3]
```

Result:

```text
[10, 20, 30]
```

You can also write:

```python
numbers[:3]
```

The ending index is **not included**.

---

## 4. Changing a List Item

Because lists are mutable, you can replace a value using its index.

```python
colors = ["red", "blue", "green"]
colors[1] = "yellow"
```

The list becomes:

```text
['red', 'yellow', 'green']
```

---

## 5. Adding Items to a List

Use `append()` to add an item to the end of a list.

```python
colors.append("purple")
```

---

## 6. Removing Items from a List

Use `remove()` when you know the value you want to remove.

```python
colors.remove("red")
```

Use `pop()` when you want to remove an item by position.

```python
colors.pop()
```

Without an index, `pop()` removes the last item.

---

## 7. Useful List Functions

Given:

```python
scores = [80, 95, 70, 88, 92]
```

Useful functions include:

```python
len(scores)
```

Returns the number of items.

```python
max(scores)
```

Returns the highest value.

```python
min(scores)
```

Returns the lowest value.

```python
sum(scores)
```

Returns the total.

To calculate an average:

```python
sum(scores) / len(scores)
```

---

## 8. Looping Through a List

A `for` loop lets you process every item in a list.

```python
animals = ["cat", "dog", "bird"]

for animal in animals:
    print(animal)
```

Output:

```text
cat
dog
bird
```

You can combine loops with conditions:

```python
numbers = [5, 12, 18, 3]

for number in numbers:
    if number > 10:
        print(number)
```

---

## 9. What Is a Tuple?

A **tuple** also stores multiple values.

Example:

```python
student = ("Maria", "Data Science", 2028)
```

Tuples normally use parentheses: `()`.

Tuples are **immutable**, which means their values cannot be changed after the tuple is created.

---

## 10. Accessing Tuple Values

Tuple values are accessed the same way as list values.

```python
student = ("Maria", "Data Science", 2028)
```

Examples:

```python
student[0]
student[1]
student[-1]
```

You can also use `len()` with tuples.

```python
len(student)
```

---

## 11. Lists vs. Tuples

| Feature | List | Tuple |
|---|---|---|
| Symbols | `[]` | `()` |
| Can store multiple values | Yes | Yes |
| Uses indexes | Yes | Yes |
| Can use `len()` | Yes | Yes |
| Can be changed after creation | Yes | No |
| Type | Mutable | Immutable |

A **list** is useful when the data may change.

A **tuple** is useful when the data should stay fixed.

---

## 12. Practice Example

Consider this list:

```python
temperatures = [72, 75, 70, 78, 80]
```

Make sure you know how to:

- Display the first temperature
- Display the last temperature
- Find the highest temperature
- Find the lowest temperature
- Find the number of temperatures
- Calculate the average
- Add another temperature
- Loop through all temperatures
- Display only temperatures above 75

---

## 13. Key Terms to Know

**List** – A mutable collection of values.

**Tuple** – An immutable collection of values.

**Index** – The position of an item in a collection.

**Mutable** – Can be changed after creation.

**Immutable** – Cannot be changed after creation.

**Slice** – A selected portion of a list or tuple.

**Loop** – Repeats code for multiple values.

---

## 14. Before Starting the Lab

You should be able to explain:

1. How to create a list.
2. How to access the first and last list items.
3. How to change a list item.
4. How to add and remove list items.
5. How to calculate the minimum, maximum, total, and average of numeric values.
6. How to loop through a list.
7. How to create and access a tuple.
8. The difference between mutable and immutable.
9. The main difference between a list and a tuple.

---

**Course:** CMP 262 – Data Science Programming  
**Topic:** Week 3 – Lists and Tuples  
**Instructor:** Prof. Amjed Hedhli
