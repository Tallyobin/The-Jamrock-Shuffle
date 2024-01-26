Page 1 of 12
COLLEGE OF COMPUTING AND INFORMATICS
PUTRAJAYA CAMPUS
FINAL EXAMINATION
SEMESTER 1 2022/2023
PROGRAMME : Diploma in Computer Science
SUBJECT CODE : CMPD244/CMPD293
SUBJECT : Programming 2
DATE : December 2022 / January 2023
DURATION : 2 Hours 30 Minutes
INSTRUCTIONS TO CANDIDATES:
1. The total marks for this exam is 75.
2. There are TWO (2) SECTIONS to this paper: Section A and Section B.
3. Answer ALL questions in the answer booklet provided.
4. When answering questions involving any kind of calculation, please show your
work.
__________________________________________________________________
THIS QUESTION PAPER CONSISTS OF TWELVE (12) PRINTED PAGES
INCLUDING THIS COVER PAGE
CMPD244/CMPD293, Semester 1, 2022/2023
Page 2 of 12
SECTION A: MULTIPLE CHOICES (20 QUESTIONS, 20 MARKS)
Instruction: Please CHOOSE the BEST answer from the choices given.
1. Which of the following is NOT a function available with iostream?
A. cin
B. cout
C. endl
D. namespace
2. Which of the following describe about cin object?
A. Store data from the keyboard only.
B. Accepts a stream of data from the standard input device.
C. Outputs a stream of data from the standard input device.
D. Accepts a stream of data from the standard output device.
3. A function prototype will tell the ____________ that there exist a function with
this name defined at begin in the program and therefore it can be used even though
the function has not yet been defined at that point.
A. call
B. compiler
C. computer
D. prototype
4. In order to write and use our own function, we need NOT do these:
I. Create a function prototype.
II. Include header file for standard input output.
III. Call the function whenever it need to be used.
IV. Define the function at beginning of the program.
A. I only
B. IV only
C. I and III only
D. I, II and III
CMPD244/CMPD293, Semester 1, 2022/2023
Page 3 of 12
5. Which of the following is a right example for the function call?
A. add(int, int);
B. add(num1, num2);
C. add(int num, int num2);
D. void add(int num, int num2);
6. Which statement dynamically allocates an array of integers of n elements?
A. int numbers[n];
B. int *numbers[n];
C. int numbers = new int[n];
D. int *numbers = new int[n];**
7. Which of the following is the proper keyword to deallocate memory in C++?
A. free
B. clear
C. delete
D. remove
8. Choose the correct way(s) to declare a 2-dimensional array with 2 rows and 3
columns.
I. int arr [2][3];
II. int arr [3][2];
III. int arr [ ][ ] = { 2, 3, 4 };
IV. int arr [ ][ ] = { { 2, 3, 4 }, {5, 6, 7 } };
A. I only
B. II only
C. I and III only
D. I, II and III
CMPD244/CMPD293, Semester 1, 2022/2023
Page 4 of 12
9. Which of the following is NOT describe about a structure?
A. We can have pointers of type structures.
B. Defining a structure is like defining a new data type.
C. A structure may contain members of many data types.
D. A structure may contain function as members of its elements.
10. Which of the following is a properly defined struct?
A. struct { int x; }
B. struct my_struct int x;
C. struct my_struct{ int x; }
D. struct my_struct{ int x; };
11. Which symbol is used to define the member of a class externally?
A. :
B. #
C. ::
D. };
12. Which of the following is declare just like a regular member function, but with a
name that matches the class name and without any return type?
A. Cass
B. Object
C. Constructor
D. User-defined
13. The default constructor does not take any __________.
A. return
B. function
C. data type
D. parameter
CMPD244/CMPD293, Semester 1, 2022/2023
Page 5 of 12
14. When constructor is invoked automatically?
A. A class is defined.
B. A class is referenced.
C. An object is instantiated.
D. An object is called by a function.
15. What will be the output if the string syafiqah is entered in code Figure 1?
Char name[20];
cout << “Enter your name : ” ;
cin.width(5);
cin >> name;
cout << name << endl;
Figure 1
A. syaf
B. syafi
C. syafiq
D. syafiqah
16. Which stream manipulator forces a floating point number to display a specific
number of digits to the right of the decimal point?
A. fixed
B. setw()
C. width()
D. scientific
17. Which stream manipulator is used to reset function showpos back to default
display mode?
A. noshowpos
B. stopshowpos
C. cancelshowpos
D. removeshowpoint
CMPD244/CMPD293, Semester 1, 2022/2023
Page 6 of 12
18. Which stream manipulator forces a floating point number to be output with its
decimal point and trailing zeros?
A. showcase
B. showpoint
C. showarray
D. noshowpoint
19. Which class file handle both file input and output?
A. infile
B. outfile
C. fstream
D. ofstream
20. What does it mean by ofstream in C++?
A. Delete the file.
B. Writes to a file.
C. Reads from a file.
D. Writes to a file & Reads from a file.
CMPD244/CMPD293, Semester 1, 2022/2023
Page 7 of 12
SECTION B: SHORT ANSWERS (9 QUESTIONS, 55 MARKS)
Instruction: Please answer ALL the questions.
Question 1
(a) What are the output for the codes in Figure 2?
int i=5, j=6, k =7, n=3;
cout << i +j * k - k % n << endl;
cout << i / n << endl;
Figure 2
[2 marks]
(b) Refer to the following segment of code in Figure 3 to answer questions below.
int num;
cout << “Enter a number : ”;
cin >> num;
if (num > 7)
cout << num << “ is greater than 7” << endl;
else if (num < 7)
cout << num << “ is less than 7” << endl;
else
cout << “Thank you!” << endl;
Figure 3
(i) What will be the output if user enters the integer value -5?
[1 mark]
(ii) What will be the output if user enters the integer value 9?
[1 mark]
(iii) What is the values for num will cause the output of the code to be Thank
you!?
[1 mark]
CMPD244/CMPD293, Semester 1, 2022/2023
Page 8 of 12
(c) What are the output for the codes in Figure 4?
class Box {
public:
double length, breadth, height;
int cal(){
return 2 * height * length;
}
};
void main()
{
Box Box1;
Box Box2;
double volume = 0.0;
Box1.height = 5.0;
Box1.length = 6.0;
Box1.breadth = 7.0;
Box2.height = 10.0;
Box2.length = 12.0;
Box2.breadth = 13.0;
volume = Box1.height * Box1.length * Box1.breadth;
cout << "Volume of Box1 : " << volume <<endl;
volume = Box2.cal();
cout << "Volume of Box2 : " << volume <<endl;
}
Figure 4
[2 marks]
Question 2
Identify and correct the errors in the following code segments. You need to rewrite a
full line of the code that has error with the new corrected code.
(a)
int x = 1, total;
while (x <= 10)
{
total = total + x;
++x;
}
[1 mark]
CMPD244/CMPD293, Semester 1, 2022/2023
Page 9 of 12
(b)
void printResult(float x, float y)
{
float sum = x + y;
return sum;
}
[1 mark]
(c)
while (y > 0)
{
cout << y << endl
++y;
}
[1 mark]
(d)
double d[2][10] ;
d[1, 9] = 4.135 ;
[1 mark]
Question 3
Write the statements to only allow user to insert one positive integer number between
1 to 10 only. If the user inserts the number outside from the range, the program will ask
the user to enter the number again. You can use any name for the variable.
[3 marks]
CMPD244/CMPD293, Semester 1, 2022/2023
Page 10 of 12
Question 4
Modify the program in Figure 5 so that all parameters in function1() uses pointers
enabling function call by reference. You only need to modify at lines of function
prototype, function call and function definition.
#include <iostream>
using namespace std;
int function1(int, int, int);
int main()
{
int a=3, b=4, sum=0;
sum=function1(a, b, sum);
cout << sum;
}
int function1(int a, int b, int sum)
{
sum=a+b;
return sum;
}
Figure 5
[7 marks]
Question 5
(a) Write a function named swap_floats that takes the address of two floating
point arguments and interchanges the values that are stored in those arguments.
The function should return no value.
[5 marks]
(b) Briefly describe what does the keyword new allows you to do?
[2 marks]
(c) Write a segment code that dynamically allocate an array of 15 items of floats.
Show the variable declaration and you can use any name of variable.
[2 marks]
CMPD244/CMPD293, Semester 1, 2022/2023
Page 11 of 12
Question 6
Write a segment codes that ask user to enter 5 numbers from user. Then, find and
display reverse of the given number using loop. You need to implement array concept.
[6 marks]
Question 7
Create a structure called committee with the following details as variables within it.
 Full Name
 Year of Study
 CGPA
 Designation
Then, write a necessary code segment to create objects for the structure to access and
print the name, year of study, CGPA and designation for one user. Assume there are
values for all elements of the object.
[8 marks]
Question 8
Referring to the code segment in Figure 6, add a code snippet creating a class named
Child, which inherits both class OneA and OneB.
#include <iostream>
using namespace std;
class OneA{
public:
OneA(int A, int B){}
};
class OneB{
};
Figure 6
[3 marks]
CMPD244/CMPD293, Semester 1, 2022/2023
Page 12 of 12
Question 9
Use stream manipulator to format the output by modifying the program in Figure 7 so
that an output as shown in Figure 8 can be achieved.
#include <iostream>
#include <string>
#include <iomanip>
using namespace std;
int main(void)
{
string s1 = "Lets Do It";
string s2 = "Are you ready?";
double a = 17.15;
double b = 69.28;
cout << s1 << endl;
cout << a << endl;
cout << s2 << endl;
cout << b << endl;
}
Figure 7
Figure 8
[8 marks]
---End of Questions---



Page 1 of 9
COLLEGE OF COMPUTING AND INFORMATICS
PUTRAJAYA CAMPUS
FINAL EXAMINATION
SEMESTER 2 2022/2023
PROGRAMME : Diploma in Computer Science
SUBJECT CODE : CMPD244/CMPD293
SUBJECT : Programming 2
DATE : May 2023
DURATION : 2 Hours 30 Minutes
INSTRUCTIONS TO CANDIDATES:
1. The total mark for Final Exam is 100 including Practical Exam 30 marks.
2. The total mark for this exam is 70.
3. There are TWO (2) SECTIONS to this paper: Section A and Section B.
4. Answer ALL questions in the answer booklet provided.
5. Write the answer to EACH question on a new page.
_____________________________________________________________________
THIS QUESTION PAPER CONSISTS OF NINE (9) PRINTED PAGES
INCLUDING THIS COVER PAGE
CMPD244/CMPD293, Semester 2, 2022/2023
Page 2 of 9
SECTION A: MULTIPLE CHOICES (15 QUESTIONS, 22.5 MARKS)
Instruction: Please CHOOSE the BEST answer from the choices given.
1. Which of the following correctly declares an array?
A. float rainfall[8];
B. float rainfall;
C. rainfall{8};
D. rainfall[8] float;
2. Which reference modifier is used to define reference variable?
A. &
B. $
C. #
D. >>
3. The standard output stream in C++ is represented by _______ operator.
A. <<
B. >>
C. ==
D. %
4. The standard input stream in C++ is represented by _______ operator.
A. <<
B. >>
C. ==
D. %
5. What will happen when we use void in argument passing?
A. It will not return value to its caller.
B. It will return value to its caller.
C. Maybe or may not be returning value to its caller.
D. All of the above.
CMPD244/CMPD293, Semester 2, 2022/2023
Page 3 of 9
6. Which symbol is used to terminate a class definition?
A. *
B. &
C. };
D. {
7. A function has been declared through the following prototype:
Which statement is true for this function?
A. This function returns no value.
B. This function returns two values which are an integer and a character.
C. During the function call, a value of type float is passed to the function.
D. During the function call, two values are passed to the function.
8. What will be the output of the following code segment in Figure 1?

 Figure 1
A. My favorite fruit is orange
B. My favorite fruit is 0
C. My favorite fruit is 1
D. No output generator: error
9. Which the following is the correct function prototype for the function call
below?
A. int functionABC(float, float, int);
B. void functionABC(int, float, int);
C. void functionABC(int, int, float);
D. void functionABC(int, float);
CMPD244/CMPD293, Semester 2, 2022/2023
Page 4 of 9
10. What is the output of the following code segment in Figure 2?

 Figure 2
A. 10
B. 20
C. 21
D. 11
11. If x is an integer and p and q are pointers to integers, which of the following
assignments will not cause a compilation error?
A. p = **&q;
B. x = *&p;
C. q = *&x;
D. p = &x;
12. Which the following is used to call function within a class?
A. Member
B. Operator
C. Class
D. Method
CMPD244/CMPD293, Semester 2, 2022/2023
Page 5 of 9
13. What will be the output of the following code segment in Figure 3?

 Figure 3
A. 5 2
B. 10 4
C. 2 5
D. 25 4
14. All of the following is a valid access specifier in a class EXCEPT:
A. private
B. public
C. protected
D. encapsulated
15. How many times a derived class can inherit from a base class?
A. One
B. Maximum three
C. Maximum five
D. More than one
CMPD244/CMPD293, Semester 2, 2022/2023
Page 6 of 9
SECTION B: SHORT ANSWERS (5 QUESTIONS, 47.5 MARKS)
Instruction:Answer ALL questions.
Question 1
(a) Answer the following questions by referring to Figure 4.
 Figure 4
(i) Identify ONE (1) class name from the code segment in Figure 4.
 [1 mark]
(ii) Identify and explain the access modifier in Line 2.
[2 marks]
(iii) Identify ONE (1) object declared in Line 8.
 [1 mark]
(iv) What is the purpose of executing the instruction in Line 9?
[2 marks]
(i) What is the output executed in Line 4?
[2 marks]
(b) Discuss the concept of base class and derived class in public inheritance.
 [4 marks]
CMPD244/CMPD293, Semester 2, 2022/2023
Page 7 of 9
Question 2
(a) Write a statement in C++ to display the following messages in TWO (2)
separate lines on the screen without directive using namespace std.
“Everyone should learn to program a computer, because it teaches you how to
think” – Steve Jobs
 [3 marks]
(b) With reference to Figure 5 and 6 below, answer the following questions.
(i) Trace the output for code segment in Figure 5.
 Figure 5
 [1 mark]
(ii) Trace the output for code segment in Figure 6.
 Figure 6
[1.5 marks]
CMPD244/CMPD293, Semester 2, 2022/2023
Page 8 of 9
Question 3
Identify EIGHT (8) errors from the program segment in Figure 7, then RE-WRITE
the whole program by showing out how do you correct all identified errors. Make sure
you UNDERLINE / HIGHLIGHT THE CORRECTIONS that you have made.
 Figure 7
 [16 marks]
Question 4
Given the following incomplete C++ program segment in Figure 8 below. Fill in the
blanks from (a) to (j) with the correct codes so the program can be executed completely.
 Figure 8
[10 marks]
CMPD244/CMPD293, Semester 2, 2022/2023
Page 9 of 9
Question 5
Trace the output for the following program in Figure 9, assuming the address of variable
num1 is 12h843 and the address of variable num2 is 14h792.
 Figure 9
[4 marks]
---End of Questions---
#include <iostream>
using namespace std;
void main(void) {
 int num1 = 2;
 int num2 = 4;
 int *ptrvar = &num1;
 int *ptrvb = &num2;
 cout<<“The address of the variable num1 is:”<< &num1 <<endl;
 cout<<“The value of the pointer ptrvar is:”<< ptrvar <<endl;
 cout<<“The value of the variable num2 is:”<< num2 <<endl;
 cout<<“The value of *ptrvb is:”<< *ptrvb <<endl;
}
