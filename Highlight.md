# Highlights

## simple example

This is _leaning text_.\
This is also *leaning text*.\
This is **bold text**.\
This is also __bold text__.\
This is ~~deleted text~~.\
`colored highlighted text`

## Code

### C

```c
// A simple line note.
/**
 * multi-line note.
 * @author Darren_Daniel_Day
 */
#include <stdio.h>
#include <stdlib.h>
int main(){
    puts("Hello, world!");
    return 0;
}
```

### C\#

```csharp
// A simple line note.
/**
 * multi-line note.
 * @author Darren_Daniel_Day
 */
using System;
public class Helloworld{
    public static void Main(){
#if DEBUG
        Console.Writeline("In debug mode...");
#endif
        Console.Writeline("Hello, world!");
    }
}
```

### Java

```java
// A simple line note.
/**
 * multi-line note.
 * @author Darren_Daniel_Day
 * @version 0.0.1
 */
public class Helloworld
{
    public static void main(String[] args) {
        System.out.println(new Helloworld());
    }

    /**
      * @returns "Hello, world!"
      */
    @Override
    public String toString() {
        return "Hello, world!";
    }
}
```

### Python

```python
class Helloworld:
    def __init__(self):
        print("Helloworld.__init__()")
        f("world")
        f("world")

def EchoIt(obj):
    print("EchoIt init.")
    return obj

@EchoIt
def f(s:str)->int:
    '''Simple function.'''
    print("Hello, {}!".format(s))
    return 0

# Simple note.
Helloworld()
```

### Typescript

```typescript
let world:str = "world";
console.log(`Hello, ${world}!`);
```

### JavaScript

```js
console.log("Hello, world!");
```

### HTML5

```html
<!--some note-->
<html>
    <h1>Hello, world</h1>
    <script>
        alert("Hello, world!")
    <script>
</html>
```

### Text

```text
Hello, world!
```

> one line quote.

Random text to divide quotes.

> Blocked quote.\
> line2.
> also line 2.
>> quote in quote\
>> line2
>>>> skipped qoute
>>>>>>>> inner

Random text to divide quotes.

> ___~~[in quote link with style supported.](https://www.google.com)~~___
