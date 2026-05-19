# Mencia Blog Finder

A simple tool that scans sequential MenciaBlogs URLs and detects when a valid blog exists.

It checks URLs like:

https://name-4575.menciablogs.nl/


If a valid blog is found, it is saved to `.links.txt`.

---

## Requirements

- Python 3.10 or higher  
Download Python: https://www.python.org/downloads/

During installation, make sure to enable:
- Add Python to PATH

---

## Installation

Run:


install.bat


This installs all required dependencies automatically.

---

## Usage

Run:


run.bat


Then enter:
- Name
- Starting number

The tool will:
- scan URLs sequentially
- detect valid blogs
- stop when a valid one is found
- save the result to `.links.txt`

---

## Project structure


mencia-blog-bruteforce/
│
├── app.py
├── run.bat
├── install.bat
├── .links.txt


---

## Notes

This tool is intended for educational and testing purposes only.
