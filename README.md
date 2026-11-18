Pseudo Code

START

    DISPLAY "PYTHON TUTORIAL SYSTEM"

    INPUT student_name

    REPEAT

        DISPLAY "MAIN MENU"
        DISPLAY "1. Introduction to Programming"
        DISPLAY "2. Basic Syntax"
        DISPLAY "3. Arithmetic Operators"
        DISPLAY "4. Exit"

        INPUT choice

        IF choice = 1 THEN

            DISPLAY "LESSON 1: INTRODUCTION TO PROGRAMMING"
            DISPLAY "Explain what programming is"
            DISPLAY "Explain what Python is"
            DISPLAY "Display Python example"
            DISPLAY "Display output"

            DISPLAY "QUIZ"
            DISPLAY "What is Python?"
            INPUT answer

            IF answer = "A" THEN
                DISPLAY "Correct!"
            ELSE
                DISPLAY "Incorrect! The answer is A."
            ENDIF

        ELSE IF choice = 2 THEN

            DISPLAY "LESSON 2: BASIC SYNTAX"
            DISPLAY "Explain Python Syntax"
            DISPLAY "Explain PRINT"
            DISPLAY "Explain VARIABLES"
            DISPLAY "Explain COMMENTS"

            DISPLAY "QUIZ"
            DISPLAY "Which statement displays text?"
            INPUT answer

            IF answer = "B" THEN
                DISPLAY "Correct!"
            ELSE
                DISPLAY "Incorrect! The answer is B."
            ENDIF

        ELSE IF choice = 3 THEN

            DISPLAY "LESSON 3: ARITHMETIC OPERATORS"

            SET num1 = 10
            SET num2 = 5

            DISPLAY "First Number", num1
            DISPLAY "Second Number", num2

            DISPLAY num1 + num2
            DISPLAY num1 - num2
            DISPLAY num1 * num2
            DISPLAY num1 / num2
            DISPLAY num1 MOD num2
            DISPLAY num1 DIV num2
            DISPLAY num1 ^ num2

            DISPLAY "QUIZ"
            DISPLAY "What is 10 + 5?"
            INPUT answer

            IF answer = "B" THEN
                DISPLAY "Correct!"
            ELSE
                DISPLAY "Incorrect! The answer is B."
            ENDIF

        ELSE IF choice = 4 THEN

            DISPLAY "Thank you for using Python Tutorial!"
            DISPLAY "Goodbye", student_name

            EXIT LOOP

        ELSE

            DISPLAY "Invalid choice! Please choose 1 to 4."

        ENDIF

    UNTIL choice = 4

END