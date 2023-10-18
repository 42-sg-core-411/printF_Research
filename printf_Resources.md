Variadic Functions:

a) https://www.linkedin.com/pulse/modern-c-variadic-functions-how-shoot-yourself-foot-avoid-zinin

b) https://medium.com/swlh/variadic-function-in-c-programming-d3632315a48e

c) https://en.cppreference.com/w/c/variadic

d) https://www.youtube.com/watch?v=Hb2m7htiKWM

 Points that can be brought up during Evaluation/Defence:
1) Why do you need to separate out the functions eg. process string/hexadecimal into a separate c file, can they be done together in one file?
Answer: For easier reading, function will not be as wordy/wall of text.

2) Variadic argument can be useful for future proofing your code, especially when you want to calculate an average that has dynamically changing sample sizes. (see 4:20 - 8:30 of https://www.youtube.com/watch?v=7Sph8JlRo0g)

3) Why do programmers use hexadecimal numbers?:
Hexadecimal is base 16, where by A means 10 and so on until F means 15. (3:10 to 3:26 of https://www.youtube.com/watch?v=dPxCGlW9lfM)
Learning to use hexadecimals is important for programming, as they are used very often in memory and network addresses to see where one byte ends and another byte begins.
(4:30 to 5:12 of https://www.youtube.com/watch?v=dPxCGlW9lfM)

4) What Is The Point Of Hexadecimal? (GCSE)
Hexadecimals are used in error codes and error reports as hexadecimal words or numbers to help identify in one look what the report is about.
(see 4:10 to 5:36 of https://www.youtube.com/watch?v=ViRR7qoeMpU)

5) Variable Naming Convention
    a) Use Descriptive Names: Variable names should be meaningful and describe the purpose of the variable.
    This makes your code self-explanatory. For example, instead of int x, use int numberOfStudents.

    b) Be Consistent: Stick to a consistent naming convention throughout your code.
    Consistency makes it easier for you and others to read and maintain the code.

    c) Hungarian Notation: Some developers use Hungarian notation to prefix variable names with one or more lowercase letters
    to indicate their data type. For example, int iCount, char cInitial.

    d) Use Meaningful Prefixes (If Applicable): In some cases, adding a meaningful prefix can clarify the variable's purpose.
    For example, strName for a string or bIsOpen for a boolean.

    e) Self-Documenting Names: Variable names should be self-documenting whenever possible.
    A well-chosen name can replace the need for a comment.

    f) Use Uppercase for Constants: If a variable is a constant, use uppercase letters with underscores to separate words.
    For example, MAX_LENGTH, PI.

    g) Use All Uppercase for Macros: Macros are usually defined in all uppercase letters.
    For example, #define BUFFER_SIZE 256.

    h) Avoid Underscores at the Beginning: Avoid starting variable names with underscores.
    Some naming conventions reserve such names for system or compiler use.

    i) Use Plural for Collections: If a variable represents a collection or array, use a plural form to indicate it.
    For example, int students[] instead of int student[].

    j) Short and Common Loop Variables: It's common to use short variable names for loop counters.
    Single-letter variables like i, j, and k are often used. They are widely recognized as loop counters.

    k) Avoid Using Single Letters: Single-letter variable names should be reserved for very short, local scopes like loop counters.
    In larger scopes or when the variable's purpose is not immediately clear, use descriptive names.
