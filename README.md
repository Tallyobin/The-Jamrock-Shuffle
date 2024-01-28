# https://chat.openai.com/share/0beb0f51-84f3-4dcd-a1dc-fe32d8a72944

```
1. Which of the following is NOT a function available with iostream?
   A. cin
   B. cout
   C. endl
 = D. namespace


2. Which of the following describe about cin object?
   A. Store data from the keyboard only.
 = B. Accepts a stream of data from the standard input device.
   C. Outputs a stream of data from the standard input device.
   D. Accepts a stream of data from the standard output device.


3. A function prototype will tell the ____________ that there exist a function with this name defined at begin in the program and therefore it can be used even though the function has not yet been defined at that point.
   A. call
 = B. compiler
   C. computer
   D. prototype


4. In order to write and use our own function, we need NOT do these:

   I. Create a function prototype.
   II. Include header file for standard input output.
   III. Call the function whenever it need to be used.
   IV. Define the function at beginning of the program.

   A. I only
 = B. IV only
   C. I and III only
   D. I, II and III


5. Which of the following is a right example for the function call?
   A. add(int, int);
   B. add(num1, num2);
 = C. add(int num, int num2);
   D. void add(int num, int num2);


6. Which statement dynamically allocates an array of integers of n elements?
   A. int numbers[n];
   B. int *numbers[n];
   C. int numbers = new int[n];
 = D. int *numbers = new int[n];**


7. Which of the following is the proper keyword to deallocate memory in C++?
   A. free
   B. clear
 = C. delete
   D. remove


8. Choose the correct way(s) to declare a 2-dimensional array with 2 rows and 3 columns.

   I. int arr [2][3];
   II. int arr [3][2];
   III. int arr [ ][ ] = { 2, 3, 4 };
   IV. int arr [ ][ ] = { { 2, 3, 4 }, {5, 6, 7 } };

 = A. I only
   B. II only
   C. I and III only
   D. I, II and III


9. Which of the following is NOT describe about a structure?
   A. We can have pointers of type structures.
   B. Defining a structure is like defining a new data type.
   C. A structure may contain members of many data types.
 = D. A structure may contain function as members of its elements.


10. Which of the following is a properly defined struct?
    A. struct { int x; }
    B. struct my_struct int x;
  = C. struct my_struct{ int x; }
    D. struct my_struct{ int x; };


11. Which symbol is used to define the member of a class externally?
    A. :
    B. #
  = C. ::
    D. };


12. Which of the following is declare just like a regular member function, but with a name that matches the class name and without any return type?
    A. Cass
    B. Object
  = C. Constructor
    D. User-defined


13. The default constructor does not take any __________.
    A. return
    B. function
    C. data type
  = D. parameter


14. When constructor is invoked automatically?
    A. A class is defined.
    B. A class is referenced.
  = C. An object is instantiated.
    D. An object is called by a function.


15. What will be the output if the string syafiqah is entered in code Figure 1?

    Char name[20];
    cout << “Enter your name : ” ;
    cin.width(5);
    cin >> name;
    cout << name << endl;

    Figure 1

  = A. syaf
    B. syafi
    C. syafiq
    D. syafiqah


16. Which stream manipulator forces a floating point number to display a specific number of digits to the right of the decimal point?
  = A. fixed
    B. setw()
    C. width()
    D. scientific


17. Which stream manipulator is used to reset function showpos back to default display mode?
  = A. noshowpos
    B. stopshowpos
    C. cancelshowpos
    D. removeshowpoint


18. Which stream manipulator forces a floating point number to be output with its decimal point and trailing zeros?
    A. showcase
  = B. showpoint
    C. showarray
    D. noshowpoint


19. Which class file handle both file input and output?
    A. infile
    B. outfile
  = C. fstream
    D. ofstream


20. What does it mean by ofstream in C++?
    A. Delete the file.
  = B. Writes to a file.
    C. Reads from a file.
    D. Writes to a file & Reads from a file.


1. Which of the following correctly declares an array?
 = A. float rainfall[8];
   B. float rainfall;
   C. rainfall{8};
   D. rainfall[8] float;


2. Which reference modifier is used to define reference variable?
 = A. &
   B. $
   C. #
   D. >>


3. The standard output stream in C++ is represented by _______ operator.
 = A. <<
   B. >>
   C. ==
   D. %


4. The standard input stream in C++ is represented by _______ operator.
   A. <<
 = B. >>
   C. ==
   D. %


5. What will happen when we use void in argument passing?
 = A. It will not return value to its caller.
   B. It will return value to its caller.
   C. Maybe or may not be returning value to its caller.
   D. All of the above.


6. Which symbol is used to terminate a class definition?
   A. *
   B. &
 = C. };
   D. {


7. A function has been declared through the following prototype:

   float process salary (int, char);

   Which statement is true for this function?

 = A. This function returns no value.
   B. This function returns two values which are an integer and a character.
   C. During the function call, a value of type float is passed to the function.
   D. During the function call, two values are passed to the function.


8. What will be the output of the following code segment in Figure 1?

   enum Fruits {orange, apple, pear};
   Fruits Myfave = orange;
   cout << "My favorite fruit is: " <<Myfave;

   Figure 1

   A. My favorite fruit is orange
 = B. My favorite fruit is 0
   C. My favorite fruit is 1
   D. No output generator: error


9. Which the following is the correct function prototype for the function call below?

   functionABC (10, 2, 3.5) ;

   A. int functionABC(float, float, int);
   B. void functionABC(int, float, int);
 = C. void functionABC(int, int, float);
   D. void functionABC(int, float);


10. What is the output of the following code segment in Figure 2?

    #include<iostream>
    using namespace std;
    int main() {
       int a[] = {10,20,30};
       cout<<*a+1;
    }
 
    Figure 2
 
    A. 10
    B. 20
  = C. 21
    D. 11


11. If x is an integer and p and q are pointers to integers, which of the following assignments will not cause a compilation error?
    A. p = **&q;
    B. x = *&p;
  = C. q = *&x;
    D. p = &x;


12. Which the following is used to call function within a class?
    A. Member
    B. Operator
    C. Class
  = D. Method


13. What will be the output of the following code segment in Figure 3?

    void fun (int*, int*);
    int main(){
       int i=5, j=2;
        fun (&i, &j);
         cout << i << j;
        return 0;
    }
    void fun (int *i, int *j)
    {
        *i = *i**i;
        *j = *j**j;
    }
 
    Figure 3

    A. 5 2
  = B. 10 4
    C. 2 5
    D. 25 4


14. All of the following is a valid access specifier in a class EXCEPT:
    A. private
    B. public
    C. protected
  = D. encapsulated


15. How many times a derived class can inherit from a base class?
  = A. One
    B. Maximum three
    C. Maximum five
    D. More than one
```
