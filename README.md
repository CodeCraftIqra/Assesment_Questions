# Assesment_Questions

Section 0: Candidate Details
Full Name – Iqra Afreen

Email Address – mirzaiqra2022@gmail.com

College  – Deewan VS Institute of Engineering and Technology

GitHub Profile URL – https://github.com/CodeCraftIqra

Internship Batch / Group Name – Mern and Pern fullstack Internship

Section 1: Git & Github
1. Difference between Git and GitHub
Git is a distributed version control system used to track code changes locally whereas GitHub is a cloud-based platform that hosts Git repositories and enables collaboration.

2. git clone, git pull, git fetch
git clone: Creates a local copy of a remote repository.
git pull: Fetches changes and merges them into the current branch.
git fetch: Fetches changes without merging.

3. Merge conflict & resolution
A merge conflict occurs when Git cannot automatically merge changes.
Resolution involves manually editing conflicting files, choosing the correct changes, and committing them.

4. git merge vs git rebase
merge: Creates a new merge commit and preserves history.
rebase: Rewrites commit history for a cleaner linear structure.

5. .gitignore
.gitignore specifies files/folders Git should ignore (e.g., node_modules, .env), preventing sensitive or unnecessary files from being committed.

6. GitHub Repository link
https://github.com/CodeCraftIqra/Assesment_Questions

Section 2: MySQL & PostgreSQL
1. MySQL vs PostgreSQL
MySQL: Faster for read-heavy workloads, simpler architecture.
PostgreSQL: Advanced features, strict ACID compliance, better for complex queries.

2. Primary key & Foreign key
Primary key uniquely identifies a record.
Foreign key references a primary key in another table.

3. WHERE vs HAVING
WHERE: Filters rows before grouping.
HAVING: Filters groups after aggregation.

4. DELETE vs TRUNCATE
DELETE: Removes specific rows, rollback possible.
TRUNCATE: Removes all rows, faster, no rollback.

5. Database normalization
Process of organizing data to reduce redundancy and improve data integrity.

6. JOIN types
INNER JOIN: Matching records from both tables.
LEFT JOIN: All records from left table + matched right.
RIGHT JOIN: All records from right table + matched left.

7. SQL Queries
INSERT INTO users VALUES (1, 'John');
SELECT * FROM users;
UPDATE users SET name='Alex' WHERE id=1;
DELETE FROM users WHERE id=1;
SELECT * FROM orders o INNER JOIN users u ON o.user_id = u.id;

Section 3: React Fundamentals
1. What is React?
React is a JavaScript library for building fast, reusable, component-based user interfaces.

2. State vs Props
State: Mutable, managed inside the component.
Props: Immutable, passed from parent to child.

3. React Hooks
Hooks are functions that allow functional components to use state and lifecycle features (e.g., useState, useEffect).

4. useEffect example
useEffect(() => {
  fetchData();
}, []);
Runs side effects like API calls after render.

5. Lifting state up
Moving shared state to the nearest common parent to share data between components.

6. React practical GitHub link
(https://github.com/CodeCraftIqra/Weather-app)

Section 4: TypeScript Basics
1. What is TypeScript?
TypeScript is a superset of JavaScript that adds static typing to improve code quality and maintainability.

2. any vs unknown
any: No type checking.
unknown: Type-safe; requires type checking before use.

3. Interfaces
Interfaces define the structure of an object.

interface User {
  name: string;
  age: number;
}

4. Type inference
TypeScript automatically infers variable types based on assigned values.

5. Optional & readonly properties
interface User {
  readonly id: number;
  name?: string;
}

6. TypeScript GitHub link
https://github.com/CodeCraftIqra/Blind_mate

Section 5: General Web Development
1. REST API
An architectural style that uses HTTP methods to perform CRUD operations on resources.

2. PUT vs PATCH
PUT: Updates entire resource.
PATCH: Updates partial resource.

3. CORS
Cross-Origin Resource Sharing allows controlled access to resources from different origins.

4. SQL vs NoSQL
SQL: Structured, relational, fixed schema.
NoSQL: Flexible schema, scalable, document/key-value based.

5. MVC Architecture
Model: Data and business logic
View: UI layer
Controller: Handles user input and updates model/view
