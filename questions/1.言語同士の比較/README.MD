## 1.プログラミング言語同士の比較
<br>

**比較対象**
- Python
- C#
- C++
- JavaScript
<br>

**比較内容**
- 動作に最低限必要なコードとコメント
- 標準出力
- 配列
- 変数の定義
- 関数（メゾット）の定義
- クラスの定義
<br>


### 動作に最低限必要なコードとコメント
Python
```Python
#必要なコードはありません。
#ここに書く 
```
C#
```Csharp
using System;
class Program{
    public static void Main(){
        /*
        ここに書く
        */
    }
}
```
C++
```C++
#include <iostream>
using namespace std;
int main(){
    /*
    ここに書く
    */
}
```
JavaScript
```JavaScript
//必要なコードはありません。
```


### 標準出力
Python
``` Python
print("Hello,World!")
```
C#
```Csharp
Console.WriteLine("Hello,World!");
```
C++
```C++
cout << "Hello,World!" << endl;
```
JavaScript
```JavaScript
console.log("Hello,World!");
```


### 配列
Python
```Python
list = [233,555,123]
```
C#
```csharp
int[] list = new int[3]{ 233, 555, 123};
```
C++
```C++
int list[3] = {222,555,123};
```
JavaScript
```JavaScript
var list = [222,555,123];
```


### 変数定義
Python
```Python
x = 2
s = "あいうえお"
```
C#
```Csharp
int n = 2;
string s = "あいうえお";
```
C++
```C++
int n = 2 ;
char s[] = "あいうえお";
```
JavaScript
```JavaScript
var n = 2;  
let s = "あいうえお";
```

### メゾット（関数）の定義
Python
```Python
def f(x,y):
    return x + y
f(2,4)
```
C#
```Csharp
int f(int x , int y){
    return x + y; 
}
f(2,4);
```
C++
```C++
int f(int x , int y){
    return x + y ;
}
f(2,4);
```
JavaScript
```JavaScript
let f = function(x,y){
    return x + y;
}
f(2,4);
```
