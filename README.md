# Functional Programming Spreadsheet

## Overview

This project presents a Functional Programming Spreadsheet, a web-based spreadsheet application that interprets and
evaluates formulas using functional programming principles. It's developed using JavaScript and HTML, offering a dynamic
and responsive user interface for complex calculations and data manipulation.

## Features

- **Dynamic Spreadsheet Grid:** A grid system labeled with letters and numbers, similar to traditional spreadsheet
  applications.
- **Formula Evaluation:** Advanced formula evaluation capabilities, including arithmetic operations, range functions,
  and custom spreadsheet functions.
- **Custom Functions:** A set of pre-defined functions like `sum`, `average`, `median`, and more, catering to various
  data processing needs.
- **Range Selection and Processing:** Ability to process cell ranges (e.g., A1:B2) for operations like sum or average.
- **Cell Reference Resolution:** Evaluates formulas containing references to other cells, updating values dynamically.

## How it Works

1. **Grid Initialization:** Upon loading, the spreadsheet dynamically generates a grid of cells labeled according to
   rows and columns.
2. **Entering Formulas:** Users can input formulas in the cells. These formulas can include arithmetic operations,
   references to other cells, or calls to custom spreadsheet functions.
3. **Formula Parsing and Evaluation:** The application parses and evaluates the input formulas, resolving cell
   references and function calls.
4. **Update Mechanism:** The `update` function triggers re-evaluation of formulas when cell values change, ensuring data
   consistency across the spreadsheet.

## Technical Details

- **Functional Programming Approach:** The application is built using functional programming paradigms in JavaScript,
  ensuring a clean and efficient codebase.
- **Custom Formula Evaluation:** Implements a formula evaluation engine that processes string inputs and calculates
  results based on custom rules.
- **Spreadsheet Functions:** A collection of functions like `sum`, `average`, `median`, etc., are defined to perform
  common spreadsheet operations.
- **Recursive Formula Resolution:** The application can handle complex nested formulas and cell references, thanks to
  its recursive evaluation mechanism.

## Installation and Usage

Simply clone the repository and open the HTML file in a browser. No additional installation is required. Input formulas
into the cells to perform calculations and see the results in real-time.

## Contributing

Contributions are welcome, especially in expanding the range of functions, improving the UI, or enhancing the formula
evaluation engine.
