# Printing Text

<tldr>

* `Console.WriteLine(<value>);`
* `Console.Write(<value>);`

</tldr>

Printing text is the spine of console programs, since the user can't do anything if you don't tell them anything.
For words, you must put them in quotations.
Numbers don't require them.

Example:
```C#
using System;

Console.WriteLine("text");
Console.Write(10);

-----
Output:
text 10
-----
```

> `using System;` is implicit in the newer versions of Visual Studio.
You won't need to include it.

You can feed a variable into it, or the result of a function, but that is later.