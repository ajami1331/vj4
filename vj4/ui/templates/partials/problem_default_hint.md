
# Hint

## C Code

```c
#include <stdio.h>
int main(void)
{
    int a, b;
    scanf("%d%d", &a, &b);
    printf("%d\n", a + b);
    return 0;
}
```

## C++ Code

```cpp
#include <iostream>
using namespace std;
int main()
{
    int a, b;
    cin >> a >> b;
    cout << a + b << endl;
    return 0;
}
```

## C# Code
```csharp
using System;
using System.Linq;

class Program {
    public static void Main(string[] args) {
        Console.WriteLine(Console.ReadLine().Split().Select(int.Parse).Sum());
    }
}
```

## Python3 Code

```python3
a, b = list(map(int, input().split()))
print(a + b)
```

## Java Code

```java
import java.io.*;
import java.util.Scanner;

public class Main {

    /**
     * @param args
     * @throws IOException 
     */
    public static void main(String[] args) throws IOException {
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        System.out.println(a + b);
    }
}
```

## Ruby Code

```ruby
a, b = gets.split.map(&:to_i)
puts(a + b)
```

# Source
