# bic21203-lab4a-javascript
# Name: Hong Jun Yang Matric Number:AI240163
Question 1: Interactive Text Changer

This exercise demonstrates how JavaScript can change the content of an HTML element when a user clicks a button.

The program uses document.getElementById() to select the paragraph and button elements from the HTML document. A function named changeMessage() is created to change the paragraph text from "Welcome to my website!" to "Hello there!". The addEventListener() method is used to detect when the user clicks the button and execute the function.

Question 2: Smart Number Validator

This exercise demonstrates how JavaScript can receive and validate user input.

The program allows users to enter a number into a text input field. The checkInput() function retrieves the input using .value and removes unnecessary spaces using .trim(). It then uses Number() and Number.isFinite() to check whether the input is a valid number.

An if...else if...else structure is used to compare the entered number with 10. The program displays an appropriate message depending on whether the number is lower than, higher than or equal to 10. Invalid or empty input displays an error message.

Question 3: Dynamic Number Generator

This exercise demonstrates how JavaScript can dynamically create HTML elements using DOM manipulation.

The program uses a function named generateNumbers() and a for loop to generate numbers from 1 to 5. The document.createElement() method creates a new list item for each number. The textContent property sets the text, while appendChild() adds each list item to the ordered list.

The existing list is cleared before generating new items to prevent duplicate entries when the button is clicked multiple times.

# Instruction
## Question 1 – Interactive Text Changer

Open Q1/index.html in your browser.
The original message "Welcome to my website!" will appear.
Click the Change Message button.
The paragraph should change to "Hello there!".

Output:
<img width="700" height="260" alt="image" src="https://github.com/user-attachments/assets/05de7168-a5ed-4390-8b74-da62f12aeb57" />

## Question 2 – Smart Number Validator

Open Q2/index.html in your browser.
Enter a number into the input field.
Click the Check button.
The validation message will appear below the input field.
Test with 5, 10, 15, abc and an empty input.
output:
<img width="677" height="247" alt="image" src="https://github.com/user-attachments/assets/498845f2-6743-4e44-8762-44aa742dfbce" />
<img width="720" height="212" alt="image" src="https://github.com/user-attachments/assets/7ebe99d4-cf33-4ab9-9978-8a97db93fe84" />

## Question 3 – Dynamic Number Generator
Open Q3/index.html in your browser.
Click the Generate button.
An ordered list containing numbers 1 to 5 will appear.
Click the Generate button again to verify that duplicate list items are not created.
Output:
<img width="810" height="292" alt="image" src="https://github.com/user-attachments/assets/f23aea6f-8896-4e67-b03c-e22ecc341242" />
