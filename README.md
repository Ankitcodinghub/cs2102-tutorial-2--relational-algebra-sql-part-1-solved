# cs2102-tutorial-2--relational-algebra-sql-part-1-solved
**TO GET THIS SOLUTION VISIT:** [CS2102 Tutorial #2- Relational Algebra & SQL (Part 1 Solved](https://www.ankitcodinghub.com/product/cs2102-solved-5/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117757&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2102 Tutorial #2- Relational Algebra \u0026amp; SQL (Part 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
1 Discussions

The following questions are to be discussed during tutorial. All answers will be released with explanation.

1. (RA Operator) This question considers a binary relational algebra operator called the division operator denoted by / . Consider two relations R and S:

• R(A1,··· ,Am,B1,··· ,Bn)

• S(B1,··· ,Bn)

where m 1 and n 1. That is, the set of attributes in S is a proper subset of the set of attributes in R.

Assume that the attributes that are in R but not in S are ordered as (A1,··· ,Am) in the schema of R and the schema of S is (B1,··· ,Bn). Let L denote the list of attributes in the schema of R.

The division of R by S (denoted by R/S) computes the largest set of tuples Q ✓ ⇡[A1,···,Am](R) such that for every tuple (a1,··· ,am) 2 Q,

⇡[L]({(a1,··· ,am)} ⇥ S) ✓ R

Q is also referred to as the quotient of R/S and its schema is (A1,··· ,Am). The following example illustrates R/S given two relations R(A,B) and S(B).

1

R

A B

a 1

a 2

b 1

c 1

c 2

c 3

d 2

d 3

A

a

c

B

1

2

S R/S

(a) Consider again Question 3 in Tutorial 1 (Challenge) to find the restaurants that sell all the pizzas that Maggie likes and don’t sell any pizza that Ralph likes. Write a relational algebra expression for this query that uses the division and natural join operators.

(b) Given relations R(A,B) and S(B), write a relational algebra expression to compute the division of R by S using only the basic relational operators (i.e., , ⇡, ⇢, ⇥, [, and ).

2. (SQL DDL) Consider a relational database for a company that consists of the following two tables.

• Offices(officeid, building, floor, room number, area)

• Employees(emp id, name, office id, manager id)

The database satisfies the following constraints:

1. Offices stores information about the o ce rooms in the company. Each room has a unique identifier office id (which is the primary key of Offices) and information on its building name, floor level, room number and floor area.

2. {building, floor, room number} is a candidate key of Offices.

3. Employees stores information about the employees in the company.

4. emp id is the primary key of Employees.

5. The name of each employee must be a non-NULL value.

8. If an employee is managed by someone, the emp id of his/her manager is recorded in manager id.

10. A manager in Employees cannot be removed if there’s some other employee managed by that manager.

11. Any modification to office id in Offices is propagated to other database records.

12. Any modification to emp id in Employees is propagated to other database records.

Write SQL statements to create the database schema with appropriate attribute domains and constraints.

3. (SQL DDL) Consider a relational database for an online shop that consists of the following five tables.

• Books(isbn, title, authors, year, edition, publisher, number pages, price)

• Customers(cust id, name, email)

• Carts(cust id, isbn)

• Purchased items(pid, isbn)

The database satisfies the following constraints:

1. Books records information about the books available for sale in an online shop. Each book has a unique identifier isbn and information about its title, authors, publishers, publication year, edition, number of pages and selling price. The title and authors must have non-NULL values. The value of the edition must be non-NULL with one of the following values: paperback, hardcover or ebook. The selling price must have a positive value. If the number of pages in known, it must be a positive value.

2. Customers stores information about the shop’s customers. Each customer has a unique identifier cust id, a name and an email address. The name must have a non-NULL value.

3. Carts stores information about the books in customers’ shopping carts. Each shopping cart record indicates a book that a customer is interested to purchase but hs not yet purchased.

4. When a customer decides to purchase their selected books, a new record for this purchase is recorded in the Purchase table which has the following information:

(a) A unique identifier pid.

(c) The customer identifier.

In addition, each book in the customers’ shopping cart is added to the Purchased items table and the customers’ shopping cart is emptied.

(a) Write SQL statements to create a database schema with appropriate attribute domains and constraints.

(c) For each of the following additional constraints on the database, state whether the constraint can be expressed using SQL constructs that you have learned. If it is possible, add this constraint to your database schema in part (a).

1. If a book is a hardcover edition, its selling price must be at least 30.

2. If a book has both hardcover and paperback editions (for the same book title and authors), the selling price for the hardcover edition must be higher than the selling price for the paperback edition.

3. If the number of pages in a book is more than 1000, the edition of the book must be an ebook or its price must be at least 100.

4. All the books published by ’Acme’ from 2010 onwards have only ebook edition.

2 Challenge

The answers to the following questions is given without explanation. Please discuss them on Canvas.

1. (SQL DDL) This question refers to your solution for question 3.

(a) Consider the following additional constraints on the database:

1. If a customer is deleted from Customers, remove all the customers’ records from Carts and Purchase.

2. If a book is deleted from Books, remove all records from Carts that reference this book. Additionally, for each of the records in Purchased items that reference this book, change its isbn value to the default value of 0.

3. If a purchase is deleted from Purchase, remove all the records from Purchased items that reference this purchase.

4. Any modification of cust id in Customers is propagated to other records in the database.

5. Any modification of isbn in Books is propagated to other records in the database.

6. Any modification of pid in Purchase is propagated to other records in the database.

Add these additional constraints to your answer for question 3(a).

2. (Cardinalities) You are given 2 relations R and S, with m being the number of tuples in R (i.e., |R| = m) and n being the number of tuples in S (i.e., |S| = n). Assume that m &gt; n &gt; 0, R and S are union-compatible and both relations do not contain any null values.

(a) R [ S [] (d) R ./ S []

(b) R S [] (e) R ./ S []

(c) R S []

3. (Equivalence) Select ALL (strongly) equivalences are true?

(a) c(E1 E2) ⌘ c(E1) E2

(b) ⇡A(⇡B(E)) ⌘⇡A(E)

(c) c1(E1 ./c2 E2) ⌘ c2(E1 ./c1 E2)

(d) (E1 ./c1 E2) ./c2^c3 E3 ⌘ E1 ./c1^c2 (E2 ./c3 E3)

(e) (E1 ./ E2) ./ E3 ⌘ E1 ./ (E2 ./ E3)
