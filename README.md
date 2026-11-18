Assignment 4 – CO4: Event-Driven GUI Design
Student Name: P.V.BHANU PRAKASH Register Number: 192411105 Course: Programming in Java (CSA09)
Course Outcome: CO4
Java Version: OpenJDK 17.0.21.0.2 LTS

📌 Overview
This assignment assesses the design, architecture, and implementation of event-driven graphical user interfaces using Java AWT and Swing. Key areas include decoupling presentation from business logic, nested layout managers, event delegation model, adapter classes, listener implementation styles, UI thread responsiveness with SwingWorker, and JDBC database integration.

📁 Directory Structure
Assignment4/
├── Task01/   # GUI Design Review & Layer Separation (Fee Payment Window)
│   └── FeePaymentApp.java
├── Task02/   # Event Modeling & Containment Tree (Hospital Outpatient Desk)
│   └── OutpatientDeskApp.java
├── Task03/   # Nested Layout Managers & Resizing (Campus Library Catalog)
│   └── LibrarySearchScreen.java
├── Task04/   # Event Forensics & Repaint Persistence (DrawPad)
│   └── DrawPad.java
├── Task05/   # Comparative Study of 4 Event-Handling Styles (Currency Converter)
│   ├── Converter.java
│   └── ConverterStylesDemo.java
└── Task06/   # Layered Swing-JDBC Desktop App & Design Challenge
    ├── EventRegistrationApp.java
    └── schema.sql
🚀 Compilation and Execution Instructions
From the Assignment4 directory:

# Task 1: Fee Payment Design Review
javac Task01/FeePaymentApp.java
java Task01.FeePaymentApp

# Task 2: Outpatient Desk Appointment GUI
javac Task02/OutpatientDeskApp.java
java Task02.OutpatientDeskApp

# Task 3: Library Search Nested Layouts
javac Task03/LibrarySearchScreen.java
java Task03.LibrarySearchScreen

# Task 4: DrawPad Event Forensics
javac Task04/DrawPad.java
java Task04.DrawPad

# Task 5: Currency Converter Event Styles
javac Task05/Converter.java Task05/ConverterStylesDemo.java
java Task05.Converter
java Task05.ConverterStylesDemo

# Task 6: Event Registration Desktop Application (Swing + JDBC)
javac Task06/EventRegistrationApp.java
java Task06.EventRegistrationApp
