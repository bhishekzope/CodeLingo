# CodeLingo

CodeLingo is a Python library that converts code snippets into plain English. It also provides the ability to execute the code and capture its output. This library is designed to help beginners understand code by translating it into human-readable explanations.

---

## Features

- **Code to English**: Converts Python code snippets into plain English explanations.
- **Code Execution**: Executes the provided code and captures its output.
- **Easy to Use**: Simple and intuitive API for quick integration.

---

## Installation

You can install CodeLingo using `pip`:

```bash
pip install CodeLingo
```

---

## Usage

You can use CodeLingo using this Code :

```python
from CodeLingo import CodeToEnglish

code = """
put your python code in here
"""

converter = CodeToEnglish(code)
explanation = converter.convert_to_english()
print("Explanation:\n", explanation)

output = converter.execute_code()
print("Output:\n", output)
```