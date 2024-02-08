# UE-CCSS R&D Unit Project Standard
## v.1.0.0 (February 8, 2023)
Written by: Chazz C. Manubay [(@chubskie)](https://github.com/chubskie), Term 2023 Team Leader

**Note:** You may follow widely-used professional coding standards for other uncovered aspects of writing code and organizing project files *(we do not need to reinvent the entire wheel)*; however, aspects covered in this standard must be **strictly** followed.

## A. Formatting
* JavaScript codes must use semicolons.
* The general rules and standards for declaring variables, constants, and classes will be followed.
* Indents must be **4 spaces wide**.
* Code must have a line of space between:
  * Blocks of statements *(conditionals, loops, etc.)*
    ```
    if (foo) {
        console.log(bar);
    }
    
    for (baz = 0; baz < 10; baz++) {
        console.log(qux);
    }
    ```
  * Function Declarations
    ```
    function functionOne(a, b, c) {
        return a + b - c;
    }
    
    function functionTwo(i, j, k) {
        return i * j / k;
    }
    ```
  * Comment blocks
    ```
    /**
     * This is an example of
     * a standard multi-line comment.
     */
    
    // This is a single-line comment.
    ```
* Parts of the source code that is not yet finished must contain a comment block indicating a **TODO** and the specifics of that **TODO**.
  ```
  // TODO: Add a function that calculates the remaining space available.
  ```
* Shortcut and ternary operators are allowed. However, you are highly encouraged to explain the functionality of the code that uses it.
  ```
  // Check if user can vote based on age.
   
  age >= 18 ? isVoter = true : isVoter = false;
  ```
## B. File Structure & Organization
* Folder names must be in lower-case and in plural form unless referring to a single entity.
  ```
  /assets
  
  /styles
  
  /pages
  
  /scripts
  ```
* File names must be written in lower-case. Names with multiple words must be separated with hyphens (-).
  ```
  /assets/icons/rnd-logo.png
  ```
* Each project must include a **README.md** file which contains information such as:
    * The project's basic information *(name, version, description)*
    * The date when the project started
    * Third-party involvement *(commissioners, partners, etc.)*
    * Team members who worked on the project including their roles and GitHub profiles.
    * Any disclaimer or important notices to repository viewers.


