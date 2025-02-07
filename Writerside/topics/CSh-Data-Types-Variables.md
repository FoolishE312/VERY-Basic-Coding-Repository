# Data Types &amp; Variables

<tldr>

* Each variable needs an explicit type
* Conversions need to be done between types
* Names are required

</tldr>

## Types

Variables are for storing information, and each one has something called a Data Type.
The basic list of them are below.

`int`
: Stores a whole number that cannot contain a decimal.

`float`
: Stores a number that can contain a decimal.

`string`
: Stores a set of words, within quotations.

`char`
: Stores a single character.

`bool`
: Stores a true or false value.

`ConsoleKeyInfo`
: Stores a key press (explained later in User Input)

Here's a simple example of a variable:

```C#
int test = 3; //valid
bool test = true; //invalid - variables cannot share names
ConsoleKeyInfo test3; //valid
string text; //valid
```

## Usage

To define a variable is to include the data type, the name, and the starting value if you so choose.
Changing a variable's value is a matter of just the name and the value.

So, a definition of `int a = 5;` could change to 7 if you just do `a = 7;`.

> Don't define variables inside of methods that you want to use outside of it.
If you want a variable to use anywhere, define it outside of the method.
{style="warning"}

## Conversions
A string cannot convert into a variable and vice-versa, at least not implicitly.
In User Input, this becomes much more useful, but here's the situation:

You have a string, `"7"`, and you want it as an integer.
C# isn't smart enough to automatically convert, so you need to do `Convert.ToInt32("7");`.
Most other data types have their own conversions.