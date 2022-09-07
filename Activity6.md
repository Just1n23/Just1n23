SEND 'Please enter firstNumber'
TO DISPLAY RECEIVE firstNumber FROM KEYBOARD 
SEND 'Please enter the second number' TO DISPLAY 
RECEIVE secondNumber FROM KEYBOARD 
SEND 'Pleade enter the third number' TO DISPLAY
RECEIVE thirdNumber FROM KEYBOARD
SET total TO (firstNumber + secondNumber + thirdNumber) / 3
SEND total TO DISPLAY
