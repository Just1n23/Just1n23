START
numb = 3
SEND "Please enter your number" TO DISPLAY
RECEIVE "guess" FROM KEYBOARD
IF guess > 10 THEN
SEND "Too high! Your gusss must be between 1 and 10" TO DISPLAY
ELES IF guess = numb THEN "Well done! You guessed correctly." TO DISPLAY
ELES IF guess ≠ numb
SEND "Bad luck! The correct answer is 'numb'" TO DISPLAY
END IF
END IF
END IF
 
