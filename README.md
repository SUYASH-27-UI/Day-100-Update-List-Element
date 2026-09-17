# Day-100-Update-List-Element
# Python Day 100 - Update List Element

This program updates an element in a list using its index position.

## Example

Original List:

```text
[10, 20, 30, 40, 50]
```

Input:

```text
Enter index to change: 2
Enter new value: 100
```

Output:

```text
Updated list: [10, 20, 100, 40, 50]
```

## Concepts Used

* Lists
* List indexing
* `input()`
* `int()`
* Variables
* Updating list elements

## How It Works

1. Create a list of numbers.
2. Display the original list.
3. Ask the user for the index that should be changed.
4. Ask the user for the new value.
5. Replace the old value using the index.
6. Display the updated list.

## Python Code

```python
numbers = [10, 20, 30, 40, 50]

print("Original list:", numbers)

position = int(input("Enter index to change: "))
new_value = int(input("Enter new value: "))

numbers[position] = new_value

print("Updated list:", numbers)
```

## Output

```text
Original list: [10, 20, 30, 40, 50]
Enter index to change: 2
Enter new value: 100
Updated list: [10, 20, 100, 40, 50]
```

## Goal

The goal of this project is to practice Python lists, indexing, user input, and updating list elements.
