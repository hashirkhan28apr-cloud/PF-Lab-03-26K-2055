
Problem 1: Display Student Information


START
    // Declare variables with appropriate data types
    DECLARE STRING studentName = "Hashir Khan"
    DECLARE STRING rollNumber = "26K-2055"
    DECLARE INTEGER age = 20
    DECLARE REAL height = 5.8
    DECLARE REAL gpa = 3.75
    DECLARE CHARACTER section = 'A'

    // Display the student details
    PRINT "--- STUDENT INFORMATION ---"
    PRINT "Name: ", studentName
    PRINT "Roll Number: ", rollNumber
    PRINT "Age: ", age
    PRINT "Height: ", height
    PRINT "GPA: ", gpa
    PRINT "Section: ", section
END



Problem 2: Read and Display a Character


START
    // Declare character variable
    DECLARE CHARACTER userChar

    // Prompt user and take input using character input method
    PRINT "Enter a single character: "
    READ userChar USING getchar()

    // Display the character using character output method
    PRINT "The character you entered is: "
    WRITE userChar USING putchar()
END



Problem 3: Display Floating-Point Value Precision


START
    // Declare floating-point variable
    DECLARE REAL num

    // Prompt and receive input
    PRINT "Enter a floating-point number: "
    READ num

    // Display with different precision settings
    PRINT "Default Precision: ", num
    PRINT "2 Decimal Places: ", FORMAT(num, 2)
    PRINT "4 Decimal Places: ", FORMAT(num, 4)
    PRINT "6 Decimal Places: ", FORMAT(num, 6)
END
