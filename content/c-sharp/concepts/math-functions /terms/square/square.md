Title: '.sqrt()'
Description: 'returns the square root of the number given.'

Subject:
  - 'Computer science'
  - 'Code foundation'

Tags:
  - 'Method'
  - 'Arithmetic'
  - 'Numbers'
  - 'Functions'
Catalogcontent:
  - 'learn-C-Sharp'
  - 'paths/Computer-science'
  ---

  The  **`Math.Sqrt()`** --Class method returns the square root of the number given.

  ## Syntax

```pseudo
Math.sqrt(x);
```

The `Math.sqrt()` The method takes only one parameter, the variable `x`, of type `double`. The function will return a positive value of type `double `unless the value passed is one of the following:

--- If `x` is `negative,` the function will return `NaN (not a number)`.
--- If `x` is` NaN,` the function will return `NaN.`
--- If `x` is `PositiveInfinity,` the function will return `PositiveInfinity.`

## Example

The following example demonstrates the `Math.Sqrt()` method. Four different values are passed to the method, and the return values are printed with the `Console.WriteLine()` method.

```cs
using System;

namespace MySquareRoot {
  public class Example {
    public static void Main(string[] args) {
      double a = Math.Sqrt(256);
      double b = Math.Sqrt(-256);
      double c = Math.Sqrt(500);
      double d = Math.Sqrt(0.144);

      Console.WriteLine(a);
      Console.WriteLine(b);
      Console.WriteLine(c);
      Console.WriteLine(d);
    }
  }
}
```

The example will result to the following output:

```shell
16
NaN
22.3606797749979
0.379473319220205
```

## Codebyte Example

The following example is runnable and uses the `Math.Sqrt()` method to return a double type value of the square root of `100`:

```codebyte/csharp
using System;

public class Example {
  public static void Main() {
    double number = 100;
    double squareRoot = Math.Sqrt(number);

    Console.WriteLine("The square root of " + number + " is " + squareRoot);
  }
}
```
