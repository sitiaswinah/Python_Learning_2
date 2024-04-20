# Python_Learning_2
Repository for beginners learning Python programming language

# Function
In Python, a function is a block of reusable code that performs a specific task. Functions allow you to break down your program into smaller, manageable pieces, making your code more modular, readable, and easier to maintain.

**Let's break down the components:**
- def: It's a keyword used to define a function.
- function_name: It's the name of the function. Choose a descriptive name that reflects the purpose of the function.
- parameters: They are optional, and you can pass zero or more parameters to a function. Parameters are variables that receive values when the function is called.
- docstring: It's an optional string literal that describes what the function does. It's good practice to include a docstring to document the purpose, usage, and parameters of the function.
- Function body: It's the block of code inside the function where you write the operations to be performed.
- return: It's a keyword used to return a value from the function. The return statement is optional, and if omitted, the function returns None.
- result: It's the value returned by the function.
  
**Return:**
In Python, the return statement is used within a function to exit the function and return a value or an expression to the caller. When a return statement is encountered in a function, the function's execution is terminated immediately, and control is passed back to the point where the function was called from.

**Modify**
To modify a list within a function in Python, you can pass the list as an argument to the function and make changes to it directly within the function. Since lists are mutable objects in Python, any modifications made to the list inside the function will affect the original list.

**Create a function (parameters are changed and parameters are assigned**

# Pandas & NumPy
**Pandas** → used to manipulate data, such as creating tables, changing data dimensions, checking data, and so on (examples of Pandas formats: xlsx, csv, txt, and so on)

**NumPy** → NumPy is a library for processing and manipulating data in array form. From a variety of integrated mathematical functions to the ease of creating and manipulating arrays, NumPy ensures we can focus on extracting information rather than being bogged down by technical limitations.

# Pandas has two objectives, namely Series and Data Frame
# 1. Object Series
Object Series has one data dimension. It doesn't have a column name because it only has one column and it has an index

1. Displays index
The index is a range where the start point is inclusive in the range and the stop point is exclusive to the range
- The implicit index is the default index (built into Python)
- Explicit index, we can define the index (defined index)
2. data selection
walaupun kita sudah membuat indeks eksplisit, kita masih bisa memanggil indeks implisit nya
when the implicit index and the explicit index are the same, when we call the data, it will only rely on the explicit index
3. data slicing
mengekstrak bagian data dan mengembalikannya sebagai data baru, tanpa mengubahnya
tapi bila kita slicing indeks implisit nya, maka hanya akan muncul titik start nya. karena indeks implisit berupa range

**Loc dan Iloc**
Loc and iloc are two functions in Pandas that are used to slice data sets in Pandas DataFrame

**Fungsi .loc** usually used for label indexing and can access multiple columns
Loc is short for 'location'. As the name suggests, it is used to select data at certain locations only

**Fungsi  .iloc** digunakan untuk pengindeksan bilangan bulat.
loc is short for 'index location'. Just like loc, it is used to select data at certain locations only. The only difference is, if loc selects data from one row to another and from one column to another column, then iloc selects data from one row to one row before another row and between one column and one column before another column. The concept is exactly like the index in an array.
Note: the iloc concept does not recognize column names. Column names will be replaced with column indexes starting from zero onwards.

# 2. Data Frame
A data frame is a data structure constructed with rows and columns, similar to a database or Excel spreadsheet.

DataFrame Structure
The DataFrame structure consists of three main components, namely indexes, columns, and values.
- Indexs
An index is a label used to identify each row in a DataFrame.
- Columns
Columns are labels used to identify each column in a DataFrame. Each column has a unique label.
- Values
Values are the actual data stored in a DataFrame.

**DataFrame from CSV, Excel file**
To create a DataFrame from a CSV (Comma-Separated Values) file, you can use the pd.read_csv() method.

# Random Python
The Python Random module generates random numbers in Python. It is a pseudo-random number meaning it is not truly random. This module can be used to perform random actions such as generating random numbers, printing random values ​​for lists or strings, etc. This is a built-in function in Python

# Datetime
Modul datetime menyediakan kelas untuk memanipulasi tanggal dan waktu.
Meskipun aritmatika tanggal dan waktu didukung, fokus penerapannya adalah pada ekstraksi atribut yang efisien untuk pemformatan dan manipulasi keluaran.

# txt file - open, read, close
Memasukan file berupa .txt ke jupiter NoteBook












