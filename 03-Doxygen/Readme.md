
# Doxygen Documentation

## 1. Introduction
Doxygen is a documentation generation tool used to create documentation from source code.

## 2. Features
- Generates HTML documentation.
- Supports C, C++, Java and Python.
- Documents classes and functions.
- Supports diagrams and cross-references.

## 3. Common Commands

| Command | Purpose |
|---|---|
| doxygen -g | Generates configuration file |
| doxygen Doxyfile | Generates documentation |
| @brief | Short description |
| @param | Describes function parameters |
| @return | Describes return value |

## 4. Example Documentation Comments

```cpp
/**
 * @brief Adds two numbers.
 * @param a First number
 * @param b Second number
 * @return Sum of two numbers
 */
int add(int a, int b) {
    return a + b;
}
```

## 5. Advantages
- Saves documentation time.
- Makes code easier to understand.
- Maintains organized documentation.
- Useful for large software projects.

## 6. Conclusion
Doxygen helps programmers generate structured documentation directly from source code.
