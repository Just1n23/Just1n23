RECEIVE temperature FROM KEYBOARD
IF 
  temperature < 18 THEN
  SEND "Cold, the perfect temperature for sleep is 18-21 degrees." TO DISPLAY
ELSE IF
  temperature > 21
  SEND "Perfect!" TO DISPLAY
ELSE IF
  SEND "No!, the perfect temperature for sleep is 18-21 degrees"
END IF
END IF
END IF

  
