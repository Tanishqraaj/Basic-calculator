# Basic Calculator

[![GitHub Repo](https://img.shields.io/badge/repo-Basic--Calculator-blue)](https://github.com/Tanishqraaj/Basic-Calculator)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE)

A simple browser-based calculator that performs four core arithmetic operations.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [How to Run](#how-to-run)
- [Usage](#usage)
- [Error Handling](#error-handling)
- [Tech Used](#tech-used)
- [License](#license)

## Overview

This project provides a lightweight calculator UI using plain HTML and JavaScript.

<details>
<summary><strong>Current repository layout note</strong></summary>

The calculator source is currently packaged inside `calculator.zip` as `calculator.html`.

</details>

## Features

- Add, subtract, multiply, and divide operations
- Numeric input fields for two values
- Instant result rendering on the page
- Validation for invalid input
- Safe divide-by-zero handling

## Project Structure

```text
Basic-Calculator/
├─ calculator.zip
├─ LICENSE
└─ README.md
```

## How to Run

<details open>
<summary><strong>Option 1: Run directly from the ZIP content</strong></summary>

1. Extract `calculator.zip`.
2. Open `calculator.html` in your browser.

</details>

<details>
<summary><strong>Option 2: Keep source directly in repo (recommended)</strong></summary>

1. Extract `calculator.html` from `calculator.zip`.
2. Move it to repository root.
3. Commit it so the app is visible without manual extraction.

</details>

## Usage

1. Enter values in **Number 1** and **Number 2**.
2. Click one operation button:
   - **Add**
   - **Subtract**
   - **Multiply**
   - **Divide**
3. Read the output in the **Result** section.

## Error Handling

- Shows alert if either input is not a valid number.
- Blocks division when the second number is `0`.

## Tech Used

- HTML5
- Vanilla JavaScript

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE).