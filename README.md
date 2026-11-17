Pseudocode

START
DISPLAY "PYTHON TUTORIAL SYSTEM"

INPUT student_name

WHILE TRUE

    DISPLAY "MAIN MENU"
    DISPLAY "1. Introduction to Programming"
    DISPLAY "2. Basic Syntax"
    DISPLAY "3. Arithmetic Operators"
    DISPLAY "4. Exit"

    INPUT choice

    IF choice = "1" THEN
        DISPLAY "LESSON 1: INTRODUCTION TO PROGRAMMING"
        DISPLAY explanation of programming
        DISPLAY explanation of Python
        DISPLAY example: print("Hello, World!")
        DISPLAY quiz question and choices
        INPUT answer
        CONVERT answer TO uppercase

        IF answer = "A" THEN
            DISPLAY "Correct!"
        ELSE
            DISPLAY "Incorrect! The answer is A."
        END IF

    ELSE IF choice = "2" THEN
        DISPLAY "LESSON 2: BASIC SYNTAX"
        DISPLAY explanation of syntax
        DISPLAY PRINT, VARIABLES, and COMMENTS examples
        DISPLAY quiz question and choices
        INPUT answer
        CONVERT answer TO uppercase

        IF answer = "B" THEN
            DISPLAY "Correct!"
        ELSE
            DISPLAY "Incorrect! The answer is B."
        END IF

    ELSE IF choice = "3" THEN
        DISPLAY "LESSON 3: ARITHMETIC OPERATORS"

        SET num1 = 10
        SET num2 = 5

        DISPLAY first number and second number
        DISPLAY addition, subtraction, multiplication,
                division, modulus, floor division, and exponent
        DISPLAY quiz question and choices
        INPUT answer
        CONVERT answer TO uppercase

        IF answer = "B" THEN
            DISPLAY "Correct!"
        ELSE
            DISPLAY "Incorrect! The answer is B."
        END IF

    ELSE IF choice = "4" THEN
        DISPLAY "Thank you for using Python Tutorial!"
        DISPLAY "Goodbye, " + student_name
        EXIT WHILE LOOP

    ELSE
        DISPLAY "Invalid choice! Please choose 1 to 4."
    END IF

END WHILE
END