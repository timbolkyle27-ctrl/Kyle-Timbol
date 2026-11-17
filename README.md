# Kyle-Timbol
while True:
    
    user = input("Enter Your Name :").upper()
    
    print("\n==================================================")
    print(f" WELCOM TO MY PYTHON TUTORIAL PROGRAM {user} ^_^")
    print("====================================================")
    
    print("\n--- PART 1: INTRODUCTION TO PYTHON ---")
    print("1. Introduction to Python all in one")

    print("\n--- PART 2: FUNDAMENTALS OF PROBLEM SOLVING ---")
    print("2. Problem Solving, Process and Algorithm")
    print("3. Pseudocode and Pseudocode Elements")
    print("4. Arithmetic Operators and PEMDAS")
    print("5. Flowchart and Flowchart Symbols")
    print("6. Program Logic")
    print("7. Logical Operators")
    print("8. IF-ELSE IF-ELSE")
    print("9. While Loop")

    print("\n0. Exit")
    print("====================================")

    choice = input("\nChoose a lesson: ")

    # LESSON 1: INTRODUCTION TO PYTHON

    if choice == "1":

        print("\n===== INTRODUCTION TO PYTHON =====")

        print("\n WHAT IS PYTHON? ")
        print("Python is a widely used programming language.")
        print("Created by Guido van Rossum in 1991.")
        print("It is a high-level, interpreted,")
        print("and general-purpose programming language.")
        
        print("\n=======================================================")

        print("\n WHY LEARN PYTHON? ")
        print("1. Simple and easy to learn")
        print("2. Readable syntax")
        print("3. Versatile - used in many fields")
        print("4. Huge community")

        print("\n===== PYTHON BASIC SYNTAX =====")
        print("Syntax refers to the rules for writing Python programs.")

        print("\n1. <<<<CASE-SENSITIVE>>>>")
        print("Python treats uppercase and lowercase letters differently.")

        name = "John"
        print(f"\nExample: name = '{name}'")
        print("Incorrect: print(Name)")
        print("Correct: print(name)")
        print(f"Output: {name}")

        print("\n2.INDENTATION")
        print("Python uses spaces to define blocks of code.")

        print("\nExample:")
        print("if 5 > 2:")
        print('    print("Five is greater than two")')
        print("Output: Five is greater than two")

        print("\n3. PRINT STATEMENT")
        print("The print() function displays information.")
        print("Syntax: print(value)")
        print('\nExample: print("Hello, World!")')
        print("Output: Hello, World!")

        print("\n4. PRINTING TEXT AND NUMBERS ")
        print("Text uses quotation marks.")
        print("Numbers can be printed without quotation marks.")

        print('\nExample: print("Hello")')
        print("Example: print(100)")
        print("Output: Hello")
        print(f"Output: {100}")

        print("\n5. PYTHON COMMENTS ")
        print("Comments are ignored by Python.")
        print("They explain the code.")
        print("# - is the symbol for comments.")

        print('\nExample: # This is a comment')
        print('print("Hello")')
        print("Output: Hello")

        print("\n6. VARIABLES AND CONSTANTS ")

        name = "John"
        print("A variable stores data in a program.")
        print(f"\nExample: name = '{name}'")
        print("Variable: name")
        print(f"Stored value: {name}")

        print("\nA constant is a value intended to remain unchanged.")
        print("Python commonly uses uppercase names for constants.")

        SCHOOL_NAME = CCST
        print(f"\nExample: SCHOOL_NAME = {SCHOOL_NAME}")
        print(f"Output: {SCHOOL_NAME}")

        print("\n7.  VARIABLE NAMING RULES ")
        print("1. Names can be short or descriptive.")
        print("2. Must start with a letter or underscore.")
        print("3. Cannot start with a number.")
        print("4. Special characters are not allowed except underscore.")
        print("5. Variable names are case-sensitive.")

        print("\nCorrect:")
        print('name = "John"')
        print("student_age = 18")

        print("\nIncorrect:")
        print("2name = 'John'")
        print("@age = 18")

        print("\n8. ASSIGNING VALUE TO VARIABLES ")
        print("The = symbol assigns a value to a variable.")

        school = "Clark College"
        print(f"\nExample: school = '{school}'")
        print(f"Output: {school}")

        print("\n9. OUTPUTTING MULTIPLE VARIABLES")
        print("You can use commas or + to display strings.")

        a = "I"
        b = "Love"
        c = "CCST"

        print("\nUsing comma:")
        print(f"{a}, {b}, {c}")

        print("\nUsing plus:")
        print(f"{a} {b} {c}")

        print("\n10. BASIC DATA TYPES ")
        print("INT - Whole numbers without decimals.")
        print("FLOAT - Numbers with decimal points.")
        print("STR - Text or characters inside quotation marks.")
        print("BOOL - Represents True or False.")

        age = 20
        grade = 89.5
        student = "Maria"
        enrolled = True

        print("\nExamples:")
        print(f"Age: {age} - INT")
        print(f"Grade: {grade} - FLOAT")
        print(f"Student: {student} - STRING")
        print(f"Enrolled: {enrolled} - BOOLEAN")

    # LESSON 2: PROBLEM SOLVING, PROCESS AND ALGORITHM

    elif choice == "2":

        print("\n===== INTRODUCTION TO PROBLEM SOLVING =====")
        print("Problem solving is the process of analyzing")
        print("a problem and finding the best solution")
        print("before writing a computer program.")

        print("\nExample:")
        print("Problem: Find the sum of two numbers.")
        print("Solution: Get two numbers, add them,")
        print("and display the result.")

        print("\n===== PROBLEM-SOLVING PROCESS =====")
        print("1. PROBLEM - Understand the problem.")
        print("2. ANALYZE - Identify inputs, outputs, and requirements.")
        print("3. CREATE ALGORITHM - Plan the solution step by step.")
        print("4. WRITE PSEUDOCODE - Write steps using simple English.")
        print("5. DRAW FLOWCHART - Visualize steps using a diagram.")
        print("6. WRITE PROGRAM - Convert the algorithm into code.")
        print("7. TEST PROGRAM - Test and fix errors.")

        print("\n===== ALGORITHM =====")
        print("An algorithm is a step-by-step procedure")
        print("used to solve a problem or complete a task.")

        print("\nExample: Add two numbers")
        print("1. Start")
        print("2. Input first number")
        print("3. Input second number")
        print("4. Add the two numbers")
        print("5. Display the sum")
        print("6. End")

        number1 = 10
        number2 = 5
        total = number1 + number2

        print("\nSample:")
        print(f"First number: {number1}")
        print(f"Second number: {number2}")
        print(f"Sum: {total}")

    # LESSON 3: PSEUDOCODE AND PSEUDOCODE ELEMENTS

    elif choice == "3":

        print("\n===== PSEUDOCODE =====")
        print("Pseudocode is an informal way of writing")
        print("program logic using simple English statements.")

        print("\nRemember:")
        print("- It is not a programming language.")
        print("- It is a plan before coding.")

        print("\n===== PSEUDOCODE ELEMENTS =====")
        print("START/END - Begins and ends an algorithm.")
        print("DECLARE - Declares variables and data types.")
        print("= - Assigns a value or result.")
        print("INPUT - Accepts information from the user.")
        print("OUTPUT - Displays information.")
        print("IF/ELSE - Conditional structure.")
        print("WHILE/FOR - Looping structure.")

        print("\nEXAMPLE 1: Display your name")
        print("START")
        print('OUTPUT "Juan Dela Cruz"')
        print("END")

        print("\nEXAMPLE 2: Input and display age")
        print("START")
        print("DECLARE Age : INTEGER")
        print("INPUT Age")
        print("OUTPUT Age")
        print("END")

        print("\nEXAMPLE 3: Sum of two numbers")
        print("START")
        print("DECLARE number1, number2, sum : INTEGER")
        print("INPUT number1")
        print("INPUT number2")
        print("sum = number1 + number2")
        print("OUTPUT sum")
        print("END")

    # LESSON 4: ARITHMETIC OPERATORS AND PEMDAS

    elif choice == "4":

        print("\n===== ARITHMETIC OPERATORS =====")

        print("+ Addition")
        print("- Subtraction")
        print("* Multiplication")
        print("/ Division")
        print("// Floor Division")
        print("% Modulus")
        print("** Exponentiation")

        a = 10
        b = 3

        print("a = 10")
        print("b = 3")

        print("\nEXAMPLES:")
        print(f"Addition: 10 + 3 = {a + b}")
        print(f"Subtraction: 10 - 3 = {a - b}")
        print(f"Multiplication: 10 * 3 = {a * b}")
        print(f"Division: 10 / 3 = {a / b}")
        print(f"Floor Division: 10 // 3 = {a // b}")
        print(f"Modulus: 10 % 3 = {a % b}")
        print(f"Exponentiation: 10 ** 3 = {a ** b}")

        print("\n===== PEMDAS =====")
        print("Python follows the order of PEMDAS")
        print("when performing mathematical calculations.")

        print("P - Parentheses")
        print("E - Exponent")
        print("M - Multiplication")
        print("D - Division")
        print("A - Addition")
        print("S - Subtraction")

        print(f"\n2 + 3 * 4 = {2 + 3 * 4}")
        print(f"(2 + 3) * 4 = {(2 + 3) * 4}")
        
    # LESSON 5: FLOWCHART AND FLOWCHART SYMBOLS

    elif choice == "5":

        print("\n===== FLOWCHART =====")
        print("A flowchart is a diagram representing")
        print("the logical sequence of steps or operations.")
        print("It shows how a process or program works.")

        print("\nPURPOSE OF FLOWCHART:")
        print("1. Shows the steps of a program.")
        print("2. Makes program logic easier to understand.")
        print("3. Helps plan before coding.")

        print("\n===== FLOWCHART SYMBOLS =====")
        print("OVAL - Start or End")
        print("PARALLELOGRAM - Input or Output")
        print("RECTANGLE - Processing")
        print("ARROW - Direction of flow")
        print("CIRCLE - Connection")
        print("DIAMOND - Decision")
        print("HEXAGON - Declaration")

        print("\nThese symbols help represent")
        print("the steps of a program visually.")

    # LESSON 6: PROGRAM LOGIC

    elif choice == "6":

        print("\n===== PROGRAM LOGIC =====")
        print("Program logic is the sequence of instructions")
        print("that tells a computer how to solve a problem.")

        print("\nINPUT -> PROCESS -> OUTPUT")

        print("\nTHREE BASIC PROGRAMMING STRUCTURES:")

        print("\n1. SEQUENCE")
        print("Instructions are executed one after another.")

        print("\n2. SELECTION")
        print("The program chooses an action based on a condition.")

        print("\n3. ITERATION")
        print("Instructions are repeated until a condition is met.")

    # LESSON 7: LOGICAL OPERATORS

    elif choice == "7":

        print("\n===== LOGICAL OPERATORS =====")

        print("AND - True when both conditions are True.")
        print("OR - True when at least one condition is True.")
        print("NOT - Reverses True and False.")

        print("\n===== AND EXAMPLE =====")
        print(f"True and True = {True and True}")
        print(f"True and False = {True and False}")

        print("\n===== OR EXAMPLE =====")
        print(f"True or False = {True or False}")
        print(f"False or False = {False or False}")

        print("\n===== NOT EXAMPLE =====")
        print(f"not True = {not True}")
        print(f"not False = {not False}")

        print("\nPRACTICAL EXAMPLE:")

        age = 18
        has_id = True

        print(f"Age: {age}")
        print(f"Has ID: {has_id}")
        print(f"Can enter: {age >= 18 and has_id}")

    # LESSON 8: IF-ELSE IF-ELSE

    elif choice == "8":

        print("\n===== IF-ELSE IF-ELSE =====")
        print("This structure is used when there are")
        print("three or more possible outcomes.")

        print("\nBASIC FORMAT:")
        print("if condition:")
        print("    statement")
        print("elif condition:")
        print("    statement")
        print("else:")
        print("    statement")

        print("\nEXAMPLE: STUDENT GRADE")

        score = int(input("Enter your score: "))

        if score >= 90:
            print(f"Score: {score} - Excellent")
        elif score >= 75:
            print(f"Score: {score} - Passed")
        else:
            print(f"Score: {score} - Failed")

        print("\nThe program checks conditions from top to bottom.")
        print("The first TRUE condition is executed.")

    # LESSON 9: WHILE LOOP

    elif choice == "9":

        print("\n===== WHILE LOOP =====")
        print("A while loop repeats instructions")
        print("while its condition is True.")

        print("\nBASIC FORMAT:")
        print("while condition:")
        print("    statement")

        print("\nEXAMPLE 1: Display numbers 1 to 5")
        print("number = 1")
        print("")
        print("while number <= 5:")
        print('    print(f"Number: {number}")')
        print("    number = number + 1")

        number = 1

        while number <= 5:
            print(f"Number: {number}")
            number = number + 1

        print("\nEXAMPLE 2: Countdown")
        print("count = 5")
        print("")
        print("while count >= 1:")
        print('    print(f"Countdown: {count}")')
        print("    count = count - 1")

        count = 5

        while count >= 1:
            print(f"Countdown: {count}")
            count = count - 1

        print("Done!")

        print("\nThe loop stops when the condition becomes False.")

        print("\nEXAMPLE 3: WHILE TRUE")
        print("while True:")
        print('    print("Hello")')
        print("    break")

        print("\nwhile True repeats continuously")
        print("until a break statement stops the loop.")

    # EXIT

    elif choice == "0":
        
        print(f"\nThank you for using my Python Tutorial {user}!")
        print("Keep practicing and learning Python until you become pro!")
        print(" -_^")
        break

    else:

        print(f"\nInvalid choice: {choice}")
        print("Please choose a number from 0 to 9.")

    if choice != "0":
        input("\nPress ENTER or Enter anything to return to the main menu...")

