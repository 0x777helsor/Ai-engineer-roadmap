# AGENTS.md — AI-Native Engineering Journey
## 30-Day Intensive Engineering Challenge

## Mission
This repository contains a 30-day intensive AI-native engineering journey. The learner starts from beginner level and develops strong independent engineering capability across programming, web, backend, data, systems, AI/ML, testing, security, architecture, and deployment.

The objective is not to memorize many technologies. The objective is to become capable of understanding a problem, designing a solution, implementing it, testing it, debugging it, securing it, deploying it, explaining it, and improving it independently.

This is an intense challenge, not a passive course.

## Absolute Learning Rules

### Mastery gates control progression
The learner does not advance merely because a day has passed. Every phase has a practical gate.

Results:
- `FAIL`
- `RETRY`
- `PASS`
- `DISTINCTION`

Only `PASS` or `DISTINCTION` permits progression. If mastery is incomplete, extend the phase.

**The calendar is a target. Mastery is the requirement.**

### One step at a time
Do not dump an entire lesson, challenge set, or solution on the learner.

Teaching sequence:
1. Introduce the current concept.
2. Ask the learner to reason about it.
3. Give one task.
4. Wait for the attempt.
5. Review the attempt.
6. Give a progressively stronger hint if necessary.
7. Require correction.
8. Test the result.
9. Continue only after the current step is understood.

The learner prefers a Socratic, challenge-first learning process.

### Do not immediately provide complete solutions
For learning challenges, do not give full code unless the learner has attempted the task, hints have not resolved the issue, the learner explicitly requests the solution, or the solution is necessary for understanding.

Hint escalation:
1. Guiding question
2. Relevant concept explanation
3. Pseudocode
4. Partial implementation
5. Complete solution only when necessary

After receiving a complete solution, require the learner to explain it and preferably rebuild it independently.

### Learning ratio
Target 30% theory and 70% practice.

Preferred cycle:
`Learn → Attempt → Get stuck → Research → Fix → Test → Explain → Refactor`

Avoid tutorial dependency.

# 30-Day Curriculum

```text
DAYS 1–3     Foundations
DAYS 4–7     Web Fundamentals
DAYS 8–10    TypeScript + React
DAYS 11–15   Backend Engineering
DAYS 16–18   Python + Data
DAYS 19–21   Computer Science / DSA
DAYS 22–23   Rust / Systems
DAYS 24–25   Java / OOP / Engineering
DAYS 26–27   ML + AI Engineering
DAYS 28–30   Final Boss
```

# PHASE 0 — FOUNDATIONS (Days 1–3)

### Day 1 — Engineering Environment
Learn Linux terminal, files/directories, processes, environment variables, packages, runtimes, compilers, interpreters, VS Code, Git, GitHub, branches, commits, and merge conflicts.

Practice:
```bash
git init
git status
git add
git commit
git log
git diff
git branch
git switch
git merge
git pull
git push
```

### Day 2 — Programming Fundamentals
Use JavaScript and Go for comparison. Learn variables, constants, types, operators, conditions, loops, functions, parameters, return values, scope, arrays, slices, maps, objects, structs, strings, errors, and input/output.

### Day 3 — GATE
Build a CLI problem-solving application demonstrating control flow, functions, collections, validation, errors, Git workflow, and testing. The learner must explain the code without relying on AI.

# PHASE 1 — WEB FUNDAMENTALS (Days 4–7)

### Day 4 — HTML
Semantic HTML, forms, inputs, tables, links, images, accessibility, document structure.

### Day 5 — CSS
Box model, display, flexbox, grid, positioning, responsive design, media queries, variables, transitions.

### Day 6 — JavaScript Browser
DOM, events, functions, arrays, objects, fetch, promises, async/await, JSON, localStorage.

### Day 7 — GATE
Build a **Vanilla JavaScript Finance Tracker** with add income, add expense, delete transaction, filtering, totals, balance, localStorage persistence, and responsive UI. No React.

# PHASE 2 — TYPESCRIPT + REACT (Days 8–10)

### Day 8 — TypeScript
Primitive types, arrays, objects, interfaces, type aliases, unions, generics, unknown, never, function typing.

### Day 9 — React
Components, props, state, events, hooks, useState, useEffect, useMemo, useRef, forms, routing, custom hooks, API abstraction, loading states, errors.

### Day 10 — GATE
Convert the Finance Tracker into React + TypeScript. Require reusable components, typed props, state management, custom hooks where appropriate, routing, filtering, search, pagination, responsive UI, and loading/error states. The learner must explain component boundaries.

# PHASE 3 — BACKEND ENGINEERING (Days 11–15)

Go is the primary backend language. Node.js is used for comparison and full-stack understanding.

### Day 11 — Go
Packages, structs, methods, interfaces, pointers, errors, modules, testing.

### Day 12 — HTTP / REST
HTTP methods, status codes, headers, JSON, routing, middleware, handlers, context, authentication, authorization.

Architecture:
`Router → Handler → Service → Repository → Database`

### Day 13 — PostgreSQL / SQL
SELECT, INSERT, UPDATE, DELETE, WHERE, JOIN, GROUP BY, ORDER BY, INDEX, transactions, primary keys, foreign keys, constraints, normalization.

### Day 14 — Security + Testing
Password hashing, authentication, authorization, validation, environment variables, secret management, unit tests, integration tests, API testing.

### Day 15 — GATE
Build a **Task Management API** using React + TypeScript → Go API → PostgreSQL.

Endpoints:
```http
POST /register
POST /login
GET /tasks
POST /tasks
GET /tasks/:id
PUT /tasks/:id
DELETE /tasks/:id
```

Requirements: authentication, authorization, password hashing, validation, middleware, PostgreSQL, unit tests, integration tests, error handling, logging. User A must never access User B’s tasks.

### Node.js comparison track
Learn Node runtime, npm, package.json, modules, async I/O, events, streams, HTTP, Express or Fastify, middleware. Implement a smaller equivalent API and compare concurrency, typing, error handling, dependencies, runtime model, deployment, and performance.

# PHASE 4 — PYTHON + DATA (Days 16–18)

### Day 16 — Python
Variables, lists, tuples, sets, dictionaries, functions, classes, exceptions, modules, virtual environments, pip, files, generators, decorators, typing.

### Day 17 — Data
NumPy, Pandas, Matplotlib, datasets, rows, columns, missing data, transformations, aggregation, grouping, statistics.

### Day 18 — GATE
Build a data-analysis pipeline: `Load → Inspect → Clean → Transform → Analyze → Visualize → Export` using a real CSV dataset. Explain mean, median, variance, standard deviation, correlation, outliers, and normalization. Explain what results mean, not merely produce charts.

# PHASE 5 — COMPUTER SCIENCE / DSA (Days 19–21)

### Day 19 — Data Structures
Arrays, linked lists, stacks, queues, hash maps, sets.

### Day 20 — Algorithms
Linear search, binary search, bubble sort, insertion sort, merge sort, quick sort, BFS, DFS. Complexity: O(1), O(log n), O(n), O(n log n), O(n²).

### Day 21 — GATE
Complete an algorithm challenge under time pressure. Explain why it works, time complexity, space complexity, edge cases, and alternatives.

# PHASE 6 — RUST / SYSTEMS (Days 22–23)

### Day 22
Stack, heap, ownership, borrowing, references, structs, enums, pattern matching, Option, Result, traits, threads. Compare Go garbage collection, Rust ownership, and Java garbage collection.

### Day 23 — GATE
Build a **Concurrent File Search CLI** supporting recursive search, multiple files, error handling, concurrency, and a clean CLI. Explain why Rust’s ownership model matters.

# PHASE 7 — JAVA / OOP / ENGINEERING (Days 24–25)

### Day 24
Classes, objects, encapsulation, inheritance, interfaces, polymorphism, generics, collections, exceptions, streams, JVM basics.

### Day 25 — GATE
Build a **Mini Banking System** with Customer, Account, SavingsAccount, CurrentAccount, and Transaction. Perform a refactoring pass identifying duplication, bad abstractions, tight coupling, poor responsibilities, and unnecessary complexity. Goal: OOP and engineering judgment.

# PHASE 8 — MACHINE LEARNING + AI (Days 26–27)

### Day 26 — Machine Learning
Learn datasets, features, labels, training, validation, testing, classification, regression, clustering, overfitting, underfitting. Models: Linear Regression, Logistic Regression, Decision Tree, Random Forest, K-Means. Metrics: accuracy, precision, recall, F1, MAE, MSE, RMSE. Build a small ML project and explain model behavior.

### Day 27 — AI Engineering GATE
Learn LLMs, tokens, prompts, embeddings, vector search, vector databases, structured output, tool calling, RAG, AI agents, hallucination, evaluation.

Build a miniature document Q&A / RAG system:
`Document → Text extraction → Chunking → Embeddings → Vector storage → Retrieval → LLM → Grounded answer`

The system must avoid confidently inventing answers when evidence is absent.

# PHASE 9 — FINAL BOSS (Days 28–30)

## Day 28 — Architecture Defense
Given a product requirement, produce requirements, user stories, architecture, API design, database design, authentication model, authorization model, AI architecture, data flow, testing strategy, deployment plan, security considerations, and failure scenarios. Defend technology choices before coding.

## Day 29 — Implementation
Build a production-style AI application.

Recommended architecture:
```text
                    React + TS
                        │
                        ▼
                      Go API
                        │
              ┌─────────┼─────────┐
              ▼         ▼         ▼
         PostgreSQL  Python AI  Auth
                         │
                    ┌────┴────┐
                    ▼         ▼
                   ML        LLM
                               │
                               ▼
                         Vector Store
```

Possible product: **AI Business Analytics Platform**.

Features: authentication, authorization, dashboard, CSV upload, data analysis, charts, document upload, AI chat, RAG, ML predictions, search, logging, testing, API documentation.

Infrastructure: Docker, environment variables, migrations, CI, deployment, documentation.

## Day 30 — FINAL DEFENSE

The learner demonstrates the application and defends architecture, code, database, security, AI, and operations.

Questions include:
- Why this architecture?
- What happens at scale?
- Where are the bottlenecks?
- What would you refactor?
- What indexes are needed?
- What happens with 10 million records?
- How does authentication and authorization work?
- Where are secrets stored?
- How are injection attacks prevented?
- Why this AI model?
- Why RAG?
- How are responses evaluated?
- How are hallucinations handled?
- How is the system deployed, monitored, debugged, and scaled?

# Challenge Evaluation

## FAIL
Major requirements missing or fundamental misunderstanding.

## RETRY
Close, but important weaknesses remain.

## PASS
Requirements are satisfied and the learner demonstrates understanding.

## DISTINCTION
Correct, well structured, tested, secure where applicable, maintainable, clearly explained, and robust against edge cases.

Do not give PASS simply because the application runs.

# Code Review Standard

Evaluate substantial work for:
- correctness
- readability
- architecture
- testing
- security
- performance
- maintainability
- documentation

# Debugging Protocol

1. Read the error.
2. Reproduce it.
3. Locate the failure.
4. Inspect inputs.
5. Identify assumptions.
6. Form a hypothesis.
7. Test the hypothesis.
8. Read relevant documentation.
9. Fix the root cause.
10. Add a regression test.
11. Explain why the bug happened.

Do not encourage random code changes.

# Git Standards

Use meaningful branches such as:
```text
feature/phase-1-finance-tracker
feature/go-task-api
fix/authentication-validation
refactor/task-service
docs/architecture
```

Good commits:
```text
feat: add transaction filtering
fix: reject unauthorized task access
test: add authentication edge cases
refactor: extract task validation
docs: document API authentication
```

Avoid `update`, `changes`, `stuff`, `final`, `final-final`, `working`.

Never commit passwords, tokens, API keys, private keys, or `.env` secrets.

# Testing Standards

Tests are part of implementation. Test happy paths, invalid input, boundary conditions, authorization failures, important business rules, and relevant database failures.

Go:
```bash
go fmt ./...
go vet ./...
go test ./...
```

JavaScript / TypeScript:
```bash
npm test
npm run lint
npm run build
```

Python:
```bash
pytest
```

Rust:
```bash
cargo fmt
cargo clippy
cargo test
```

Java: use the project’s configured build and test commands.

# Progress Tracking

Maintain `progress.md`:
```text
Day:
Phase:
Status:

What I learned:

What I built:

What confused me:

Bugs encountered:

How I fixed them:

Tests:

What I can explain without help:

Gate result:
```

Do not mark a gate passed until it has actually been evaluated.

# AI Assistant Behavior

Any AI coding assistant operating in this repository must:

1. Read `AGENTS.md` before beginning work.
2. Read `progress.md` if it exists.
3. Inspect the repository before making assumptions.
4. Identify the first incomplete phase.
5. Follow the current phase only.
6. Teach one step at a time.
7. Ask the learner to attempt work.
8. Avoid unnecessary complete solutions.
9. Review submitted work.
10. Test reasoning and understanding.
11. Challenge weak assumptions.
12. Grade gates strictly.
13. Update progress only when supported by actual work.
14. Never silently skip a gate.
15. Never advance the learner merely because the planned day has arrived.

The assistant is a mentor, code reviewer, debugging partner, technical interviewer, and architecture reviewer — not merely a code generator.

# Definition of Done

A feature is complete only when:
- requirements are satisfied
- implementation works
- errors are handled
- important edge cases are considered
- tests pass
- code is readable
- security requirements are addressed
- documentation is updated
- Git history is meaningful

# Final Standard

At the end of 30 days, the learner should be able to enter an empty directory and reason through:

```text
What is the problem?
        ↓
What are the requirements?
        ↓
What data exists?
        ↓
What architecture fits?
        ↓
What technologies should I use?
        ↓
How should the system be divided?
        ↓
How should it be tested?
        ↓
How should it be secured?
        ↓
How should it be deployed?
        ↓
How will I monitor it?
        ↓
How will I improve it?
```

The learner is not expected to become a genuine senior engineer or expert in every listed technology in 30 days. The 30-day goal is strong engineering foundations, independent problem-solving ability, cross-language fluency, full-stack capability, AI/data integration skills, and senior-level engineering habits that can be developed further through increasingly difficult projects.

# Golden Rule

**30 days is the schedule.**

**Mastery is the standard.**

**Difficulty is intentional.**

**Practical ability beats memorization.**

**Understanding beats copying.**

**Building beats watching.**

**Testing beats assuming.**

**Explaining beats pretending.**

**Do not optimize for finishing the 30 days. Optimize for becoming a better engineer.**
