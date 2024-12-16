java c

Module code and Title 
Database Development and Design (DTS207TC) 
School Title 
School of AI and Advanced Computing 
Assignment Title 
001: Assessment Task 1 (CW) 
Submission Deadline 
23:59, 15th Dec (Friday) 
Final Word Count 
NA 
Database Development and Design (DTS207TC) 
Assessment 001: Individual Coursework
Due: Dec   15th, 2024   @   23:59 Weight: 60%
Maximum Marks: 100
Overview  Outcomes 
This course work will be assessed for the following learning outcomes:
A. Identify and apply the principles underpinning transaction   management within   DBMS.
B. Demonstrate an understanding of advanced   SQL topics.
E. State the main concepts in data   warehousing   and   data   mining.
Submission 
You must submit the following files to   LMO:   1)A report named as Your_Student_ID.pdf.
2)A directory containing all your source code, named as Your_Student_ID_code.NOTE: The report shall be in A4 size,   size   11 font,   and   shall   not   exceed 8 pages   in   length. You   can include only key code snippets in your   reports. The   complete   source   code   can   be   placed   in   the attachment.
Assessment Tasks 
Matrix multiplication is a fundamental operation in   linear algebra where   two   matrices   are multiplied to produce a new matrix. Specifically,   if we   have two   matrices A   and   B, the   product      of these matrices, denoted as AB, is calculated by taking the   dot   product   of the   rows of A with   the columns of B. For example, for two matrices   of dimension   2x2, their   matrix   multiplication formula   is 

To test your proficiency in SQL under an open-book   setting,   this   assignment   requires   you to   implement matrix multiplication using SQL. It   is   divided   into the following   steps:
1)       The Python function in the attachment   is capable   of generating   an   N-dimensional   square
matrix composed of random numbers in the format of (row_id,   col_id,   value).   First,   use   a   Python program to invoke this function and generate such a   matrix, then   import   it   into   a table M in PostgreSQL. Additionally, discuss the impact   of database transaction   mechanisms   on the performance of record insertion. Record the   program   running   time   (ideally,   <10s) when   N=500 and take a scr代 写Database Development and Design (DTS207TC)Python
代做程序编程语言eenshot. (20   marks)
2)       Perform. a “pivot” operation on the table M from   1)   (write the   PL/pgSQL   manually   without   using crosstab) to generate a data table A. You can design your own schema for table A,      but ensure that each   row of the matrix is placed   in   a   separate   record.   Note that   N   cannot   be predetermined in the program. Provide   a screenshot   of the computation   results   when      N=3 and perform. a correctness check.   Provide another screenshot of the   running time (ideally,   <1s) when N=500. (20 marks)
3)       Using PL/pgSQL, perform   a   matrix transposition   on   table A from   2)   and   store   the   results   in   another table with the same schema as A. Provide a screenshot of the computation   results   when   N=3 and perform. a correctness check.   Provide another screenshot of the   running time (ideally,   <1s) when N=500. (20 marks)
4)       Using PL/pgSQL, calculate the   matrix   multiplication of the   matrix stored   in table A from   2)   with itself, and store the results in   another   table with   the   same   schema   as A.   Provide   a screenshot of the computation results when   N=3 and perform. a correctness   check.   Provide   another screenshot of the running time (ideally,   <1 min) when N=500. (20 marks) 
5)       For the above tasks   1-4, check the program's   running   time   when   N=1700.   Provide
corresponding screenshots. The ideal running times should not   exceed:   2   minutes for   task   1,   10 seconds for task 2,   10 seconds for task 3, and 30   minutes   for   task 4.   (20   marks)
NOTE:
a.          Provide a brief introduction to the   program   logic   in your own words;   including   code snippets is encouraged, but please do   not directly   paste the   entire   program   into   the   report   without explanation; b.       For your full academic development, the   use of generative AI to gain   inspiration   is   allowed      for this assignment; however, out of mutual respect,   please do   not   directly   paste   its   output   into   your assignment and submit   it;
c.       To prove that you have indeed completed this assignment   and   did   not   rely   solely   on   generative AI, please provide screenshots of the running   results for each   task.


         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
