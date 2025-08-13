# resume_keyword_search
A lightweight tool that scans all .docx resumes in a specified folder and identifies which ones contain specific keywords. Perfect for recruiters, or job seekers managing large collections of resumes. The script supports multiple keywords, ignores temporary Word files, and prints out the matching filenames along with the found keywords.

# Resume Keyword Search Tool

A simple Python script to search through multiple Word (`.docx`) resumes in a folder for specific keywords.

## Features
- Scans all `.docx` files in a given folder.
- Supports multiple keywords.
- Ignores temporary Word files (`~$`).
- Prints matching resumes and found keywords.

## Requirements
- Python 3.7+
- `python-docx` library

## Installation
```bash
pip install python-docx
