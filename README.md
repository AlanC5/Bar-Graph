# Bar-Graph
Used FLTK to generate a bar graph of grades from user input (number of students)
After receiving the number of students, the user is asked to randomly generate the grades or input them manually. Once the grades have been created, users will be asked to enter a color for the axis, labels, columns, and line.

The bar graph will display 10 grade intervals (0-10, 11-20, etc). A dotted line will connect the center top of each interval/bar. The y axis will vary based on the number of students. For example, if the interval 81-90 has 20 students, then the y axis will expand from the default 10 and have at least 20 ticks/dashes. 


The program was written in Eclipse with some modifications to: 

Properties -> C/C++ Build -> Settings -> MacOS X C++ Linker -> Libraries  

Properties -> C/C++ Build -> Settings -> GCC C++ Compiler -> Includes

Reference for Graph.h: http://www.stroustrup.com/Programming/PPP2code/Graph.h

# Example
[Bar (input)](https://github.com/AlanC5/Bar-Graph/blob/master/Bar%20(1).png)

[Bar (ouput)](https://github.com/AlanC5/Bar-Graph/blob/master/Bar%20(2).png)