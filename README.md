# Assignment_BTech2026_-2201921630044-
This is a README file which will consist the details like
     > Problem Statement
     > Coding Platform Used
     > Approach and solution explaination
of daily problem solved of oops.

<b> 26th Jan </b>
Problem statement:
    We can store details related to a student in a class consisting of his age (int), first_name (string), last_name (string) and standard (int).

    You have to create a class, named Student, representing the student's details, as mentioned above, and store the data of a student. Create setter and getter functions for each element; that is, the class should at least have following functions:

    get_age, set_age
    get_first_name, set_first_name
    get_last_name, set_last_name
    get_standard, set_standard
    Also, you have to create another method to_string() which returns the string consisting of the above elements, separated by a comma(,). You can refer to stringstream for this.

    Input Format

    Input will consist of four lines.
    The first line will contain an integer, representing the age. The second line will contain a string, consisting of lower-case Latin characters ('a'-'z'), representing the first_name of a student.
    The third line will contain another string, consisting of lower-case Latin characters ('a'-'z'), representing the last_name of a student.
    The fourth line will contain an integer, representing the standard of student.

    Note: The number of characters in first_name and last_name will not exceed 50.  

    Output Format

    The code provided by HackerRank will use your class members to set and then get the elements of the Student class.

Platform used: HackerRank

Approach and Solution:
    This was a simple question related to class,
    And I used C++ to solve this problem.
    So, the main tasks were:-
    >Create the required Student classwith the mentioned atrributes.
    >Implement setter and getter on every attribute mentioned.
    >Use of to_string method to  format the student's information as a string in a specific format.
    >Read the input values and use the methods.

<b>27th Jan</b>
Problem Statement:
    Create a derived class from base class Triangle named as Isosceles Triangle which will contain description function and isosceles function.
    Show the inheritance.

Platform used: HackeRank

Approach and Solution:
    Inheritance is one of the major property of Object Oriented Programming. Inheritance allows us to define a class in terms of other class and increases the reusability of the code. In this problem we will first create base class Triangle with method triangle and then inherit it with another derived class called Isosceles with two methods isosceles and description. And then, in main function we will create a object of Isoceles(i.e. derived class) and with that we will call the methods of both the class. 

<b>28th Jan</b>
Problem Statement:
    We have a class A which is the base class and we have a class B which is derived from class A and we have a class C which is derived from class B, we can access the functions of both class A and class B by creating an object for class C. Hence, this mechanism is called multi-level inheritance. (B inherits A and C inherits B.)

    Create a class called Equilateral which inherits from Isosceles and should have a function such that the output is as given below.

    I am an equilateral triangle
    I am an isosceles triangle
    I am a triangle

Platform Used: HackerRank

Approach and solution:
    This is a problem related to Multi level inheritance. it is a type of inherritance in which Class B inherits class A and further class C inherits class B. So, we can access the methods of both the class(i.e, class A and class B) from the object of class C. 
