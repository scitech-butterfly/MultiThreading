# MultiThreading

Multithreading Demo in Java:

This project demonstrates the concept of multithreading in Java by running three separate operations concurrently using different thread classes:
<ol><li>EvenThread: Prints even numbers.</li>

<li>OddThread: Prints odd numbers.</li>

<li>CharThread: Prints characters (A to E).</li></ol>

Each operation runs on its own thread, showcasing parallel execution.

Project Structure

MultiThreadDemo/ ├── Main.java // Entry point of the program
├── EvenThread.java // Thread to print even numbers
├── OddThread.java // Thread to print odd numbers
└── CharThread.java // Thread to print characters A–E

How It Works:

<li>All thread classes extend the Thread class.</li>

<li>Each thread overrides the run() method and executes its respective function.</li>

<li>Threads are started from the Main class and run concurrently.</li>

Features:

<li>Demonstrates basic multithreading using Java's Thread class.</li>

<li>Clean and modular structure with separate files for each operation.</li>

<li>Each operation encapsulated inside its own method for clarity.</li>

<li>Follows Java coding conventions and includes inline comments.</li>

How to Run:
<ol>
<li>Compile all files:

javac *.java</li>

<li>Run the program:

java Main</li>

<li>Observe the output showing interleaved results from multiple threads.</li></ol>

Requirements:

Java JDK 8 or above

Terminal or IDE (like IntelliJ IDEA or Eclipse)

Author:

Name : Kashvi Singh

PRN : 23070126057

Batch : A3
