# calcProd.py

**Code Analysis: Calculating the Product of the First 100,000 Numbers**

This Python script calculates the product of the first 100,000 numbers and measures the execution time.

### Code Breakdown

1. **Importing the `time` Module**: The script starts by importing the `time` module, which provides functions for working with time-related tasks.
2. **Measuring Execution Time**: The script records the current time using `time.time()` and assigns it to the `startTime` variable.
3. **Calculating the Product**: A `for` loop iterates from 1 to 99,999 (inclusive), multiplying the `product` variable by each number in the range. This effectively calculates the product of the first 100,000 numbers.
4. **Measuring Execution Time (Again)**: After the loop completes, the script records the current time using `time.time()` and assigns it to the `endTime` variable.
5. **Printing Results**: The