# 从"Hello World"开始编程之旅 😘

> - 目标：在控制台终端显示文字"Hello World"

> 示例代码

```clike
#include <iostream>

using namespace std;
int main(){
    cout << "Hello World!";
    return 0;
}
```

## 代码解释

在运行 C++ 程序时，通常从`main()`函数开始执行。因此，C++ 程序必须包含一个名为 `main()` 的函数。在 `main()` 多维函数中我们执行了唯一的语句：

```clike
cout << "Hello World!";
```

该语句将"Hello World!"打印在屏幕上。

以下是该程序的其他语法及解释：

|         语法         |                                   解释                                    |
| :------------------: | :-----------------------------------------------------------------------: |
| #include\<iostream\> |        意思是引入 iostream 库，即输入输出流库。([关于#include]())         |
| using namespace std  | 使用`std`命名空间，`namespace`是一个 C++中的一个关键字([关于 namespace]()) |
|     int main(){}     |                              主函数默认写法                               |
|       cout <<        |             输出流，可以将内容打印在屏幕上([关于 iostream]())             |
|    "Hello World!"    |                                字符串常量                                 |
|      return 0;       |           主函数的返回类型为`int`，所以返回一个`int`型(`return 0`)           |
