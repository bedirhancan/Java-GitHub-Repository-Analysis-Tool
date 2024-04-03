# Java-GitHub-Repository-Analysis-Tool
=======================================

This project comprises a console application in Java designed to analyze a GitHub repository URL provided by the user.

Features
--------

* Performs cloning operation on the GitHub repository URL provided by the user.
* Retrieves *.java extension files from the cloned repository.
* Extracts files containing only classes.
* Conducts the following analysis for each class:
    * Number of Javadoc comment lines
    * Number of other comment lines
    * Number of code lines (excluding all comment and blank lines)
    * LOC (Line of Code) (total number of lines including everything in a file)
    * Function count (total number of functions contained within the class)
    * Comment Deviation Percentage (percentage deviation of required comment lines)
