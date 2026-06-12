# Contest Companion

## Overview

Contest Companion is a Visual Studio Code extension designed to simplify competitive programming workflows. It automates test case retrieval, code execution, and result verification directly within VS Code, allowing users to focus on problem-solving rather than manual testing.

The extension currently supports multiple programming languages and provides a streamlined environment for practicing coding problems efficiently.

---

## Project Objectives

The primary objectives of Contest Companion are:

* Automate test case fetching from coding platforms.
* Reduce manual effort in running and validating solutions.
* Provide a seamless coding experience within VS Code.
* Support multiple programming languages through a unified workflow.
* Create a scalable framework for future competitive programming integrations.

---

## Features

| Feature                      | Description                               |
| ---------------------------- | ----------------------------------------- |
| Automatic Test Case Fetching | Retrieves sample test cases automatically |
| Multi-Language Support       | Supports C++ and Python solutions         |
| Integrated Execution         | Run solutions directly from VS Code       |
| Output Verification          | Compares outputs against expected results |
| Modular Architecture         | Easy to extend and customize              |

---

## System Workflow

The extension follows the workflow below:

1. Fetch problem test cases.
2. Store test cases in a structured format.
3. Execute the user solution.
4. Compare generated output with expected output.
5. Display results in the terminal.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/Aryan-soni6387/Contest-Companion-Vscode.git
```

### Open the Project

```bash
code Contest-Companion-Vscode
```

### Install Dependencies

Navigate to the backend directory and install dependencies:

```bash
npm install
```

---

## Usage

### Writing Solutions

Create your solution in either:

```text
solution.cpp
```

or

```text
solution.py
```

### Running the Solution

Press:

```text
Ctrl + Shift + B
```

The extension will:

* Fetch available test cases
* Execute the solution
* Validate outputs
* Display execution results

---

## How It Works

### Test Case Retrieval

Contest Companion retrieves problem test cases and stores them locally for execution.

### Solution Execution

The extension automatically invokes the selected compiler or interpreter and runs the user's solution.

### Result Validation

Generated outputs are compared against expected outputs, and the results are summarized in the terminal.

---

## Technologies Used

* JavaScript
* Node.js
* VS Code Extension API
* C++
* Python
* JSON

---

## Repository Structure

```text
Contest-Companion-Vscode/

├── .vscode/
│   └── tasks.json
│
├── backend/
│   ├── package.json
│   ├── runner.js
│   └── fetchTestCases.js
│
├── solution.cpp
├── solution.py
├── README.md
└── LICENSE
```

---

## Future Enhancements

* Support for additional coding platforms
* Custom test case management
* Performance benchmarking
* Submission analytics
* Enhanced user interface

---

## Contribution

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push the branch.
5. Submit a Pull Request.

---

## Author

Aryan Soni 🎓 B.Tech Student, IIT Roorkee

GitHub: https://github.com/Aryan-soni6387
