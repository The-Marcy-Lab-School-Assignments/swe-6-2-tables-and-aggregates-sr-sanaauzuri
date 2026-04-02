# Short Response: Creating Tables and Aggregates

Answer each question below. Write in complete sentences (3–5 per answer).

---

## Question 1

What is a data type? Why does it matter what type you assign to a column? Give an example of what could go wrong if you used the wrong type.

**Your answer:**

A data type is 

## Question 2

What is a constraint? Name two constraints and explain what each one enforces.

**Your answer:**

A **constraint** is a rule that is placed onto a column to determine the values that can or cannot be stored there.\
`NOT NULL`: This constraint means that a column must have a value and cannot be left empty. For example, a password column can use this constraint to ensure that each user has a password when they sign up.
`UNIQUE`: This constraint means that no two rows can have the same value in that column. A username column can use this constraint since each user has to have a different username to be identified.


## Question 3

What is the difference between `WHERE` and `HAVING`? Can you use both in the same query? If so, what does each one do?

**Your answer:**

---

## Question 4

What is a seed file? Why is seeding important when working on a team?

**Your answer:**

---

## Question 5

You have a table called `orders` with a `customer_name` column and a `total` column. Write a SQL query that shows each customer's total spending, but only includes customers who have spent more than $100 in total.

```sql
-- Your query here
```
