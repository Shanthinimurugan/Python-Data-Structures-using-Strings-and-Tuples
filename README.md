# Python-Data-Structures-using-Strings-and-Tuples
A collection of Python programs demonstrating fundamental data structure concepts using Strings and Tuples, including creation, indexing, slicing, method, accessing elements, concatenation, and common operations.

## 📌 Project Overview

This project demonstrates how to work with strings and tuples is an essential part of learning Python programming. Beginners need practical experience in manipulating text and working with immutable data collections.

This project addresses this requirement by implementing various string and tuple operations using Python. It demonstrates how to combine strings, access individual characters, extract portions of text, modify strings using built-in methods, and perform basic operations on tuples.


## 🎯 Project Objectives

The main objective of this project is to develop a basic understanding of Python Strings and Tuples through practical coding exercises. The project focuses on performing string manipulation, indexing, slicing, built-in string methods, and tuple operations.

The examples are designed to understand how Python handles text data and immutable collections.

## 📌 Problem Statement

* Analyse string concatenation in Python.
* Perform string indexing and slicing.
* Reverse a string using slicing.
* Extract specific words from a string.
* Apply common string methods such as `upper()`, `lower()`, `capitalize()`, `count()`, and `replace()`.
* Create and concatenate tuples.
* Repeat tuple elements.
* Access individual tuple elements.
* Extract elements from tuples using slicing.

## 🧩 Topics Covered

### 1. String Concatenation

The project demonstrates how to:

* Combine two strings using the `+` operator.
* Accept user input using `input()`.
* Add spaces and other text while concatenating strings.

Example:

```python
string1 = "Hello"
string2 = input("Enter your name: ")
a = string1 + " " + string2
print(a)
```

### 2. String Slicing and Indexing

The project demonstrates:

* Accessing the first character using `text[0]`.
* Accessing the last character using `text[-1]`.
* Extracting characters using slicing.
* Extracting the last characters of a string.
* Reversing a string using `text[::-1]`.
* Extracting the word `"Python"` using `split()` and `index()`.

Example:

```python
text = input("Enter the String: ")

print(text[0])
print(text[-1])
print(text[:6])
print(text[-11:])
print(text[::-1])
```

### 3. String Methods

The following Python string methods are explored:

| Method         | Purpose                                        |
| -------------- | ---------------------------------------------- |
| `upper()`      | Converts a string to uppercase                 |
| `lower()`      | Converts a string to lowercase                 |
| `capitalize()` | Capitalizes the first character                |
| `count()`      | Counts occurrences of a character or substring |
| `replace()`    | Replaces part of a string with another value   |

Example:

```python
strM = "Python beginner tutorial"

print(strM.upper())
print(strM.lower())
print(strM.capitalize())
print(strM.count("t"))
print(strM.replace("Python", "Data Analytics"))
```

### 4. Tuples

The project also demonstrates basic tuple operations.

Two tuples are created:

```python
tuple1 = (10, 20, 30)
tuple2 = (40, 50, 60)
```

The following operations are performed:

* Tuple creation
* Tuple concatenation
* Tuple repetition
* Accessing elements using indexing
* Accessing the first three elements
* Accessing the last three elements

Example:

```python
t_combine = tuple1 + tuple2

print(t_combine)
print(t_combine * 3)
print(t_combine[2])
print(t_combine[0:3])
print(t_combine[-3:])
```

## 🛠️ Technologies Used

* **Python**
* **Google Colab**

## 📚 Key Concepts Learned

Through this project, I practiced:

* String manipulation
* String indexing
* String slicing
* User input
* String methods
* Tuple creation
* Tuple concatenation
* Tuple repetition
* Tuple indexing
* Tuple slicing

## 📂 Project Structure

```text
Python-Data-Structures-using-Strings-and-Tuples
│
├── Exploring Python Strings and Tuples.ipynb
└── README.md
```

## 🚀 How to Run

1. Open the `Exploring Python Strings and Tuples.ipynb.ipynb` file in **Google Colab** or **Jupyter Notebook**.
2. Run each code cell sequentially.
3. Provide the required input when prompted.
4. Observe the output for each operation.

## ✅ Conclusion

This project provides practical experience with **Python Strings and Tuples**. It builds a strong foundation for understanding data manipulation in Python and prepares for more advanced topics such as **Lists, Dictionaries, Sets, Functions, NumPy, and Pandas**.

## 👩‍💻 Author

**Shanthini**

**Aspiring Data Analyst**

**Skills:** Python | Data Structures | String Operations | Tuple Operations | Data Manipulation

## 📄 License

This project is created for educational and assignment purposes only.

## 🙏 Acknowledgments

I would like to thank:

- **Entri Elevate Course Support** for providing guidance and learning resources throughout this project.
- **Python Documentation** for valuable references and support in understanding Python syntax, string operations, and tuple concepts.
- **Google Colab** for providing an interactive environment to practice and execute Python code.



