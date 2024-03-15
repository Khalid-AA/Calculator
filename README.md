# Requirements 

### Basic arithmetic 
- Addition: Users should be able to add several numbers.
- Subtraction: Users should be able to subtract multiple numbers.
- Multiplication: Users should be able to multiply two or more numbers.
- Division: Users should be able to divide one number by another. Division by zero should result in an error message. 

### Memory Functions 
- Memory Storage: Users should be able to store their calculations in a table for viewing.
- Memory Clear: Users should be able to clear the table. 

### Special features 
- Decimal: users should be able to perform arithmetic using floating point numbers.
- Percentage: users should be able to carry out arithmetic in terms of percentages.
- BODMAS: Users can perform complex operations which will follow the mathematical rule of order of operations.
- Parenthesis: Users can use brackets which will also follow BODMAS rule.
- Result reuse: Users can use the result of an expression for a new operation by pressing any operator. 

# Interface
<img width="532" alt="image" src="https://github.com/Khalid-AA/Calculator/assets/119416718/14cfa0d5-2063-4183-a0f6-3f94328c0a53">


### 1. Keypad 
- Contains the buttons for building complex expressions involving parenthesis, percentage, and decimals. 
- Backspace and clear buttons for erasing one character and entire expression respectively. 

### 2. Displays 
- The first larger display where expressions are built. 
- Second field for displaying results 

### 3. Table for memory 
- Stores a history of calculations performed. 
- Can be erased using the “Clear” button.


#  Functionality
### BODMAS expression
<img width="395" alt="image" src="https://github.com/Khalid-AA/Calculator/assets/119416718/5af80228-036e-4696-b3d3-7c69245c3f73">

#### Key points
- The expression follows the BODMAS rule and displays the correct answer.
- The expression along with the result is stored in the table.
- Shown below, the result (-5.9) can be reused upon pressing any operator (+, -, *, /).

### Result reuse
<img width="395" alt="image" src="https://github.com/Khalid-AA/Calculator/assets/119416718/c258c44d-a8bb-40c0-af34-4397902abca3">

#### Key points
- The result from the previous calculation can be used in new calculation.
- The new result will continue to be stored in the table.


### Division by zero error
<img width="396" alt="image" src="https://github.com/Khalid-AA/Calculator/assets/119416718/1179efe4-7a0b-4018-8522-2775f454e528">

#### Key points
- Dividing by zero immediately throws an error, indicating the message on the result text field.
- This will not be added to the table.

### Floating point arithmetic
<img width="395" alt="image" src="https://github.com/Khalid-AA/Calculator/assets/119416718/7b8461cc-567d-4374-b3cf-4dd6c85fbad9">

- Floating point operations can be carried out to a high precision.

