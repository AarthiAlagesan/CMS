
# CMS using Reader-Writer Problem

## Description

This project demonstrates the **Reader-Writer problem** using **Java concurrency**. It simulates multiple threads reading and writing to articles in a simple **Content Management System (CMS)**. The project uses Java’s `ReentrantReadWriteLock` to ensure that multiple readers can access an article at the same time, but only one writer can modify it at a time.

## How It Works

- **Readers**: Multiple threads can read an article at the same time.
- **Writers**: Only one thread can write to an article, and it blocks other readers and writers while writing.

## Output

The program will show reading and writing activities from multiple threads and print the final content of all articles.

```plaintext
Final State of Articles:
Title: Concurrency in Java
Content: Concurrency is the ability of a program to perform multiple tasks simultaneously...

Title: Introduction to Java
Content: Java is a high-level, class-based, object-oriented programming language...

![Screenshot (67)](https://github.com/user-attachments/assets/dcc24d17-a693-40a9-ad98-4ee367cf921e)
