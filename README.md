Hash Table

A Python implementation of a hash table for storing and managing key-value pairs.

About the Project

This project was completed as part of the Python Certification Projects in the "freeCodeCamp" (https://www.freecodecamp.org/) curriculum.

The project demonstrates how hashing can be used to store and retrieve data efficiently using keys and values.

Features

The "HashTable" class provides the following operations:

- "add()" — Adds a key-value pair to the hash table.
- "lookup()" — Retrieves the value associated with a key.
- "remove()" — Removes a key-value pair from the hash table.
- "hash()" — Generates a hash value from a string key.

How It Works

The "hash()" method converts a string key into a numerical hash value by calculating the sum of the Unicode values of its characters.

The implementation also handles hash collisions by storing multiple key-value pairs under the same hash value.

Example

table = HashTable()

table.add("name", "Javed")
table.add("language", "Python")

print(table.lookup("name"))
# Jawed

table.remove("name")

print(table.lookup("name"))
# None

Concepts Practiced

- Python Classes
- Object-Oriented Programming
- Dictionaries
- Key-Value Data Structures
- Hashing
- Hash Collisions
- Functions and Methods
- Data Structure Design

Source

This project was completed as part of the Python Certification Projects from freeCodeCamp.

The project requirements were provided by freeCodeCamp, and the solution was implemented in Python.
