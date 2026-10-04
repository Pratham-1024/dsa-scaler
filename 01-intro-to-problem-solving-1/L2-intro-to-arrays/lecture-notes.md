Arrays: The Building Blocks of Data Structures
Arrays are fundamental data structures in almost all programming languages. They provide a simple yet effective way to store a fixed-size, sequential collection of elements of the same data type.

What is an Array?
An array is a data structure consisting of a collection of elements (values or variables), each identified by at least one array index or key.

Homogeneous: All elements in an array must be of the same data type (e.g., all integers, all strings).
Contiguous Memory: Array elements are stored in adjacent or contiguous memory locations. This allows for fast, random access to any element.
Fixed Size: Once an array is created, its size is usually fixed and cannot be changed during execution.
Key Characteristics
Characteristic	Description
Indexing	Elements are accessed using a zero-based index (0, 1, 2, ...).
Data Type	All elements must share the same data type.
Access Time	O(1) time complexity for accessing any element.
Memory	Contiguous block of memory is allocated for the entire array.
Image URL: https://drive.google.com/file/d/10xlTFiU612CCXkg44qCW_gv45xjb4nAu/view?usp=drive_link

Types of Arrays
Arrays can be broadly classified based on the number of indices used to access an element.

1. One-Dimensional Arrays (1D)
A one-dimensional array is the simplest form of an array, where elements are arranged in a single row or column. You need only one index to access an element.

Example: A list of student scores.
scores = [85, 92, 78, 95, 88]

Index	Value
0	85
1	92
2	78
3	95
4	88
2. Multi-Dimensional Arrays
These arrays require more than one index to access an element. The most common is the two-dimensional array (2D array).

Two-Dimensional Arrays ( 2D )
Often visualized as a table or a matrix, a 2D array is essentially an array of arrays. It requires two indices: one for the row and one for the column.

Example: A 3*3 matrix.

Index (Row, Col)	Col 0	Col 1	Col 2
Row 0	10	11	12
Row 1	20	21	22
Row 2	30	31	32
