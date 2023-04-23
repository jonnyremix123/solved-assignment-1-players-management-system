Download Link: https://assignmentchef.com/product/solved-assignment-1-players-management-system
<br>
<p class="ui header product-top-header" title=" Assignment 1: Players Management System Solution"> Assignment 1: Players Management System

1. Overview

This assignment aims to establish a basic familiarity with the JDK development system and its associated on-line Java API class documentation. Students should apply the appropriate fundamental programming concepts (such as variables, constants, arrays, strings, methods, selection and repetition constructs etc.) and make use of appropriate Java API classes (such as Scanner, PrintWriter, String etc.) that they have learnt to solve the given problem.

2. Objectives

On completion of this assignment a student should be able to write simple Java application

that:

• Makes use of selection and repetition constructs to achieve desired outcomes

• Stores data to and reads data from arrays

• Generates output to and reads input from the console window

• Reads data from and writes data to text file

• Manipulates string using Java API “String” class

• Handles basic errors

• Applies object-oriented concepts

3. Scope

This assignment is based on individual effort. You are required to design, develop and test a user accounts management system for a game application.

Besides providing the required functionalities, your program should incorporate appropriate error handling. Comments are also to be inserted to improve program clarity. Before you start coding your program, you are strongly advised to carry out proper problem analysis and program design.  You are required to use JDK 1.5 developer version or later.

4. Requirements

This application allows the admin to

1.    Admin Login

2.    Create a player

3.    Delete a player

4.    Edit a player information

5.    Export players information

6.    Change admin password

7.    Logout

This application will have access to two text files.

The first text file (admin.dat) contains the administrator-hashed password (SHA-256).

For example

be4b826c27636ab54a8bf15d73fc1bf2a533f547f2343d12a499d45643453ad4

The second text file (players.dat) contains the player’s information in the following format

&lt;Login Name|&lt;password in SHA-256|&lt;Chips|&lt;Name|&lt;Email|&lt;Birthdate

The Birthdate is in YYYY-MM-DD format

For example

BlackRanger|21a57f2fe765e1ae4a8bf15d73fc1bf2a533f547f2343d12a499d45643453ad4|10|Jason Tan|<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="2c66786c6f7f6f651e1d1f024f4341">[email protected]</a>|2000-1-18BlueKnight|e765e4456e4f1ae4ae8bf15d73f435535e4a56f441f2556315a23646473e3454|15|Mary Tey|<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="98d5ccd8dbcbdbd1aaa9abb6fbf7f5">[email protected]</a>|1999-2-22IcePeak|343a4d56b453c76e5e1ae54a8bf15d73fc1bf2a533f547f2343d19c0592044d4|10|Peter Loh|<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="d38387939080909ae1e2e0fdb0bcbe">[email protected]</a>|1998-1-9GoldDigger|bf2a536446464643e32335b3eddff2233433f547f2343d12a49343345ab53c4d|22|Zack Toh|<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="c49e90848797878df6f5f7eaa7aba9">[email protected]</a>|2001-3-8

Error Handling

Your program should be able to handle error situations. For example where a player login name already existed (for Create a player) or player login name not found (for delete player). You should look out for other possible exceptions and handle them too.

For Export players information requirement, the program should produce a file (playersData.dat) with the following format:

CSCI213 Players Management System

Player 1

Name: Jason Tan

Email:  <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="fcb6a8bcbfafbfb5cecdcfd29f9391">[email protected]</a>

Birthdate: 2000-1-18

Login Id : BlackRanger

Balance Chips:10

Player 2

Name: Mary Tey

Email:  <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="8cc1d8cccfdfcfc5bebdbfa2efe3e1">[email protected]</a>

Birthdate: 1999-2-22

Login Id : BlueKnight

<strong>//Code Only no report</strong>

5/5 - (3 votes)