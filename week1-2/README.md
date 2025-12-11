# Week 1-2: Python Fundamentals & SQL Mastery

## 📖 Overview

This section covers core Python programming and SQL database concepts. By the end of Week 2, I've mastered:
- Advanced Python (OOP, decorators, generators)
- Database design and SQL queries
- Python-database connectivity

## 📁 Project Structure

week1-2/
├── week1/
│ ├── day1_sum.py # Sum of N numbers
│ ├── day1_max_min.py # Find max/min
│ ├── day1_even_filter.py # Filter operations
│ ├── day1_count_vowels.py # String manipulation
│ ├── day1_calculator.py # Basic calculator
│ ├── day1_reverse.py # String reversal
│ ├── day1_palindrome.py # Palindrome check
│ ├── day1_merge_lists.py # List operations
│ ├── day1_find_duplicates.py # Duplicate finder
│ ├── day1_dict_ops.py # Dictionary operations
│ ├── utils.py # Utility functions (Day 2)
│ ├── main.py # Main module test (Day 2)
│ ├── bank_system.py # OOP practice (Day 3)
│ ├── vehicle_system.py # Advanced OOP (Day 4)
│ ├── comprehensions.py # List comprehensions (Day 5)
│ ├── data_transform.py # map/filter/reduce (Day 5)
│ ├── generators.py # Generators (Day 6)
│ ├── iterators.py # Iterators (Day 6)
│ ├── context_managers.py # Context managers (Day 6)
│ └── decorators.py # Decorators (Day 7)
│
└── week2/
├── food_database.sql # Database schema
├── queries.sql # Sample SQL queries
├── db_connector.py # Python-DB connectivity
├── cli_food_app.py # CLI Food Browser project
└── schema_diagram.txt # ER diagram


## 🎯 Week 1: Python Core

### Day 1: Variables, Data Types, Operators
**Concepts:** Variables, types, operators, collections  
**Projects:** 10 small programs (sum, max, filter, etc.)  
**Deliverable:** 10 .py files on GitHub

### Day 2: Functions & Modules
**Concepts:** Function definition, *args, **kwargs, imports  
**Projects:** utils.py with 5 functions, main.py imports  
**Deliverable:** Working module with imports

### Day 3: OOP Basics
**Concepts:** Classes, __init__, inheritance, methods  
**Projects:** BankAccount with SavingsAccount & CurrentAccount  
**Deliverable:** bank_system.py with inheritance

### Day 4: OOP Advanced
**Concepts:** Private variables, @property, polymorphism, ABC  
**Projects:** Vehicle abstract class with Car & Bike  
**Deliverable:** vehicle_system.py with ABC

### Day 5: Comprehensions & Functional Programming
**Concepts:** Comprehensions, lambda, map, filter, reduce  
**Projects:** 10+ comprehension examples, data transformations  
**Deliverable:** comprehensions.py & data_transform.py

### Day 6: Generators & Iterators
**Concepts:** yield, generators, custom iterators, context managers  
**Projects:** Even number generator, Fibonacci, custom iterators  
**Deliverable:** generators.py, iterators.py, context_managers.py

### Day 7: Decorators & Git
**Concepts:** Function decorators, decorator arguments, Git basics  
**Projects:** @time_logger, @require_positive, @retry decorators  
**Deliverable:** decorators.py + GitHub repo setup

## 🗄️ Week 2: SQL & Databases

### Day 8: SQL Fundamentals
**Concepts:** CREATE, INSERT, SELECT, UPDATE, DELETE  
**Deliverable:** users table with sample data

### Day 9: SQL Joins & Relationships
**Concepts:** INNER/LEFT/RIGHT JOINs, foreign keys  
**Deliverable:** Multi-table schema with working joins

### Day 10: Indexes & Optimization
**Concepts:** CREATE INDEX, EXPLAIN, query optimization  
**Deliverable:** Indexed tables with performance comparison

### Day 11: Database Design
**Concepts:** ER diagrams, normalization, relationships  
**Deliverable:** Complete food ordering schema

### Day 12: Python-Database Connectivity
**Concepts:** psycopg2/mysql-connector, CRUD operations  
**Deliverable:** db_connector.py with working functions

### Day 13: CLI Project
**Concepts:** Integration of DB with Python  
**Deliverable:** cli_food_app.py (working CLI)

### Day 14: Review & Cleanup
**Deliverable:** Clean, documented code

## 📊 Key Concepts Mastered

### Python
- ✅ Data structures (list, dict, set, tuple)
- ✅ Functions and modules
- ✅ Object-oriented programming
- ✅ Decorators and generators
- ✅ Comprehensions and functional programming

### SQL
- ✅ CRUD operations
- ✅ JOINs and relationships
- ✅ Indexing and optimization
- ✅ Database normalization
- ✅ ER diagram design

## 🔧 Technologies Used

- **Language:** Python 3.10+
- **Databases:** PostgreSQL / MySQL
- **Tools:** Git, GitHub, VS Code

## 📈 How to Run

### Python Programs
```bash
python day1_sum.py
python utils.py
python bank_system.py
```

## Database Projects
```bash
# Connect to database
psql -U username -d food_db

# Run queries
\i queries.sql

# Run Python DB connector
python db_connector.py

# Run CLI app
python cli_food_app.py
```


## 📚 Key Learnings

1. **Python OOP is crucial** - Strong foundation for everything else
2. **Database design matters** - Good schema prevents future headaches
3. **Testing edge cases** - Always verify boundary conditions
4. **Clean code** - Readable code is reusable code
5. **Git discipline** - Commit frequently with descriptive messages

## 🎓 What's Next?
- Week 3: HTTP & REST APIs with FastAPI
- Week 4: FastAPI + SQLAlchemy integration
- Week 5: Authentication & security
---
## 📝 Notes
- All code follows PEP 8 style guide
- Each program is tested and working
- Comments explain non-obvious logic
- Git history shows daily progress
---
## 👨‍💻 Author
Learning Path: 60-Day FastAPI Backend Bootcamp  
Duration: Week 1-2 (14 days)  
Status: ✅ COMPLETE