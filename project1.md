[Back to Portfolio](./)

Student ID Map
===============

-   **Class: CSCI 315** 
-   **Grade: 100.00**
-   **Language(s): C++**
-   **Source Code Repository:** [Epowell50/Data_Structures_Project](https://github.com/Epowell50/Epowell50-Data_Strucutres_Project)  
    (Please [email me](mailto:erpowell@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

This project is a data structure designed to map student names with their respective ID numbers. This project has the following functions:
* Add a student
    * This function adds a student to the strucuture.
* Delete a student
    * This function removes a student from the structure.
* Retirieve a student
    * This funcytion retirieves the student ID when given the respective name.
* How many
    * This function displays the number of students with the given prefix.

## How to compiles / run the program

How to compile (if applicable) and run the project.

```bash
cd /project
g++ map.cpp map.hpp main.cpp -o Run.exe
```

## UI Design

Since the program is built around a data structure and not a user interface, the interface is very simple. This program was meant to stress the use of a data structure to effectively store a large amount of data and consistently have a quick acess time. While in operation, the structure will have the add, remove, howMany, and get function. These functions are shown below and can be referenced in figure 1. First is the add function. The add function adds the name to the data structure with the given ID. The get function is then called to retrive the specific ID of the given name, returning 1 as the name exists. The next function removes the name from the structure, although keeping the allocated lists. Lastly, we try to remove a name that does not exist in the structure. This results in a return value of 0, being false, to show that the name was unsuccessfully removed.

![screenshot](images/Map_Project.JPG)
Fig 1. The data structure in action

## 3. Additional Considerations

This project was made to stress test making a map structure from the ground up. This structure has a log27(n) search and delete time, making it very efficient for storing large amounts of IDs. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
