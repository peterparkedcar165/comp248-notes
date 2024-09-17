# COMP248 Notes

### September 11th 2024
#### Lecture 2:

#### Revision of last class:
###### All keywords are lowercase
###### Whatever { must end with a }
###### When identifying a variable, it is preferrable to use a term that is relevant or related to whatever the variable is.

##### To define a new class:

public class NameOfTheClass { // The only thing I change is the name of the class.

public static void main(string[] args) { // args is the only thing i can change. the brackets can be found after string or after arg, both work but preferable after string.

  }
}

#### Way to comments:

//              << single line

/*     */       << as many lines as desired

/**    */       << for a purpose, .javadoc



#### Identifiers:

Can only identify one thing, no ambiguity. Ex: what if you're two guys w the same name, its ambiguous, confusing.

Identifier may contain: A-Z | a-z | digit | $

Cannot start with digit

Cannot have space

If identifier happens to have many words, first character may be capitalized. class names only.

constants must be uppercased

variables, like in c++, likeThis

#### EXAMPLES OF IDENTIFIERS:

GST -- YES

PriceBeforeTax -- YES

Student_3 -- YES

#### Methods:

method should contain a verb

______________

#### Indentation:

Good or bad indentation will dictate whether your program is easily readable or not.

#### Data Types in Java:

##### There are 8 data types.

Numeric: 4 integers ---- byte, short, int, long. (ex: 2-3-4-5-6-7) - Analogy: datatype are like containers, and youre going to pick the best fitting size whatever you want to store. You wouldn't use a huge cauldron to hold a bowl-worthy of pasta. The fridge is your computer, will it fit?
         2 floating point numbers ---- float, double. (ex: 2.2-3.2-5.2-etc.)

Characters: 1 char ---- a, b, c ,d ,e

Boolean: boolean --- true/false

1 byte = 8 bit

boolean -> 1 byte

char -> 2 bytes

byte -> 1 byte

short -> 2 bytes

int -> 4 bytes

long -> 8 bytes


##### Variables:

Must be declared before it is used.

ex:

int total; //Data type, then variable identifier --

Just like in C++, multiple variables of the same type can be declared at once.

int total, count, temp, result;



# September 16th:
