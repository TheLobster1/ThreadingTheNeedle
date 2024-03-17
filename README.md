# Extreme File Finder - C# .NET MAUI

## Introduction

Extreme File Finder is an application used for finding files on your system using multiple threads. It will look through specified folders or all folders.


### About the developers

This application is being developed part of the course "Threading in C#" at NHL Stenden University of Applied Sciences.

Below you can find the team members:

|        Name        |
|:------------------:|
|    Rob Veldman     |
|    Roy Stobbe      |
|  Andrei Khoudiakov |

## Description

The program will let users search for files, making use of threading.

*General specifications:*

* .NET MAUI
* MVVM
* Threading

### Class Diagram

![C# threading diagram](https://github.com/TheLobster1/ThreadingTheNeedle/assets/112638712/a261bcc0-005a-4a00-90fd-c1f92f290133)

### MoSCoW analysis

| Priority | Task |
| --- | --- |
| Must have | File searching on name and / or file type, Reading the text in the file, History of past successful searches|
| Should have | Show sizes of folders, Button to copy file path, Hidden files being visible, show extensions of files|
| Could have | Wildcard searches, Queue for searching |
| Won't have | GUI navigation|

## Input & Output

*The section below is yet to be updated*

### Input

|        Case         |   Type   | Conditions |
|:-------------------:|:--------:|:----------:|
| Example exampleName | `String` | not empty  |

### Output

|  Case   |   Type   |
|:-------:|:--------:|
| Example | `String` |

### Calculations

|  Case   |    Calculation    |
|:-------:|:-----------------:|
| Example | `Example*Example` |

### Remarks

* Input will be validated

## Test Plan

In this section the testcases will be described to test the application.

### **Test Data**

In the following table you'll find all the data that is needed for testing.

### Test Cases

In this section the test cases will be described. Every test case should be executed with the test data as starting
point.

#### Test Case 1

Description: Testing input validation.

| Step | Input |        Action         |              Expected Output              |
|:----:|:-----:|:---------------------:|:-----------------------------------------:|
|  1   |       | setExample("Example") |                 `Example`                 |
|  2   |       |   setExample(null)    |                   null                    |
|  3   |       |    setExample(" ")    | `Example must be at least 2 letters long` |


