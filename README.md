# interview-prep

06-12-2025
==========
*Java and Programming Concepts*

1. Java 8 features
2. Functional interface basics
3. Why not only static methods in functional interface
4. Exception handling concepts
5. Method throws IOException without IO – why?
6. Ways to handle exceptions
7. Access modifiers – overriding protected → private
8. Can return type be changed in overriding?
9. What is abstraction?
10. Collections overview
11. ArrayList vs LinkedList
12. When to use ArrayList vs LinkedList
13. Internal working of HashMap

*Database and SQL*

14. Full outer join explanation
15. Table A(3 rows) + B(5 rows), single match
16. Cross join explanation

*Design Patterns and Principles*

17. SOLID principles
18. Singleton pattern
19. Factory pattern
20. Types of design patterns
21. Dependency Injection
22. Autowiring

*Spring and Framework*

23. How @Transactional works across microservices
24. Circuit breaker – simple controller example
25. @Autowired inside same class
26. Is Singleton thread-safe?
27. How to make Singleton thread-safe
28. Prototype scope drawbacks
29. Advantages of Spring framework

*Testing and Code Quality*

30. JUnit basic concepts
31. Mockito behaviour

*Problem-Solving and Code Challenges*

32. Count occurrences of words in a string (Java code)
33. Find duplicate in ArrayList (1–10,000)
34. More efficient duplicate finding
35. Output of given code (image)
36. System.out.print output question (image)
37. UPI payment failure scenario – debited but server issue







================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================
================================================

================================================

Hint variable - db - parrelel - master slave 

Park / Unpark virtual thread —- thread pool

Context switching- 1 java thread map to 1 os thread

Redis - distributed cache - only ram

Ehcache - rom + ram

@Async









difference between inheritance and composition with example

Inheritance- has-a - tightly coupled- extends

Composition- is-a - loosely coupled- object reference to another class

















=================================

[11/07/23, 9:22:18 PM] Prathmesh Gaikwad: Hi Please find below questions(Duration:90min)

EPAM:

1) Explain your technical skills, roles and responsibilities, and project.

2) difference between inheritance and composition with example

3) What is hibernate transaction and what is transaction propagation

4) What are Transaction Isolations

5) Which interface is handy for sorting and pagination?

6) Tell the full form of SOLID

7) How will you create one to many relationship

8) Eager vs Lazy

9) What are the types of join and explain left join

10) What is dependency injection

11) Difference between component and service

12) What is a functional interface

13) share your screen and create a functional interface and provide its implementation

14) You will have a list of products (with name and price properties) calculate the sum of all the products having 'PRIME' name

15) He shared his screen and asked some questions based on inheritance, I had to tell the output

16) How to create an immutable class and how to break immutability?

17) can you hold an instance of an immutable class in an abstract method

18) What authentication do you know and how does it work?

19) When does spring perform dependency injection at the time of compilation, runtime, deployment?

20) Any exposure to JUnit?



The interviewer was very friendly.



[11/07/23, 9:22:18 PM] Prathmesh Gaikwad: 1.ITIVITI

1.volatile keywords ? What is thread safety ?

2.final keywords

3.multi threading related to questions

4.message read from MQ

5.How success and failure returns in MQ



2.BOA

1. WHAT is features of JAVA 8

2.What internal workings of Vector

3.Arraylist vs Vector

4. What is Hashset 

5.concurrent hashmap ?

6.CopyonWrite Array list ?

7. What is Serialisation and deserialization  ? Not want to serialise any variable ?

8. Things taken care while storing object as Key in hashmap



3.Altres technologies

1.When to use comparable or comparator

2.how should we convert arraylist to array and vice versa

3.count occurrence of character in string?Is we need to implement hashcode or equals method ?

4.design pattern ? use case for singleton design patterns ?

5. Servlet vs jsp ?



4.BOA

1.equals and hashcode ?

2.overriding access modifiers and exception ?

3.What is returns type fixed thread pool

4.reading 4gb and write to database

5. Method overriding and access specifiers, exeption







5.Accolite Morgan Stanley

1. Abstract vs interface interms of java 8?

2. Why string is immutable class in java 

3. Character array vs string  which is better

4.Program questions



Round:

1.Try with resources bloock?

2.Sub arrary who have highest sum

3.largest palindrom



6.Nomura

1.way to implement threads ? What is benifit implement on each other ?

2.arraylist vs linkedlist which one will used

3. Is concurrent modification occurrs in arraylist

4. Things needs to take if we use object as Key

5.intial size of hashmap

6. Design patterns in java?  Singleton ? What will be passed in  synchronised ?

7. JVM memory management

8. Generics benefits

9.java parameters pass

10.linux command to rename

11.linux command to change file permissions





7.Synechron Morgan Stanley



1.what is clauses in SQL?

2.how to return from run()?What callable?

3.What is singleton ?in multi-threading ?

4.even odd thread print thread print number order like 1,2,4,5.....?

5.What is clauses in oracle?

6.What is copyonwriteArraylist?

7.String is palindrom with best best case?

8. is test variable and testing() accessible in Class C?

pkg 1{

Class A{

protected int test

protected int testing()

}



pkg2

{

class B extends class A

{



}

class C extends class B

{



}

}



9.Arralist vs linkedlist ? internal implemnetaion of both?

10.What are protected method of Object class?why clonable methods of object is protected ?is it for client

11.What is locks in multi-threading?What is retrant lock?

12.what are design patterns java you know



8.BOA

1.second highest salary

2.garabage collection algorithm

3.design patterns ? singleton design patterns in multi threading

4.java 8 remove duplicate from arraylist

5.what stack.and heap memory

6.What's is volatile and transient variable ?

7.blocking queue

8. What is SOLID principles

9.find second largest number in array

10.binary tree



9.Genpact

1.merged two array in sorted manner ?

2.oops concept with examples

3.method overriding

4.threashold in hashmap

5.fail safe vs fail fast

6.internal working of treemap

7. Race conditions in hashmap

8. Volatiles keywords

9 design patterns

10. Executor framework ?





10.BOA

1.euqals and hashcode internally works?  Why we need custom equals method if it is present object level ? What efficient hashcode implementation ?

2.one producer and 2 consumer one write to file and one write to DB without blocking queue

3.why wait(),notify() are object level of we using at thread class

4.collection hierarchy ?

5.Can we make arryalist final ?

4.best collection for multiplethreding environment ?





11.Morgan Stanley

1.How values strored in hashmap ?

2.What is atomic integer ?

3. How thread implement in your project

4.lamda expression 

5. Program for below no character should be repeated more than two consecutively

String s="aaaabccbddac" 

o/p:"aabbccdacdaa" 

6.how java gc work? Can we called it explici tly ?

10.java code to implement own STACK 





12.JPMC(J P Morgan Chase)

1.Oops concept ? abstraction vs encapsulation

2.string vs new String ()

3.stringbuffer vs stringbuilder

4.hashmap vs hashtable ? Concurrent collection ? Listinterator

5.markertinterface 

6 Transient ?

7.Types of SQL statements

8. PRIMARY KEY Vs Unique key

9. Type of index

10. Executor framework

11. Substring leak issue

12.sleep vs wait

13.difference between date and SQL date object ? Why we can not use normal date in SQL date

14 what is cursor in SQL

15. What is constrainent is SQL



13.J P Morgan

1. Reverse number

2. Interface vs abstract when to use ?

3. Write linkedlist ?

4. Synchronisation in Java ?

5. GC implementation in Java ?

6. If one thred in thredpool crash what happened with other thread in pool ?



[11/07/23, 9:22:18 PM] Prathmesh Gaikwad: Tricky SQL Queries



SQL Queries



delete record who have same name and salary



delete rowid from emp where

rowid not in (select max(rowid) from emp

group by ename,sal);



department count more than average employees department count



select DEPTNO,count(DEPTNO) as empcount fromEMP group by DEPTNO having count(DEPTNO) >(select avg(count(deptno)) from emp group bydeptno);





    List all employees who has manager



select distinct e.Ename as Employee, m.mgr as reports_to, m.Ename as Manager

from EMPLOYEES e

inner join Employees m on e.mgr = m.EmpID;



    Find the 3rd MAX salary in the emp table.



select distinct sal from emp e1 where 3 = (select count(distinct sal) from emp e2 where e1.sal <= e2.sal); 



alternate solution:

select rownum as rank, empno, sal from (select empno, salary from emp where sal is not null order by sal desc) where rownum<=3





    Find the 3rd MIN salary in the emp table.



select distinct sal from emp e1 where 3 = (select count(distinct sal) from emp e2where e1.sal >= e2.sal);



select rownum as rank, empno, sal from (select empno, sal from emp where sal is not null order by sal) where rownum<=3



    Select FIRST n records from a table.



select * from emp where rownum <= &n; 



    Select LAST n records from a table



select * from emp minus select * from emp where rownum <= (select count(*) - &n from emp); 



    List dept no., Dept name for all the departments in which there are no employees in the department.



select * from dept where deptno not in (select deptno from emp);



alternate solution:  select * from dept a where not exists (select * from emp b where a.deptno = b.deptno);



altertnate solution:  select empno,ename,b.deptno,dname from emp a, dept b where a.deptno(+) = b.deptno and empno is null; 



    How to get 3 Max salaries ?



select distinct sal from emp a where 3 >= (select count(distinct sal) from emp b where a.sal <= b.sal) order by a.sal desc; 



    How to get 3 Min salaries ?



select distinct sal from emp a  where 3 >= (select count(distinct sal) from emp b  where a.sal >= b.sal);



    How to get nth max salaries ?



select distinct hiredate from emp a where &n =  (select count(distinct sal) from emp b where a.sal <= b.sal);



    Select DISTINCT RECORDS from emp table.



select * from emp a where  rowid = (select max(rowid) from emp b where  a.empno=b.empno); 



    How to delete duplicate rows in a table?



delete from emp a where rowid != (select max(rowid) from emp b where  a.empno=b.empno); 



    Count of number of employees in  department  wise.



select count(EMPNO), b.deptno, dname from emp a, dept b  where a.deptno(+)=b.deptno  group by b.deptno,dname; 



    Suppose there is annual salary information provided by emp table. How to fetch monthly salary of each and every employee?



select ename,sal/12 as monthlysal from emp;



    Select all record from emp table where deptno =10 or 40.



select * from emp where deptno=30 or deptno=10;



    Select all record from emp table where deptno=30 and sal>1500.



select * from emp where deptno=30 and sal>1500;



    Select  all record  from emp where job not in SALESMAN  or CLERK.



select * from emp where job not in ('SALESMAN','CLERK');



    Select all record from emp where ename in 'BLAKE','SCOTT','KING'and'FORD'.



select * from emp where ename in('JONES','BLAKE','SCOTT','KING','FORD');



    Select all records where ename starts with �S� and its lenth is 6 char.



select * from emp where ename like'S_';



    Select all records where ename may be any no of  character but it should end with �R�.



select * from emp where ename like'%R';



    Count  MGR and their salary in emp table.



select count(MGR),count(sal) from emp;



    In emp table add comm+sal as total sal  .



select ename,(sal+nvl(comm,0)) as totalsal from emp;



    Select  any salary <3000 from emp table. 



select * from emp  where sal> any(select sal from emp where sal<3000);



    Select  all salary <3000 from emp table. 



select * from emp  where sal> all(select sal from emp where sal<3000);



    Select all the employee  group by deptno and sal in descending order.



select ename,deptno,sal from emp order by deptno,sal desc;



    How can I create an empty table emp1 with same structure as emp?



Create table emp1 as select * from emp where 1=2;



    How to retrive record where sal between 1000 to 2000?



Select * from emp where sal>=1000 And  sal<2000



    Select all records where dept no of both emp and dept table matches.



select * from emp where exists(select * from dept where emp.deptno=dept.deptno)



    If there are two tables emp1 and emp2, and both have common record. How can I fetch all the recods but common records only once?



(Select * from emp) Union (Select * from emp1)



    How to fetch only common records from two tables emp and emp1?



(Select * from emp) Intersect (Select * from emp1)



    How can I retrive all records of emp1 those should not present in emp2?



(Select * from emp) Minus (Select * from emp1)



    Count the totalsa  deptno wise where more than 2 employees exist.



SELECT  deptno, sum(sal) As totalsal

FROM emp GROUP BY deptno HAVING COUNT(empno) > 2







3 table join

mysql> SELECT emp_name, dept_name FROM Employee e JOIN Register r ON e.emp_id=r.emp_id JOIN Department d ON r.dept_id=d.dept_id;



[11/07/23, 9:22:18 PM] Prathmesh Gaikwad: 1.Genpact (telephonic)

1.10 java api(collection, multi-threading/classes use in you project

2.what is change management ?

3. How release has been manage ?

4.code management ?how  manange not to overwrite in cvs

2. L & T (telephonic)

1.get access data from database using thread in concurrent manner

2. How to set priorities in two task ?--- PriorityQueue

3.how to set priorities in thread ?

4.how you handle outofmemmory error ? Weather we handle outofmemmory error or not ?

5. Best way read large files ?

6.When use bufferreader what happened internally ?is buffer reader store internally store anything to cap memory/cache.

7. What is scanner ? Difference between buffer reader and scanner ? When use bufferreader or when use scanner ?

8. Java Nio ?

9. Jdk 1.8 features ? 

10. What you understand abstract or interface ? Can we create Constructor in abstract class or interface ?

11. What is Polymerphism ?  WHAT IS Overloading or Overriding ?

12. Hibernate,JPA and Spring

13. What is high level design or low level design ?what is key factors while preparing designing like logging,scalability ?

14.what you advice while designing your application for  performance in database access? What type of designing pattern use in this case ?

15. Rest API ? What framework use? What library use like Rest Api ,Spring MVP , JERSEY 

16 What type Soap web services use ? ---- AXIS 2

17. Ever use Database Join ? Any experience store procedure ? How to call store procedure from java

18 Linux ? tomcat with NO HOP Command  ? Unix Command to print websphere process ID ?

19 how to KILL PID in Linux ?---- Kill -9 PID

20.how to read core dump ?

3.TIAA

1.how NLP Implemented in your company

2.NLP algorithm ?

3.NLP working in KB? How AI is implemented

4. Synechron for UBS

1. What is OOPS principles ? What's is abstractions ? If  interfaces in java 8 is similar to abstract class then why it is required ?

2. Composition and Aggregation

3.what is indexing in SQL ? types of index ?

4.what is difference between concurrentHashMap and hashMap ? What is LINKEDHASHMAP ?

4. Return in try and return in finally what value shoud return

? What happened if exception in finally ?

5. Design patterns in java ? What is singleton design pattern ? Where singleton pattern used ?

6. How to create custom exception ?

7.What is the difference between ClassNotFoundException and NoClassDefFoundError?

8. Difference between synchronised and lock

9. What is difference between notify ()and  notifyall() ? If notifyall() then why required notify() ? 

10. What is read write lock in java ?.

11. What is Retrancelock() ?

12 what I producer and consumer model ? What is blocking queue

13. What is countdownlatch ? What is cycallibarrier ?

14. What is java 7 features ?

15. What is SOLID principles

5. Jio

1.oops principles

2.what is polymerphism

3.below polymerphism related program

Class mathoperation

Int Add(int a,int b)

Return a

Float Add(int a,int b)

Return 

Main(){

Add(5,10)

}

5.arraylist vs set ?

6.o/p below program

Arraylist a

A.add(1)

A.add(2)

A.remov(1)

A.add(4)

7.o/p below program

Set a

A.add(1)

A.add(2)

A.remov(1)

A.add(4)

8.exception related program

Main()

Try {

}Catch(exception e){}

Catch(Numberformat nme){}

9.which class have wait(), notify(), notifyall()

10.can we store emp object in hashcode as key?can we store unique emp object ? What is format of hashcode?

10.remove duplicate from arrays list?

11.know any design pattern ? singleton design patterns ?

12.know anything about string 

13.string a vs String a= new String a()

14.Stringbuffer vs String builder

15. What is deployment architecture ?

16. What is performance ?

17. What hardware used ?dell , RAC ,LINUX ? How many cores

18. HOW thread implemented in ur servers ? Threapool









Your order #58461 has been accepted. Verify the details of the rider before handing over the parcel. If there are any discrepancies, kindly contact us through chat support.





Address :- *HItesh Thakkar*

Safe Zone, Office No. 412, 4th Floor, Sai Dham, Above Barista, Nr. Vikrant Circle, Road, Ghatkopar East, Mumbai – 400077





    1.Genpact (telephonic)

    1.10 java api(collection, multi-threading/classes use in you project

    2.what is change management ?

    3. How release has been manage ?

    4.code management ?how  manange not to overwrite in cvs

    2. L & T (telephonic)

1.get access data from database using thread in concurrent manner

2. How to set priorities in two task ?--- PriorityQueue

3.how to set priorities in thread ?

4.how you handle outofmemmory error ? Weather we handle outofmemmory error or not ?

5. Best way read large files ?

6.When use bufferreader what happened internally ?is buffer reader store internally store anything to cap memory/cache.

7. What is scanner ? Difference between buffer reader and scanner ? When use bufferreader or when use scanner ?

8. Java Nio ?

9. Jdk 1.8 features ? 

10. What you understand abstract or interface ? Can we create Constructor in abstract class or interface ?

11. What is Polymerphism ?  WHAT IS Overloading or Overriding ?

12. Hibernate,JPA and Spring

13. What is high level design or low level design ?what is key factors while preparing designing like logging,scalability ?

14.what you advice while designing your application for  performance in database access? What type of designing pattern use in this case ?

15. Rest API ? What framework use? What library use like Rest Api ,Spring MVP , JERSEY 

16 What type Soap web services use ? ---- AXIS 2

17. Ever use Database Join ? Any experience store procedure ? How to call store procedure from java

18 Linux ? tomcat with NO HOP Command  ? Unix Command to print websphere process ID ?

19 how to KILL PID in Linux ?---- Kill -9 PID

20.how to read core dump ?

3.TIAA

1.how NLP Implemented in your company

2.NLP algorithm ?

3.NLP working in KB? How AI is implemented

4. Synechron for UBS

1. What is OOPS principles ? What's is abstractions ? If  interfaces in java 8 is similar to abstract class then why it is required ?

2. Composition and Aggregation

3.what is indexing in SQL ? types of index ?

4.what is difference between concurrentHashMap and hashMap ? What is LINKEDHASHMAP ?

4. Return in try and return in finally what value shoud return

? What happened if exception in finally ?

5. Design patterns in java ? What is singleton design pattern ? Where singleton pattern used ?

6. How to create custom exception ?

7.What is the difference between ClassNotFoundException and NoClassDefFoundError?

8. Difference between synchronised and lock

9. What is difference between notify ()and  notifyall() ? If notifyall() then why required notify() ? 

10. What is read write lock in java ?.

11. What is Retrancelock() ?

12 what I producer and consumer model ? What is blocking queue

13. What is countdownlatch ? What is cycallibarrier ?

14. What is java 7 features ?

15. What is SOLID principles

5. Jio

1.oops principles

2.what is polymerphism

3.below polymerphism related program

Class mathoperation

Int Add(int a,int b)

Return a

Float Add(int a,int b)

Return 

Main(){

Add(5,10)

}

5.arraylist vs set ?

6.o/p below program

Arraylist a

A.add(1)

A.add(2)

A.remov(1)

A.add(4)

7.o/p below program

Set a

A.add(1)

A.add(2)

A.remov(1)

A.add(4)

8.exception related program

Main()

Try {

}Catch(exception e){}

Catch(Numberformat nme){}

9.which class have wait(), notify(), notifyall()

10.can we store emp object in hashcode as key?can we store unique emp object ? What is format of hashcode?

10.remove duplicate from arrays list?

11.know any design pattern ? singleton design patterns ?

12.know anything about string 

13.string a vs String a= new String a()

14.Stringbuffer vs String builder

15. What is deployment architecture ?

16. What is performance ?

17. What hardware used ?dell , RAC ,LINUX ? How many cores

18. HOW thread implemented in ur servers ? Threapool







Spring Boot:
@RestController: combination of @Controller and @ResponseBody

logging.level.root=debug property in application.property

@RestController and @Controller

@EnableAutoConfiguration

types of dependency Injection





Hibernate:

ORM

SQL injection attack - Incorporate Prepared Statements that use Parameterized Queries

Hibernate Inheritance Mapping - Relational databases do not support inheritance - flat structure

Single Table Strategy
Table Per Class Strategy
Mapped Super Class Strategy
Joined Table Strategy
@Immutable / markingmutable=false

hibernate.cfg.xml

Session is not a thread-safe object

SessionFactory provides an instance of Session.

application generally has a single instance of SessionFactory. Internal state of a SessionFactory (includes metadata of ORM) is immutable

Hibernate core interfaces are: Configuration, SessionFactory, Session, Criteria, Query, Transaction

difference between first level cache and second level cache









SQL:

Joins

Functions

Here is a focused list of SQL topics that are especially relevant for a Java developer:

Basic SQL Operations
SELECT, INSERT, UPDATE, DELETE statements
WHERE, ORDER BY, GROUP BY, HAVING clauses
Data types and constraints (PRIMARY KEY, FOREIGN KEY, UNIQUE, NOT NULL, CHECK)
Joins and Relationships
INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN, CROSS JOIN, SELF JOIN
Using JOINs instead of subqueries for performance
Indexes and Performance
Creating and using indexes for query optimization
Analyzing query execution plans
Avoiding SELECT *
Optimizing GROUP BY and ORDER BY
Limiting number of rows returned (LIMIT, FETCH, TOP)
Advanced Querying
Subqueries and nested queries
EXISTS vs. IN
Aggregate functions: COUNT, SUM, AVG, MIN, MAX
CASE statements
Views and Materialized Views
Creating and using views for simplified access and security
Using materialized views for performance
Transactions and Concurrency
ACID properties
COMMIT, ROLLBACK, SAVEPOINT
Isolation levels and locking mechanisms
SQL Functions
Date, string, numeric, and conversion functions
Batch Processing and Connection Pooling
Using batch processing for multiple statements
Implementing connection pooling for efficient resource management
Security and Best Practices
Preventing SQL injection (using PreparedStatement in Java)
Regularly reviewing and refactoring SQL code
Using appropriate data types
Integration with Java
JDBC fundamentals: connections, statements, result sets
Using PreparedStatement and CallableStatement
Error handling and resource management
Other Useful Topics
UNION, UNION ALL, INTERSECT, MINUS
Aliases and subqueries
Data constraints and normalization












latency in networking 

latency = n/w delay + computational delay

Monolithic ---> computational delay

Distributed ---> n/w delay + computational delay

Reduce:

Caching, CDN (proxy servers), h/w upgrade



throughput

volume of work

process flow rate

bps

Reasons: latency. protocol overhead, congestion

Improve: LB, Distibuted system, Caching, CDN 



availability ( replication vs redundancy)

Monolithic --- > SPOF

fault tolerance == availability

Increase: replication, distributed, redundancy



Consistency

diff clients same resp

dirty read --- diff clients diff resp

Increase: n/w b/w, stop the read, replication based on distance aware strategies

Types: Strong, Eventual and Weak Consistency



CAP theorem

2/3 can be achieved - max (ca / cp / ap) ---- ca - not reccommended, centralised



Lamport Logical Clock 











horizontal and vertical scaling

vertical --- h/w inhance - 1 machine - SPOF

horizontal --- new machine / servers





Difference between Redundancy and Replication

Redundancy ——> active and passive

Replication ——> active and passive —> Redundancy + synchronous

Redundancy

Redundancy is simply the duplication of nodes or components so that when a node or component fails, the duplicate node is available to service customers.

Active Redundancy is considered when each unit is operating/active and responding to the action. Multiple nodes are connected to a load balancer, and each unit receives an equal load.

Passive Redundancy is considered when one node is active or operational and the other is not operating. During the breakdown of the active node, the passive node maintains availability by becoming the active node.

every read -write → master

If master goes down one slave becomes master

Master-slave replication can be either synchronous or asynchronous. The difference is simply the timing of propagation of changes. If the changes are made to the master and slave at the same time, it is synchronous. If changes are queued up and written later, it is asynchronous



load balancer 

Virtual ip —> LB —> Nodes (servers)
**Roles of Load Balancer**

   The load distribution is equal over every node.
   Health check lif the node is not operational, the request is passed to another node that is up and running).
  3. Load balancers ensure high scalability, high throughput and high availability

**When to use it and when not to ?**

In monolithic or in case of vertically scaled system we don't need it. But in microservice architecture we need it.

**Challenges of Load Balancing**

Single Point Of Failure - During a load balancer malfunctioning, the communication

between clients and servers would be broken. To solve this issue, we can use redundancy. The system can have an active load balancer and one passive load balancer

**Advantages**

**Load Balancing Algorithms**

   Round Robin (Static) - rotation fashion.
   Weighted Roud robin (Static) - It is similar to the Round Robin when the servers are of different capacities. (some node can have better resoures, others might not have )
   IP Hash Algorithm (Static) - The servers have almost equal capacity, and the hash function ( input is source IP) is used for random or unbiased distribution of requests to the nodes.
   Source IP Hash (Statio) - Source IP Hash combines the server and client's source and destination
IP addresses to produce a hash key. The key can be used to determine the request distribution.

   Least Connection Algorithm (Dynamic) - Client requests are distributed to the application server with the least number of active connections at the time the client request is received.
   Least Response Time (Dynamic) - The request is distributed based on the server which has the least response time.




Caching

Used: read-intensive / static contents

Types:

  Application server cache

  CDN (Content delivery network)







Cache Eviction Techniques ( LRU, LFU, MRU, LIFO, FIFO & RR )

Delete





File based storage system ( File Based Database Management System)

A file-based storage system is a database management system where data is stored in the form of files.

Challenges: Redundancy,  poor-security, slow





Can RDBMS scale horizontally? ( Why is it hard to scale relational database? )

Scaling issue (horizontal) - complex



Types of NoSQL Databases ( Which one to use and where ? )





What is Polyglot Persistence ?

When application need multiple types of DB





What is denormalization in RDBMS

normalization : Putting data in multiple tables to avoid redundancy

denormalization: combines data in single table

Benefits of denormalization

   Faster data read operations
   Management convenience
   High data availability
   Reduces the number of network calls to fetch data from multiple places.


Challenges of Denormalization

Redundant data -> wastage of memory
   It increases the complexity
   Data inconsistency
   It will cause slow write operations since we will need to write multiple places due to redundancy




How does indexing work in Databases ( How to optimize SQL Queries )

Indexing creates a lookup table with the column and the pointer to the memory location of the row, containing this column.

Binary tree

Separate memory - column - memory location - pointer

Read intensive DB only (Not write intensive - why? Insert in actual table as well as sep mem + sorting)



What is Synchronous communication

For consistency / Transaction

Stock, bank. Ticket booking, Real-time





What is synchronous and asynchronous communication

asynchronous: scalability, avoid cascading, less computation time





What is message based communication?

Async - in form of msg

Kafka, rabbitmq





What is web server



What is communication protocol in computer network

These protocols can be implemented using hardware, software, or a combination of both.

Models

   Push
   Pull / Polling /
   Long Polling
   Socket
   Server sent events


REST API | SOA | Microservices architecture | Tier architecture

Website - static

Web app - dynamic

What is required for communication to happen ?

   Language independent
   Fast
   Enable communication over the n/w
   light weighted


Advantages of Service-Oriented Architecture

   Selective scaling
   Different tech stacks
   loose coupling
   Agile
Disadvantages of Service-Oriented Architecture

Higher latency
   Complex to secure
   Cascading failures
Complex understading


A web application can be designed according to the n-tier architecture where tiers are different layers of architecture.

A tier is a logical separation between different components of the application.











Difference between Authentication and Authorization

Who are you? Authentication

VS

What can you do ? - Authorization







Basic Authentication



Token Based Authentication



OAuth Authentication



Forward proxy and reverse proxy Explained



Reverse proxy server

Forward proxy hides the client

Reverse proxy hides the server





URL shortener system design | Tinyurl system design | Bitly system design



Dropbox system design | Google drive system design











  











IWO HashMap





IWO HashSet



No S / P - till switch









https://www.digitalocean.com/community/tutorials/java-programming-interview-questions
https://www.greenstechnologys.com/java-programs-interview-questions-and-answers.html 



Pending: 201, 202, 229, 230











196 Intro to JS and FE

JavaScript History etc. es6 

Objects, OOP

Memories like stack etc.





Cover: 

iNeuron videos, 
notes revision
Resume
Interview questions 1 - Java
Interview questions 2 - Advance Java, Spring Boot, Hibernate etc.
Interview questions 3 - Misc. topics such as Microservices, CI/CD, Docker, MongoDB etc.


Plan:

03
04

05

06

07

-08

09

10

11

12

13

-14

-15



16

17

18

19

20

21

-22



Skills

Agile Methodologies Git JavaScript Spring MVC XML Cascading Style Sheets (CSS) Software Development Tomcat SQL







Core Java Expertise: Arrays, operators, loops, OOP concepts, collections, multithreading, generics, exception handling, serialization, and memory management45.
Frameworks & Libraries: Spring (Boot, MVC, Security, Data JPA, AOP, IOC), Hibernate, JSF, Struts, JSP/Servlets56.
Web Technologies: HTML, CSS, JavaScript, jQuery, AJAX, JSON, XML56.
APIs & Services: RESTful and SOAP web services, microservices architecture56.
Databases: Proficiency in Oracle, MySQL, and experience with NoSQL databases like Cassandra; strong SQL skills, query optimization, and stored procedures56.
Build & Version Control Tools: Maven, Gradle, SVN, Git5.
Application Servers: Tomcat, JBoss5.
Testing: JUnit, Mockito56.
Development Methodologies: Experience with Agile/Scrum and full SDLC participation57.
Cloud & DevOps (if applicable): Exposure to AWS, Azure, CI/CD pipelines, Docker, Jenkins27.






Technical Skills

Programming Languages: Java (Core, SE, EE), SQL
Frameworks: Spring Boot, Hibernate, Spring MVC, JPA
Web Technologies: RESTful APIs, JSP, Servlets, HTML, CSS, JavaScript
Tools & Platforms: Maven, Git, Jenkins, Docker, Tomcat
Databases: Oracle, MySQL, NoSQL (Cassandra)
Testing: JUnit, Mockito
Cloud & DevOps: AWS (basic), CI/CD pipelines




















———







Tech Mahindra

Designed and implemented advanced CRM features for a major banking client using Java, Spring, and RESTful APIs, enhancing customer engagement and operational efficiency.
Led the integration of external services via SOAP and REST, working closely with multidisciplinary teams to ensure robust and reliable system connectivity.
Streamlined the CRM platform by restructuring and merging overlapping modules, adopting a modular approach to boost performance and simplify future maintenance.


Capgemini

Upgraded the FINEOS Absence module for insurance sector client FINEOS, applying Java, Guice, and Spring to address complex leave management requirements.
Maintained high code standards through rigorous unit and integration testing frameworks, leveraging JUnit and Mockito for quality assurance.
Reengineered key components to enhance the module’s scalability and maintainability, aligning with evolving business and technical needs.


Mindgate Solutions

Played a key role in developing the BHIM SBI Pay app for State Bank of India, focusing on secure UPI payment flows and user-centric digital banking experiences.
Engineered features supporting instant payments, bill settlements, and merchant transactions, utilizing Java, Guice, and Spring to ensure reliability and performance in a high-transaction environment.
Collaborated with product and QA teams to optimize app responsiveness and stability, meeting stringent standards for large-scale banking applications.




————




Prathmesh Gaikwad  

Mumbai, Maharashtra, India | (+91) 9870858383 | prathmeshgaikwad@live.com  

LinkedIn: linkedin.com/in/yourprofile | GitHub: github.com/yourusername



--------------------------------------------------------------------------------

Professional Summary

--------------------------------------------------------------------------------

Java Backend Developer with 5 years of experience delivering scalable solutions for banking, insurance, and fintech. Proficient in Java, Spring Boot, RESTful APIs, and microservices, with a focus on performance, security, and robust system integration.



--------------------------------------------------------------------------------

Experience

--------------------------------------------------------------------------------

Mindgate Solutions, Mumbai — Software Developer  

Aug 2023 – Present

• Developed and optimized UPI payment modules for BHIM SBI Pay (SBI) using Java and Spring Boot, enabling secure, high-volume digital transactions.

• Delivered features for instant payments, bill settlements, and merchant transactions.

• Collaborated with cross-functional teams to enhance app responsiveness and stability.



Capgemini, Mumbai — Software Developer  

2022 – 2023

• Enhanced FINEOS Absence module for insurance clients using Java, Guice, and Spring.

• Ensured code quality with unit/integration testing (JUnit, Mockito).

• Refactored components for scalability and seamless integration.



Tech Mahindra, Mumbai — Software Engineer  

2021– 2022

• Designed and implemented advanced CRM features for a banking client using Java, Spring, RESTful APIs.

• Integrated external services via SOAP/REST, ensuring secure interoperability.

• Modularized CRM components to improve performance and maintainability.



--------------------------------------------------------------------------------

Education

--------------------------------------------------------------------------------

B.E., Electronics Engineering, DMCE, University of Mumbai — 2017 

Diploma, Electronics Engineering, Government Polytechnic, Mumbai — 2013



--------------------------------------------------------------------------------

Skills

--------------------------------------------------------------------------------

Languages: Java, C, JavaScript (Working knowledge), SQL  

Frameworks: Spring Boot, Spring MVC, Hibernate, React.js (Basic)  

Web: HTML, CSS, JSP, Servlets (Working knowledge)  

Databases: MySQL, Oracle, MongoDB  

Tools/Platforms: Tomcat, Linux, Eclipse, STS, Maven, Gradle  

Version Control/CI: Git, SVN, Jenkins  

Testing: JUnit, Mockito, Selenium  

Practices: Agile, Scrum, TDD  

APIs: RESTful, SOAP



--------------------------------------------------------------------------------

Key Projects

--------------------------------------------------------------------------------

• UPI Global: Architected global UPI transaction support, enabling QR payments and app-based activation with merchant integration.

• Rupay Credit for UPI: Integrated Rupay credit cards with UPI on Yono, implementing secure payment authorization and settlement logic.

• Foreign Remittance (FIR/FOR): Developed secure backend modules for UPI-based remittances, integrating KYC, OTP, and compliance checks.

• ICCW: Built UPI-based card-less cash withdrawal for SBI ATMs, including QR/NFS integration and security controls.

• UPI Lite: Implemented UPI Lite for high-frequency, low-value transactions, optimizing for scalability and reliability.

• FINEOS Absence Module: Developed modular components for FINEOS AdminSuite, enhancing business logic and supporting CI/CD automation.



--------------------------------------------------------------------------------

















Prathmesh Gaikwad
Mumbai, Maharashtra, India | (+91) 9870858383 | prathmeshgaikwad@live.com
LinkedIn: | GitHub:



Professional Summary
Java Backend Developer with 4 years of experience delivering scalable, high-performance solutions for banking, insurance, and fintech. Skilled in Java, Spring Boot, RESTful APIs, and microservices, with a focus on security, system integration, and agile collaboration.



Experience



Mindgate Solutions, Mumbai — Software Developer
2023 – Present

Developed and optimized UPI payment modules for BHIM SBI Pay (SBI) using Java and Spring Boot, enabling secure, high-volume digital transactions.
Delivered features for instant payments, bill settlements, and merchant transactions; collaborated with cross-functional teams to enhance app responsiveness and compliance.
Capgemini, Mumbai — Software Developer
2022 – 2023

Enhanced FINEOS Absence module for insurance clients using Java, Guice, and Spring, improving leave management workflows and integrating with legacy systems.
Ensured code quality with unit and integration testing (JUnit, Mockito); refactored components for scalability and maintainability.
Tech Mahindra, Mumbai — Software Engineer
2021 – 2022

Designed and implemented advanced CRM features for a banking client using Java, Spring, RESTful APIs.
Integrated external services via SOAP/REST, modularized CRM components, and improved system performance.


Education
B.E., Electronics Engineering, DMCE, University of Mumbai
Diploma, Electronics Engineering, Government Polytechnic, Mumbai



Skills:
Programming Languages: Java, SQL, C, JavaScript (Working knowledge); Frameworks/Libraries: Spring Boot, Spring MVC, Hibernate, React.js (Basic); Web Technologies: HTML, CSS, JSP, Servlets (Working knowledge); Databases: MySQL, Oracle, MongoDB; Tools/Platforms: Tomcat, Linux, Eclipse, STS, Maven, Gradle; Version Control/CI/CD: Git, SVN, Jenkins; Testing: JUnit, Mockito, Selenium; Development Practices: Agile, Scrum, TDD; APIs: RESTful APIs, SOAP



Key Projects



UPI Global
Designed and implemented backend modules for international UPI transactions, including global QR payments and app-based activation, using Java and Spring Boot. Integrated multi-currency conversion, merchant onboarding, and compliance workflows for seamless cross-border payments.



Rupay Credit for UPI Transactions
Developed secure integration of Rupay credit cards with UPI on Yono, implementing card discovery, validation, PIN setup, and payment authorization using Java and Spring Boot. Built business logic for restrictions and custom settlement processing.



Foreign Inward/Outward Remittance (FIR/FOR)
Engineered backend components for UPI-based foreign remittances, integrating VPA, KYC, OTP, and product code validations. Implemented real-time heartbeat and consent flows, and managed secure, scalable transaction processing for UPI–PayNow integration.



ICCW (Interoperable Card-less Cash Withdrawal)
Built UPI-based card-less cash withdrawal for SBI ATMs, focusing on QR code generation/validation, NFS integration, and secure, RBI-compliant transaction flows.



UPI Lite
Developed backend services for UPI Lite to support low-value, high-frequency transactions, implementing efficient top-up and micropayment flows for scalability and reliability.



FINEOS Absence Management Module
Developed modular, scalable features for FINEOS AdminSuite using Java and Google Guice, enhancing plan/data management logic and integrating with legacy systems.
