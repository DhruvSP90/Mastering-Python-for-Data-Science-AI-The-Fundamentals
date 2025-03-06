# Mastering-Python-for-Data-Science-AI-The-Fundamentals

This repository contains educational materials for learning Python fundamentals for data science and AI applications. It includes example code and a practical temperature analysis project that demonstrates these concepts in action.

## Repository Contents

This repository contains two Jupyter notebooks:

1. **Mastering_Python.ipynb**: Covers essential Python concepts for data science
2. **Temperature Analysis Project.ipynb**: A complete data analysis project that applies these concepts

## Python Fundamentals Notebook

The `Python_Fundamentals.ipynb` notebook covers the following topics:

### 1. Data Types & Variables
- Numeric types (int, float, complex)
- Strings
- Booleans
- Type checking

### 2. Data Structures
- Lists (ordered, mutable collections)
- Dictionaries (key-value pairs)
- Tuples (ordered, immutable collections)
- Sets (unordered collections of unique elements)

### 3. Control Flow & Logic
- Conditional statements (if/elif/else)
- Loops (for/while)
- Using logic for data categorization

### 4. List Comprehensions
- Basic list comprehensions
- Filtering with conditionals
- Nested comprehensions
- Real-world applications in data transformation

### 5. Functions
- Function definition and documentation
- Arguments and return values
- Creating reusable analysis components

### 6. Working with Files
- Reading and writing CSV files
- Data import and parsing
- Handling file paths and errors

### 7. Error Handling
- Try/except blocks
- Handling different error types
- Creating robust data pipelines

## Temperature Analysis Project Notebook

The `Temperature_Analysis_Project.ipynb` notebook contains a complete temperature analysis application that demonstrates how to apply Python fundamentals to a real-world data analysis problem.

### Project Overview

This project analyzes a week of temperature data (in Fahrenheit) from four cities:
- New York
- San Francisco
- Chicago
- Miami

### Features

The analysis includes:

1. **Statistical calculations**:
   - Averages, medians, ranges
   - Maximum and minimum temperatures

2. **Climate classification**:
   - Hot (≥75°F)
   - Warm (60-74°F)
   - Moderate (45-59°F)
   - Cold (30-44°F)
   - Very Cold (<30°F)

3. **Freezing point analysis**:
   - Days above/below freezing

4. **Comparative analysis**:
   - Warmest and coldest cities
   - Most variable temperature city

### Implementation

The project is organized into modular functions:
- `calculate_statistics()`: Computes basic statistics for a list of numbers
- `analyze_temperatures()`: Processes temperature data for multiple cities
- `find_extremes()`: Identifies cities with extreme temperatures
- `display_results()`: Formats and presents the analysis results

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Jupyter Notebook or JupyterLab
- Basic knowledge of Python syntax

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/python-data-science-fundamentals.git
   ```

2. Navigate to the repository directory:
   ```
   cd python-data-science-fundamentals
   ```

3. Install required dependencies:
   ```
   pip install jupyter numpy matplotlib
   ```

4. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

5. Open either notebook in your browser.

## Learning Path

For beginners, I recommend following this learning path:

1. Start with `Python_Fundamentals.ipynb` and work through each section
2. Practice the concepts with the provided examples
3. Move to `Temperature_Analysis_Project.ipynb` to see how these concepts work together
4. Try modifying the temperature analysis project with your own enhancements

## Extending the Project

Here are some ideas to extend the temperature analysis project:
- Add data visualization with matplotlib
- Expand the analysis to include more cities or longer time periods
- Implement humidity or precipitation analysis
- Create a function to read temperature data from CSV files

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- This material is designed for educational purposes
- Inspired by real-world applications of Python in data science

## Contact

If you have any questions or feedback, please open an issue in this repository or contact me at [your email address].
