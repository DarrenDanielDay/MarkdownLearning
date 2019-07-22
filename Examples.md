
# Hello, world

> 正如标题所示，这是本人于本站的第一篇博客。
> 接下来会测试一些markdown相关显示效果。

## h2

## h2 copy

### h3

### h3 copy

#### h4

## h2 copy2

### h3 copy2

#### h4 copy

##### h5

###### h6

####### h7(not really h7)

## Highlights

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

## List

1. First ordered list item

2. Another item
    * Unordered sub-list.
    1. Ordered sub-list.

3. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list

4. And another item.  
    Some text that should be aligned with the above item.

* Unordered list can use asterisks
* Unordered list item 2

```note
Unordered list prefix can be '-', '+' and '*'.
But in one document, the prefixes should be the same.
```

## Links

[click me to the top](#Hello,-world)

## [click me to the bottom](#bottom)

[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

URLs and URLs in angle brackets will automatically get turned into links.
<http://www.example.com> or <http://www.example.com> and sometimes
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org

[link text itself]: http://www.reddit.com

[baidu.com]

[baidu.com]: https://baidu.com

<Darren_Daniel_Day@hotmail.com>

## bottom
