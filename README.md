# Week 2 Assignment: Python List Operations

A Python program demonstrating various list manipulation methods including appending, inserting, extending, removing, sorting, and finding elements.

## Assignment Requirements

This program completes the following tasks:

1. ✅ Create an empty list called `my_list`
2. ✅ Append the elements: 10, 20, 30, 40
3. ✅ Insert the value 15 at the second position
4. ✅ Extend `my_list` with another list: [50, 60, 70]
5. ✅ Remove the last element from `my_list`
6. ✅ Sort `my_list` in ascending order
7. ✅ Find and print the index of the value 30

## Program Output

```
1. Empty list created: []
2. After appending 10, 20, 30, 40: [10, 20, 30, 40]
3. After inserting 15 at second position: [10, 15, 20, 30, 40]
4. After extending with [50, 60, 70]: [10, 15, 20, 30, 40, 50, 60, 70]
5. After removing the last element: [10, 15, 20, 30, 40, 50, 60]
6. After sorting in ascending order: [10, 15, 20, 30, 40, 50, 60]
7. Index of value 30: 3

Final list: [10, 15, 20, 30, 40, 50, 60]
```

## List Methods Used

| Method | Description | Example |
|--------|-------------|---------|
| `append()` | Adds an element to the end of the list | `my_list.append(10)` |
| `insert()` | Inserts an element at a specific position | `my_list.insert(1, 15)` |
| `extend()` | Adds all elements from another list | `my_list.extend([50, 60, 70])` |
| `pop()` | Removes and returns the last element | `my_list.pop()` |
| `sort()` | Sorts the list in ascending order | `my_list.sort()` |
| `index()` | Returns the index of a specified value | `my_list.index(30)` |

## How to Run

1. Make sure you have Python 3.x installed
2. Clone or download this repository
3. Navigate to the project directory
4. Run the program:
   ```bash
   python list_operations.py
   ```

## Requirements

- Python 3.x

## Key Concepts Demonstrated

- **List Creation**: Creating empty lists
- **List Modification**: Adding, inserting, and removing elements
- **List Sorting**: Organizing data in order
- **List Indexing**: Finding positions of elements
- **List Extension**: Combining lists

## Notes

- List indexing in Python starts at 0 (first position is index 0)
- The `insert()` method takes two parameters: position and value
- `extend()` adds multiple items, while `append()` adds a single item
- `sort()` modifies the list in place (doesn't return a new list)
- The `index()` method returns the first occurrence of the value

## Author

[Your Name]

## Course

Intro to Python - Week 2 Assignment

## License

This project is for educational purposes.