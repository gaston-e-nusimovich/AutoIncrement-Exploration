## Welcome to AutoIncrement Exploration

This repository contains the tools I have developed to explore the ups and downs of the use of AutoIncremental (Identity, Sequence) generators for ID fields in tables in any given SQL DBMS (that supports autoincremental generators).

### General Comments

The main reason for this exploration is to determine, with as many objective arguments as possible (based on evidence, that is), how good or bad, from the perspective of both **Quality Attributes** (like performance and scalability) and **Software Architecture**, is the overall end result that provides the use of AutoIncremental generators.

Even though I use a specific ORM tool (**NHibernate**) in the tools and code samples that form this exploration, the conclusions arrived by said exploration apply for all software projects that use AutoIncremental generators, whether or not said projects use ORM tools.
