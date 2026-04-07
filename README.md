# 🔺 Pascal's Triangle (C++)

This repository contains a C++ solution for generating **Pascal's Triangle**.

---

## 🚀 Problem Statement

Given an integer `numRows`, return the first `numRows` of Pascal's triangle.

In Pascal's triangle:
- The first and last element of each row is `1`
- Each middle element is the sum of the two elements directly above it

---

## 🧠 Approach

- Use a 2D vector to store the triangle
- Each row has `i + 1` elements
- First and last elements are always `1`
- Middle elements:
