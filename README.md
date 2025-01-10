Two Sum Solution in C++

This project implements a solution to the **Two Sum** problem in C++. The program allows the user to input an array of integers and a target value, then finds two indices of the array such that their corresponding elements add up to the target. 

## Problem Description
Given an array of integers `nums` and an integer `target`, find two indices such that:
- `nums[index1] + nums[index2] == target`
- Each input has exactly one solution, and you may not use the same element twice.

## Features
- Accepts input for array size, elements, and target from the user.
- Finds the solution using an efficient hash map-based algorithm with a time complexity of **O(n)**.
- Outputs the indices of the two elements in the array that sum up to the target.

## Example Usage
### Input
```
Enter the number of elements in the array: 4
Enter the elements of the array:
2 7 11 15
Enter the target sum: 9
```

### Output
```
Indices of the two numbers are: [0, 1]
```

## Constraints
- \( 2 \leq 	ext{nums.length} \leq 10^4 \)
- \(-10^9 \leq 	ext{nums[i]} \leq 10^9\)
- \(-10^9 \leq 	ext{target} \leq 10^9\)
- Only one valid answer exists.

## How to Run
1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd TwoSumAssignment
    ```
3. Compile the code using a C++ compiler (e.g., g++):
    ```bash
    g++ two_sum_input.cpp -o two_sum
    ```
4. Run the program:
    ```bash
    ./two_sum
    ```

## Code Explanation
- **Function `findIndices`:**
  - Takes the input array and target value as arguments.
  - Uses a hash map to store elements and their indices.
  - Finds the two indices where the sum equals the target efficiently.

- **Main Function:**
  - Accepts user input for array size, elements, and target value.
  - Calls `findIndices` to compute the result.
  - Outputs the indices if a solution exists.

## Files
- `two_sum_input.cpp`: The main program file containing the solution.
- `README.md`: Project documentation.

## Dependencies
- Requires a C++ compiler supporting C++11 or later.

## License
This project is licensed under the MIT License. Feel free to use and modify it for personal or educational purposes.

## Author
Developed by Vrishab Talla.  
