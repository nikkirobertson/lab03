# lab03

## What do you think is the type of each of the following fields? 
* private int count; 
* int
* private Student representative; 
* student
* private Server host; 
* server

## What are the names of the following fields? 
* private boolean alive; 
* alive
* private Person tutor;
* tutor 
* private Game game; 
* game

## From what you know about the naming conventions for classes, which of the type names in the above questions would you say are class names? 
Person, Game, Student, Server. 

## In the following field declaration from the `TicketMachine` class  
```
private int price;
```
does it matter which order the three words appear in? Edit the TicketMachine class to try different orderings. After each change, close the editor. Does the appearance of the class diagram after each change give you a clue as to whether or not other orderings are possible? Check by pressing the Compile button to see if there is an error message. Make sure that you reinstate the original version after your experiments! 

when I put int private price; not able to compile. says <identifier> expected. does matter the order in which the three words appear. 


## Is it always necessary to have a semicolon at the end of a field declaration? Once again, experiment via the editor. The rule you will learn here is an important one, so be sure to remember it. 

editor says ";" expected. cannot compile. yes it is necessary 

## Write in full the declaration for a field of type `int` whose name is `status`.

private int status
## To what class does the following constructor belong?
```
public Student(String name)
```
class Student
## How many parameters does the following constructor have, and what are their types?
```
public Book(String title, double price)
```
two parameters, string and double
## Can you guess what types some of the `Book` class’s fields might be, from the parameters in its constructor? Can you assume anything about the names of its fields?

The object is a book with a title that is a string and has a price containing  decimals.

## Suppose that the class `Pet` has a field called `name` that is of the type `String`. Write an assignment statement in the body of the following constructor so that the `name` field will be initialized with the value of the constructor’s parameter.
```
public Pet(String petsName)
{ 
name= petsName;
}
```
## The following object creation will result in the constructor of the `Date` class being called. Can you write the constructor’s header?
```
new Date("March", 23, 1861)
public Date (String month, int date, int year)
```
Try to give meaningful names to the parameters.
