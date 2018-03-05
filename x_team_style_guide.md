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
public <Class name>{
 }
* fields
* constructors
* methods
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements
  * switch statement
  * while loops
  * for loops
  * enhanced for loops
