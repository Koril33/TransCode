# Translate code in different scene
提供同一场景下的不同语言示例
---

## Motivation
工作和学习中会使用不同的语言，对于不同的场景下，每个语言有不同的规范和技巧，个人比较熟悉 Java 和 Python，其他语言可能并不是场景的最佳实践，仅供参考。

---

## Table of contents
0. [Code convention](https://github.com/Koril33/TransCode/tree/main/CodeConvention) 
1. Basic concept
    1.1 基本数据类型、变量、常量
    1.2 if...else... 分支判断
    1.3 for & while 循环语句
    1.4 函数
    1.5 作用域
2. Collection
    1.1 Array
    1.2 List
    1.3 Map
    1.4 Set
    1.5 Sort
3. IO
4. Time
5. Regex

## Sample
Different "Hello world!"
1. Java
Main.java:
```Java
class Main {
    public static void main(String[] args) {
        System.out.println("Hello world!");
    }
}
```

2. Python
main.py:
```Python
def main():
    print("Hello world!")

if __name__ == "__main__":
    main() 
```

3. C
main.c:
```C
#include <stdio.h>

int main(void) {
    printf("Hello world\n");
    return 0;
}
```

4. JavaScript
main.js
```JavaScript
console.log("Hello world");
```

5. Go
main.go
```Go
package main

import "fmt"

func main() {
    fmt.Println("Hello world")
}
```
