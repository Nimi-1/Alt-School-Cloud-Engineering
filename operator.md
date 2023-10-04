 Different operators in Linux and their Uses
 In Linux Operating system, we have several operators that used to carry out different operations.
 Having a good understanding of file operators in Llinux help to harness the full potentials of the linux systems, streamline workflows and will also help users perform their tasks effectively and efficiently.
 Linux operators are categorized into five different categorizes, namely,
 1. Arithmetic Operators: allows you to perform basic operations in linux, e.g. - , +, *, /, and %
 2. Relational Operators: are commonly used in conditional statements, such as if-else constructs and while loops to compare values and make decisions based on comparison results, e.g. ==, !=, >, <, >=, and <=
 3. Boolean Operators: Boolean operators are commonly used in conditional statements, command chaining, and control flow structures within Linux scripts and commands, e.g. &&, ||, and !
 4. Bitwise Operators: Bitwise operators in Linux are used to perform bitwise operations on binary representations of integers, e.g. AND, OR, XOR, NOT, e.t.c.
 5. File Test Operators: In Linux, file test operators are used to perform various tests on files or directories. These operators are typically used in shell scripting to check the properties or attributes of a file before performing certain actions or making decisions based on the test results, e.g. -e, -f, -d, -w , -r, -s e.t.c.

 Below are examples of file operators and their uses:
 (a) -e: checks if the file exists, e.g. [-e file.txt]
 (b) -f: checks if the file is a regular file e.g. [-f file.txt]
 (c) -d: checks if the file is a directory e.g. [-d toluwanimi]
 (d) -s: checks if the file has a non-zero size e.g. [-s file.txt]
 (e) -w: checks if a file is writable e.g. [-w file.txt]
 (f) -r: checks if a file is readable e.g. [-r file.txt]
 (g) Logical AND (&&): allows you to perform operations based on multiple conditions, and the subsequent command is executed if all conditions are true e.g. mkdir directory && cd directory.
 (h) Logical OR (||): allows you to perform operations based on multiple conditions, and the subsequent command is executed if at least one condition is true e.g. grep "tolu" file.txt || echo "tolu not found"
 (i)Logical NOT (!): negates the result of a condition or expression. It returns true if the condition is false and false if the condition is true e.g. !rm file.txt
 (j) Equal to (==): checks if two values are equal. This operator compares two values and returns true if they are equal; otherwise, it returns false e.g. 
 [ 5 == 5 ]   # true
[ "hello" == "world" ]   # false
 (l) Not equal to (!=): checks if two values are not equal. This operator compares two values and returns true if they are not equal; otherwise, it returns false e.g. 
 [ 5 != 3 ]   # true
[ "hello" != "hello" ]   # false
 (m) Greater than (>): checks if one value is greater than another. This operator compares two values and returns true if the first value is greater than the second; otherwise, it returns false e.g. 
 [ 5 > 3 ]   # true
[ 2 > 10 ]   # false
 (n) +: adds two value together e.g. 5+3, result = 8
 (l) *: multiplies two values together e.g. 6*2, result = 12
 (o) %: computes the remainder of a division e.g. 10%3,result = 1

 Gaining proficiency in the basic Unix/Linux operators empowers users to efficiently interact with their operating systems, leverage the command line's power, and become more effective in system administration, programming, and everyday usage.