Section 0: Candidate Details

Full Name: Iqra Afreen

Email Address: mirzaiqra2022@gmail.com

College: Deewan VS Institute of Engineering and Technology

GitHub Profile URL: https://github.com/CodeCraftIqra

Internship Batch / Group Name: MERN and PERN Full Stack Internship

Section 1: Git & GitHub

1. Difference between Git and GitHub

Git is a distributed version control system that allows developers to track changes in source code locally, manage versions, and collaborate efficiently. GitHub is a cloud-based platform that hosts Git repositories and provides collaboration features such as pull requests, issue tracking, code reviews, and team management.

2. git clone, git pull, git fetch

git clone is used to create a local copy of a remote repository.
git pull fetches changes from a remote repository and immediately merges them into the current branch.
git fetch retrieves changes from the remote repository without merging them, allowing review before integration.

3. Merge conflict & resolution

A merge conflict occurs when Git cannot automatically merge changes due to conflicting modifications in the same part of a file. It is resolved by manually reviewing the conflicting code, selecting or combining the correct changes, and then committing the resolved version.

4. git merge vs git rebase

git merge combines branches by creating a new merge commit while preserving the complete history.
git rebase rewrites the commit history by moving commits to a new base, resulting in a cleaner and linear commit history.

5. .gitignore

The .gitignore file specifies which files or directories Git should ignore, such as node_modules or .env files. It helps prevent unnecessary, sensitive, or auto-generated files from being committed to the repository.

6. GitHub Repository Link

https://github.com/CodeCraftIqra/Assesment_Questions

Section 2: MySQL & PostgreSQL
1. MySQL vs PostgreSQL

MySQL is known for its simplicity and performance in read-heavy applications. PostgreSQL provides advanced features, strict ACID compliance, and is better suited for complex queries and large-scale applications.

2. Primary key & Foreign key

A primary key uniquely identifies each record in a table. A foreign key establishes a relationship between two tables by referencing the primary key of another table.

3. WHERE vs HAVING

The WHERE clause filters rows before grouping occurs, while the HAVING clause filters grouped data after aggregation functions are applied.

4. DELETE vs TRUNCATE

DELETE removes specific rows from a table and supports rollback.
TRUNCATE removes all rows quickly, resets identity counters, and does not support rollback.

5. Database normalization

Database normalization is the process of organizing data to reduce redundancy and improve data integrity by dividing data into related tables.

6. JOIN Types

An INNER JOIN returns records that have matching values in both tables.
A LEFT JOIN returns all records from the left table along with matching records from the right table.
A RIGHT JOIN returns all records from the right table along with matching records from the left table.

7. SQL Queries
   
INSERT INTO users VALUES (1, 'John');

SELECT * FROM users;

UPDATE users SET name = 'Alex' WHERE id = 1;

DELETE FROM users WHERE id = 1;

SELECT * FROM orders o 

INNER JOIN users u ON o.user_id = u.id;

Section 3: React Fundamentals

1. What is React?

React is a JavaScript library used for building fast, scalable, and reusable user interfaces using a component-based architecture.

2. State vs Props

State is mutable data managed within a component and can change over time. Props are immutable data passed from a parent component to a child component.

3. React Hooks

React Hooks are functions that allow functional components to manage state and lifecycle features, such as useState and useEffect.

4. useEffect Example
   
useEffect(() => {
  fetchData();
}, []);

The useEffect hook is used to perform side effects such as API calls after the component renders.

5. Lifting State Up

Lifting state up involves moving shared state to the nearest common parent component so that multiple child components can access and update it.

6. React Practical GitHub Link

https://github.com/CodeCraftIqra/Weather-app

Section 4: TypeScript Basics

1. What is TypeScript?

TypeScript is a superset of JavaScript that introduces static typing, enabling better error detection, scalability, and maintainability of applications.

3. any vs unknown

The any type disables type checking, while unknown enforces type safety by requiring validation before usage.

5. Interfaces

Interfaces define the structure of objects in TypeScript.

interface User {
  name: string;
  age: number;
}

4. Type Inference

TypeScript automatically determines variable types based on assigned values, reducing the need for explicit type declarations.

6. Optional & Readonly Properties
interface User {
  readonly id: number;
  name?: string;
}

8. TypeScript GitHub Link

https://github.com/CodeCraftIqra/Blind_mate

Section 5: General Web Development

1. REST API

A REST API is an architectural style that uses standard HTTP methods to perform CRUD operations on resources.

2. PUT vs PATCH

PUT updates the entire resource, whereas PATCH updates only specific fields of a resource.

3. CORS

Cross-Origin Resource Sharing (CORS) is a security mechanism that allows or restricts resource access from different origins.

4. SQL vs NoSQL

SQL databases are relational with a fixed schema, while NoSQL databases are non-relational, schema-flexible, and designed for scalability.

5. MVC Architecture

The Model manages data and business logic, the View handles the user interface, and the Controller processes user input and coordinates between the Model and View.
