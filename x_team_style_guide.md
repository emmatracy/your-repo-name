# X-Team 271 Style Guide 

Least confusing and most descriptive as possible for teammates to interpret.

## Naming conventions

Primarily focused on readability and consistency.

### Examples
* interfaces
```
public interface NameOfInterface
```
* classes
```
private class NameOfClass
```
* exception types
```
class NameOfException extends Exception
```
* fields
```
private int lowerCamelCase
```
* methods
```
private void nameOfMethod() 
```
* parameters
```
(int nameOfParam, T genericParamName)
```
* local variables
```
int localVariable;
```
* instance constants
```
int CONSTANT_NAME;
```
* class constants
```
static List LIST_CONSTANT;
```

## Commenting style for public and private members of a class or interface:

JavaDoc for all classes. JavaDoc when necessary for methods (if the method's functionality is not intuitively
obvious from method name/params/usage). In-line comments as necessary to explain specific algorithm steps.

### Examples

* classes
```
//This class is an AVL search tree implementing the BalancedSearchTree interface
public class AVLTree() implements BalancedSearchTree
```
* fields
```
In-line as necessary
Node root //The tree's root
```
* constructors
```
//Initializes a new AVLTree
//@param root is a Node that will serve as the tree's root
public void AVLTree(Node root)
```

* methods
```
/*
     * This method returns the value in the parameter
     * @param value - the value passed as the parameter
     * @return value - return the value passed into the parameter
     */
```
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  * switch statement
     ```
     int num = 2;
     switch (num) {
        case 1:
           System.out.println("");
           break;
        case 2: 
           System.out.println("");
           break;
        default:
           System.out.println("");
      }
      ```  
  * while loops
  * for loops
  * enhanced for loops
