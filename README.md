# HTTP-Request-Analyzer
## Project Overview

The HTTP Request Analyzer is a Python-based cybersecurity and networking project designed to analyze HTTP requests and responses from web servers and APIs.

This project was created to strengthen practical understanding of:
- HTTP communication
- APIs
- Request and response structures
- Headers
- JSON parsing
- Response analysis
- Backend interaction
- Python scripting for cybersecurity

---

# Objectives

The objectives of this project were to:

- Understand how HTTP requests work
- Analyze server responses
- Inspect HTTP headers
- Parse JSON API responses
- Practice debugging and scripting
- Learn basic API interaction
- Build hands-on cybersecurity skills

---

# Technologies Used

- Python 3
- Requests Library
- JSON
- Linux Terminal
- Nano Editor

---

# Features Implemented

## Current Features

- Send HTTP GET requests
- Analyze response status codes
- Display response headers
- Parse JSON responses
- Display raw response body
- Measure response timing
- Handle request errors
- Interactive URL input

---

# Sample Output

```json
{
  "args": {},
  "headers": {
    "Accept": "*/*",
    "Host": "httpbin.org",
    "User-Agent": "python-requests/2.32.5"
  },
  "origin": "102.xxx.xxx.xxx",
  "url": "http://httpbin.org/get"
}
```

---

# HTTP Concepts Learned

## HTTP Methods
- GET
- POST (planned)

## HTTP Headers
- User-Agent
- Accept
- Content-Type
- Host

## Status Codes
- 200 OK
- 404 Not Found
- 500 Server Error

## APIs
The project interacts with APIs such as:
- httpbin.org
- GitHub API

---

# Challenges Encountered

## Python NameError

An error occurred due to a typo:

```python
print(renponse.text)
```

Corrected to:

```python
print(response.text)
```

This improved debugging and troubleshooting skills.

---

# Security Concepts Learned

- Request inspection
- Header analysis
- API communication
- Client fingerprinting
- Response analysis
- Metadata exposure
- JSON parsing

---

# Future Improvements

Planned upgrades include:

- POST request support
- Cookie analysis
- Authentication token handling
- Security header scanner
- Redirect tracking
- Logging system
- GUI dashboard
- Multi-threaded requests
- Proxy support

---

# How to Run

## Install Dependencies

```bash
pip install requests
```

## Run the Program

```bash
python analyzer.py
```

---

# Project Structure

```bash
http-request-analyzer/
│
├── analyzer.py
└── README.md
```

---

# Learning Outcome

This project improved understanding of:
- HTTP communication
- APIs
- Python scripting
- Linux workflow
- Cybersecurity fundamentals
- Web application interaction

---

# Author

Fridah Nyambura

Cybersecurity and Information Security Student
