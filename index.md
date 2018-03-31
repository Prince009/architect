---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](another-page).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# [](#header-1)Infosys interview Questions And Answers

1.Difference between C and C++?

 

a) C follows the procedural programming paradigm while C++ is a multi-paradigm language (procedural as well as object oriented)
In case of C, importance is given to the steps or procedure of the program while C++ focuses on the data rather than the process.
Also, it is easier to implement/edit the code in case of C++ for the same reason.
b) In case of C, the data is not secured while the data is secured (hidden) in C++
This difference is due to specific OOP features like Data Hiding which are not present in C.
c) C is a low-level language while C++ is a middle-level language
C is regarded as a low-level language (difficult interpretation & less user friendly) while C++ has features of both low-level (concentration on what's going on in the machine hardware) & high-level languages (concentration on the program itself) & hence is regarded as a middle-level language.
d) C uses the top-down approach while C++ uses the bottom-up approach
In case of C, the program is formulated step by step, each step is processed into detail while in C++, the base elements are first formulated which then are linked together to give rise to larger systems.
e) C is function-driven while C++ is object-driven
Functions are the building blocks of a C program while objects are building blocks of a C++ program.
f) C++ supports function overloading while C does not
Overloading means two functions having the same name in the same program. This can be done only in C++ with the help of Polymorphism (an OOP feature)
g) We can use functions inside structures in C++ but not in C.
In case of C++, functions can be used inside a structure while structures cannot contain functions in C.
h) The NAMESPACE feature in C++ is absent in case of C
C++ uses NAMESPACE which avoid name collisions. For instance, two students enrolled in the same university cannot have the same roll number while two students in different universities might have the same roll number. The universities are two different namespace & hence contain the same roll number (identifier) but the same university (one namespace) cannot have two students with the same roll number (identifier)
i) The standard input & output functions differ in the two languages
C uses scanf & printf while C++ uses cin>> & cout<< as their respective input & output functions
j) C++ allows the use of reference variables while C does not
Reference variables allow two variable names to point to the same memory location. We cannot use these variables in C programming.
k) C++ supports Exception Handling while C does not.
C does not support it "formally" but it can always be implemented by other methods. Though you don't have the framework to throw & catch exceptions as in C++.

2.What is null pointer?

When referring to computer memory, a null pointer is a command used to direct a software program or operating system to an empty location in the computer memory. Commonly, the null pointer is used to denote the end of a memory search or processing event. In computer programming, a null pointer is a pointer that does not point to any object or function.
A nil pointer is a false value. For example, 1 > 2 is a nil statement.
In the programming language C, NULL is an available command that can be used, where nil is an available command used in the Pascal programming language.

 

3.What are the 4 basics of OOP?  
 Abstraction, Inheritance, Encapsulation, and Polymorphism.

 

4.What you mean by Object Relational DBMS?

An object-relational database (ORD), or object-relational database management system (ORDBMS), is a database management system (DBMS) similar to a relational database, but with an object-oriented database model: objects, classes and inheritance are directly supported in database schemas and in the query language. In addition, just as with proper relational systems, it supports extension of the data model with custom data-types and methods.

 

5.Structural difference between bitmap and b-tree index ? 

Btree
It is made of branch nodes and leaf nodes. Branch nodes holds prefix key value along with the link to the leaf node. The leaf node in turn contains the indexed value and rowed.
Bitmap
It simply consists of bits for every single distinct value. It uses a string of bits to quickly locate rows in a table. Used to index low cardinality columns. 

 

6.what is database Schema?
The formal definition of database schema is a set of formulas (sentences) called integrity constraints imposed on a database.
 

7.what are the different levels of database schema?
Conceptual schema- a map of concepts and their relationships.
Logical schema- a map of entities and their attributes and relations
Physical schema- a particular implementation of a logical schema
Schema object- Oracle database object

 

8.what is difference between foreign key and reference key ?  
  Reference Key is the primary key that is referenced in the other table (linked via the other tables Foreign Key). Foreign Key is how you link the second table to the primary tables Primary Key (or Reference Key).

 

9.Tell me about DSN?
A Data Source Name (DSN) is the logical name that is used by Open Database Connectivity (ODBC) to refer to the drive and other information that is required to access data. The name is used by Internet Information Services (IIS) for a connection to an ODBC data source, such as a Microsoft SQL Server database. 

 

10.ifference between Clustered index and non clustered index ?   

Clustered Index
Only one per table
Faster to read than non clustered as data is physically stored in index order
Non Clustered Index
Can be used many times per table
Quicker for insert and update operations than a clustered index

 

11.What is WPF and WCF?

WPF/WCF application, need in .NET 3.0 Framework. This application will cover the following concepts:
WCF(Windows Communication Foundation)
The new service orientated attributes
The use of interfaces
The use of callbacks
Asynchronous delegates
Creating the proxy
WPF( Windows Presentation Foundation )
Styles
Templates
Animations
Databinding
Multithreading a WPF application
 

12.What is the difference between an EXE and a DLL?   

The term EXE is a shortened version of the word executable as it identifies the file as a program. On the other hand, DLL stands for Dynamic Link Library, which commonly contains functions and procedures that can be used by other programs.
10.Scenarios in which web application should be used and desktop application should be used?
 

13.Tell how to check whether a linked list is circular.

Create two pointers, each set to the start of the list. Update each as follows:
while (pointer1) {
pointer1 = pointer1->next;
pointer2 = pointer2->next; if (pointer2) pointer2=pointer2->next;
if (pointer1 == pointer2) {
print ("circular\n");
}
}

 

14.How can u increase the heap size in the memory?

If heap size set too low then you will get "out of memory" errors. If you set it too high then your system will hang or you will suffer poor performance because parts of the jvm will be swapped in and out of memory. A rule of thumb is that you should not set this parameter larger than about 80% of your free physical memory. On Windows XP machines you can determine your free physical memory from the Performance tab of the Task Manager application. 

Boosting the heap size parameter will allow you to read in larger file-based projects. It will also improve the performance of the database back-end since more memory is available for caching.In Java Set the maximum heap size, using the -Xmx command-line option, to a value that allows the application to run with 70% occupancy of the Java heap.The Java heap occupancy often varies over time as the load applied to the application varies. For applications where occupancy varies, set the maximum Java heap size so that there is 70% occupancy at the highest point, and set the minimum heap size, using the -Xms command line option, so that the Java heap is 40% occupied at its lowest memory usage. If these values are set, the Java memory management algortihms can modify the heap size over time according to the application load, while maintaining usage in the optimal area of between 40% and 70% occupancy.

 

15.Why is it difficult to store linked list in an array?

Both Arrays and Linked List can be used to store linear data of similar types.

Linked list provide dynamic size while the size of array is fixed, So we must know the upper limit on the number of elements in advance.
Linked lists have following drawbacks:
1) Random access is not allowed. We have to access elements sequentially starting from the first node. So we cannot do binary search with linked lists.
2) Extra memory space for a pointer is required with each element of the list.
3) Arrays have better cache locality that can make a pretty big difference in performance.

 

16.Different types of keys in SQL?

The different types of Keys in sql server are,
 

A candidate key acts as a unique key. A unique key can be a Primary key. A candidate key can be a single column or combination of columns. Multiple candidate keys are allowed in a table.
 

Primary Key

To uniquely identify a row, Primary key is used.
A table allows only one Primary key
A Primary key can be a single column or combination of columns.
 

Foreign Key

A foreign key in a table is a key which refer another tables primary key . A primary key can be referred by multiple foreign keys from other tables. It is not required for a primary key to be the reference of any foreign keys. The interesting part is that a foreign key can refer back to the same table but to a different column. This kind of foreign key is known as self-referencing foreign key.
 

17.Explain about Joins, Views, Normalization, Triggers?

The JOIN keyword is used in an SQL statement to query data from two or more tables, based on a relationship between certain columns in these tables.
Tables in a database are often related to each other with keys.

A view is a virtual table.A view contains rows and columns, just like a real table. The fields in a view are fields from one or more real tables in the database.
You can add SQL functions, WHERE, and JOIN statements to a view and present the data as if the data were coming from one single table.

 

Normalization is the process of efficiently organizing data in a database. There are two goals of the normalization process: eliminating redundant data (for example, storing the same data in more than one table) and ensuring data dependencies make sense (only storing related data in a table). Both of these are worthy goals as they reduce the amount of space a database consumes and ensure that data is logically stored. 
 

First Normal Form (1NF)

sets the very basic rules for an organized database:
Eliminate duplicative columns from the same table.
Create separate tables for each group of related data and identify each row with a unique column or set of columns (the primary key).
 

Second Normal Form (2NF)

further addresses the concept of removing duplicative data:
Meet all the requirements of the first normal form.
Remove subsets of data that apply to multiple rows of a table and place them in separate tables.
Create relationships between these new tables and their predecessors through the use of foreign keys.
 

Third Normal Form (3NF)

Meet all the requirements of the second normal form.
Remove columns that are not dependent upon the primary key.
 

Boyce-Codd Normal Form (BCNF or 3.5NF)

It also referred to as the "third and half (3.5) normal form", adds one more requirement:
Meet all the requirements of the third normal form.
Every determinant must be a candidate key.
 

Fourth Normal Form (4NF)

Meet all the requirements of the third normal form.
A relation is in 4NF if it has no multi-valued dependencies.
Remember, these normalization guidelines are cumulative. For a database to be in 2NF, it must first fulfill all the criteria of a 1NF database.
In a DBMS, a trigger is a SQL procedure that initiates an action (i.e., fires an action) when an event (INSERT, DELETE or UPDATE) occurs. Since triggers are event-driven specialized procedures, they are stored in and managed by the DBMS. A trigger cannot be called or executed; the DBMS automatically fires the trigger as a result of a data modification to the associated table. Triggers are used to maintain the referential integrity of data by changing the data in a systematic fashion. Each trigger is attached to a single, specified table in the database. 
 

18.what is the difference between socket and session?

The Socket is a Combination of Ip address and Port Number (in pairs)
Session is a Logical Connectivity between the source and destination 
 

19.What is a default gateway?

In organizational systems a gateway is a node that routes the traffic from a workstation to another network segment. The default gateway commonly connects the internal networks and the outside network (Internet). In such a situation, the gateway node could also act as a proxy server and a firewall. The gateway is also associated with both a router, which uses headers and forwarding tables to determine where packets are sent, and a switch, which provides the actual path for the packet in and out of the gateway.
 

20.Given an array of 1s and 0s arrange the 1s together and 0s together in a single scan of the array. Optimize the boundary conditions.

void main()
{
int A[10]={'0','1','0','1','0','0','0','1','0','1','0','0'};
int x=0,y=A.length-1;
while(x if(!A[x])
x++;
else if(A[y])
y--;
if(A[x] && !A[y])//here we are checking that stating index is having 1 and last index having 0 than swap values

A[x]=0,A[y]=1;
}
getch() 
}
 

21.Define Data Abstraction. What is its importance?

Abstraction is the process of recognizing and focusing on important characteristics of a situation or object and leaving/filtering out the un-wanted characteristics of that situation or object.
Abstraction is the basis for software development. Its through abstraction we define the essential aspects of a system. The process of identifying the abstractions for a given system is called as Modeling (or object modeling).
Three levels of data abstraction are:
1. Physical level : how the data is stored physically and where it is stored in database.
2. Logical level : what information or data is stored in the database. eg: Database administrator
3.View level : end users work on view level. if any amendment is made it can be saved by other name.

 

22.Write a program to swap two numbers without using a temporary variable.

void swap(int &i, int &j)
{
i=i+j;
j=i-j;
i=i-j;
}

 

23.Memory Allocation in C/C++

calloc() allocates a memory area, the length will be the product of its parameters(it has two parameters). calloc fills the memory with ZERO's and returns a pointer to first byte. If it fails to locate enough space it returns a NULL pointer.
malloc() allocates a memory area, length will be value entered as parameter.(it has one parameter). It does not initializes memory area
free() used to free the allocated memory(allocated through calloc and malloc), in other words, this used release the allocated memory
new also used to allocate memory on heap and initialize the memory using constructor
delete also used release memory allocated by new operator

 

24.Write output of the program?

int i=10; 
printf("%d%d%d",i,++i,i++);
Answer = 10 12 12

 

25.what is virtual function and pure virtual function?

Virtual function:-To achieve polymorphism, function in base class is declared as virtual , By declare virtual we make base class pointer to execute function of any derived class depends on content of pointer (any derived class address).
Pure Virtual Function :-This is function used in base class, and its defination has to be provide in derived class, In other pure virtual function has not defination in base it defined as :
virtual void fun()=0;
This means that this function not going to do anything, In case of pure virtual funtion derived function has to 
implement pure virtual function or redeclare it as pure virtual function

## [](#header-2)Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### [](#header-3)Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### [](#header-4)Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### [](#header-5)Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### [](#header-6)Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
