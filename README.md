# Algorithms and Data Structures Tasks for PI24E students.

Theory with practice : https://runestone.academy/ns/books/published/cppds/index.html

Any book Bjarne Stroustrup, The C++ Programming Language.


C++ docs : https://en.cppreference.com/w/cpp/algorithm/binary_search


### PROGRAMMING TOOLS : 

Jetbrains C++ CLION IDE
https://www.jetbrains.com/shop/eform/students

OR USE VISUAL STUDIO

### CONTACT INFO 

E-mail: m.gzegozevskis@eif.viko.lt; 

# TASKS 

1. Data Structures in Real-World Applications (Arrays, Stacks, Queues, Deques)
📌 Task: Implement an Undo/Redo system for a text editor

Use a stack to track user actions (typed text, deleted text).
Implement undo (pop from stack) and redo (push to another stack).
🔹 Real-world relevance: Used in text editors, code editors, and design software.

2. Dynamic Lists for Social Media Feeds
📌 Task: Design a linked list-based social media feed system

Each post is a node in a doubly linked list.
Implement adding, removing, and sorting posts (based on time or engagement).
Allow navigation using "next" and "previous" buttons.
🔹 Real-world relevance: Similar to Facebook, Instagram, and Twitter feed algorithms.

3. Binary Trees for File System Management
📌 Task: Simulate a file system structure using a binary tree

Implement folders as nodes in a binary tree.
Each node can store file metadata (name, size, type).
Implement recursive searching for a file by name.
🔹 Real-world relevance: How operating systems store directories and files.

4. Balanced Trees for Database Indexing (B-Trees)
📌 Task: Design a simple database indexing system using a B-tree

Store employee records in a B-tree for efficient searching.
Implement fast lookups by employee ID or name.
🔹 Real-world relevance: SQL and NoSQL databases use B-trees for fast indexing.

5. Graphs for Route Optimization (Dijkstra’s Algorithm)
📌 Task: Develop a route planner for a city’s public transport system

Use a graph where nodes = bus/train stations, edges = travel times.
Implement Dijkstra’s algorithm to find the shortest route between two locations.
Bonus: Allow real-time traffic updates (adjust edge weights dynamically).
🔹 Real-world relevance: Used in Google Maps, Waze, and GPS navigation.

6. Sorting Algorithms in E-Commerce (Product Listings)
📌 Task: Implement sorting algorithms for an online store’s product catalog

Products have name, price, rating, and popularity.
Implement QuickSort and MergeSort to sort products by different attributes.
Compare performance for small vs. large datasets.
🔹 Real-world relevance: Amazon, eBay, and Shopify use sorting for product recommendations.

7. Heap for Job Scheduling in an Operating System
📌 Task: Create a job scheduler for a cloud computing service

Use a min-heap to prioritize jobs based on priority level.
Jobs with lower execution time get processed first.
Implement Heapsort to efficiently schedule and execute jobs.
🔹 Real-world relevance: Used in AWS, Google Cloud, and OS process scheduling.

8. AI and Machine Learning (Decision Trees & Graphs)
📌 Task: Build a simple decision tree for medical diagnosis

Use a binary decision tree where each node represents a symptom/question.
Based on user input, navigate through the tree to suggest a possible diagnosis.
🔹 Real-world relevance: Used in healthcare AI and chatbots.

9. Cybersecurity: Password Strength Checker (Hash Tables & Sorting)
📌 Task: Develop a password strength checker

Use a hash table to store and check weak passwords (e.g., common passwords list).
Implement sorting algorithms to rank password strength.
🔹 Real-world relevance: Used in Google, Microsoft, and security software.

10. Real-Time Event Processing (Queues in Messaging Systems)
📌 Task: Simulate a real-time messaging system using a queue

Messages are enqueued when sent and dequeued when delivered.
Implement a priority queue for urgent messages.
🔹 Real-world relevance: Used in WhatsApp, Slack, Kafka, and message brokers.



# Project Title: Interactive Learning Decision Tree Game
Overview
This project involves creating an interactive game that utilizes a decision tree to guess what the user is thinking. The game learns from the user's inputs by asking yes/no questions and, if unable to guess correctly, requests the correct answer and a new distinguishing question to expand its knowledge base for future interactions. The decision tree is dynamically updated and persisted across sessions by storing it in a file.

Objectives
To develop an understanding of decision trees and their applications in simple machine learning contexts.
To gain experience with file input/output operations for data persistence.
To practice implementing algorithms that manipulate complex data structures.
To enhance programming skills in C++ with a focus on object-oriented design.
Functional Requirements
Initialization from File: On startup, the program should load an existing decision tree from a file (data.txt), creating a basic tree if the file does not exist or is empty.
Interactive Gameplay: The program must interactively ask the player yes/no questions in an attempt to guess what the player is thinking of. This process should traverse the decision tree based on the player's responses.
Learning from Mistakes: If the game fails to guess correctly, it should ask the player for the correct answer and a question that can distinguish this answer from its incorrect guess. The game should then update the decision tree with this new information.
Data Persistence: After updating the decision tree with new information, the game should save the updated tree back to the file, ensuring that the learning is retained for future game sessions.
User Interface: Implement a simple, user-friendly console interface that guides the player through the game, making it clear when input is expected and providing feedback on the game's guesses.
Technical Requirements
Language: The project must be implemented in C++.
Data Structure: Utilize custom structs or classes to represent the nodes of the decision tree, each containing a question or answer string, IDs for itself, and links to its left (yes) and right (no) children.
File I/O: Implement file reading and writing operations to load and save the decision tree.
Memory Management: Ensure that the program efficiently manages memory, especially when dynamically resizing the decision tree.
Error Handling: The program should gracefully handle common errors, such as file not found, invalid input formats, and unexpected user input.
Deliverables
Source Code: Well-documented and cleanly written source code for the game.
Executable: A compiled version of the game that can be easily run on a standard computer.
User Manual: A brief document explaining how to play the game, including how to start the game, how to interact with it, and what kind of questions the game can learn from.
Design Document: A detailed explanation of the decision tree structure, including how nodes are added and traversed. This document should also outline the main components of the program and their interactions.
Evaluation Criteria
Functionality: The game correctly implements all functional requirements, accurately guessing and learning from user inputs.
Usability: The game provides a clear and intuitive user experience, with easy-to-understand prompts and feedback.
Code Quality: The source code is well-organized, readable, and appropriately commented, demonstrating good programming practices.
Robustness: The program handles errors and edge cases gracefully, without crashing or behaving unexpectedly.
Documentation: The provided documents clearly explain the game's design and how to use it, demonstrating an understanding of the project's objectives and technical details.
EXAMPLE IMPLEMENTATION: https://gist.github.com/eif-courses/c6c0170608adcbaf9b2a4f93287c9178



