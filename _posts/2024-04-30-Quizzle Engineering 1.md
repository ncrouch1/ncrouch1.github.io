---
title: 'Quizzle: The Beginning'
date: 2024-04-30
permalink: /posts/2024/Engineering/Quizzle1
tags:
  - Engineering
  - Quizzle
  - Backend
  - Project Beginnings 
---

Introducing my latest project, Quizzle. A platform similar to Quizlet in structure using flash card decks to aid users in memorizing key terms but with games!

Motivation
=====
While playing Wordle I had an idea. Why does Quizlet not include games? Gamification has been a research topic interest of mine for a while now. So when I had that thought I decided, if they're not going to make it, I'll make it.

First Project
=====
For the first building block, I decided to design and implement a flash deck service to allow creation, importing of, modification, and deletions of decks in our database. I chose Cassandra primarily for its horizontal scalability factor and because I desired to use a document database to store the decks as JSON objects. 

For the service I decided to use Spring boot and Java to implement the logic. I chose Java primarily because I am most comfortable working with the language and value the verbosity and type safety of the language.

Implementation Journey
=====
For all features I had to design a data structure to organize flashcards in both the program and database. I decided to go with a simple structure composing of a list of cards and a UUID identifier. Each card had two strings, a term and a definition. Once the data structure was set in stone programming and laying out endpoints for the server was childs play. Importing the deck from Quizlet was byfar the easiest part of the project after structuring the data. Since Quizlet offers support for the exportation of their decks, I built an endpoint to process the output of their function into a deck in my service. 

Conclusion and Learned Skills
=====
Through this process my key takeaways were the importance of structuring data and implementation of database program interfaces. Coming from a non computer science, but still adjacent, background I had no need to use a database in my coursework projects aside from BaaS (Back-end as a Service) services such as Google's firebase. Designing and implementing my first 'from scratch' connection was difficult, but an eye opening experience. From basic needs such as deciding if I wanted a relation database, to thinking about the future in horizontal scaling on platforms such as Azure, AWS, and GCP through Kubernetes. The experience was very humbling.


