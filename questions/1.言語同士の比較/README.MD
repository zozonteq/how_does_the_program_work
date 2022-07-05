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

## Python
オブジェクト指向インタープリター言語  
動的型付け  
処理速度が遅い。  
簡単  
幅広く使われる。　　
[Wiki Pedia](https://ja.m.wikipedia.org/wiki/Python "WikiPedia")
## C#
オブジェクト指向コンパイル言語  
静的型付け  
Windowsと相性が良い　　
コンパイル必要
[Wiki Pedia](https://ja.m.wikipedia.org/wiki/C_Sharp "WikiPedia")
## C++
オブジェクト指向コンパイル言語  
静的型付け  
処理速度が速い。  
機械語に近い  
C言語の上位互換  
コンパイルが必要
[Wiki Pedia](https://ja.m.wikipedia.org/wiki/C%2B%2B "WikiPedia")
## JavaScript
オブジェクト指向スクリプト言語  
動的型付け  
主にWeb系で使われる。  
ブラウザで動く  
[WikiPedia](https://ja.m.wikipedia.org/wiki/JavaScript "WikiPedia")
## Java
オブジェクト指向  
JVM上で動く  
クロスプラットフォーム  
コンパイル必要
### 動作に最低限必要なコードとコメント
Python
```Python
#直接かける
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
//直接かける
```
PythonやJavaScriptは直接書ける、C#とC++はごにょごにょ書かないといけない。
コンパイラ言語は大抵ごにょごにょ書く雰囲気  
pythonとjsは行末に;がいらない。

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
std::cout << "Hello,World!" << std::endl;
```
JavaScript
```JavaScript
console.log("Hello,World!");
```
C#,Python,JavaScriptはメゾットで出力している。C++はシフト演算。

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
Python,JavaScriptは少ないコードでかける。


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
C#とC++は静的型付けだがPythonとJavaScriptは動的型付け。
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
C#とC++はほとんど同じ。  
Phthonとjsは戻り値の型を指定しなくていい。



### クラス定義
Python
```Python
class Human:
   def  __init__(name,age):
      self.name=name
      self.age=age
      
Tomas = Human("Tomas",22)
```
C#
```Csharp
class Human{
    string name = "Tom";
    int age = 0 ;
    public Human(string name,int age){
        this.name = name;
        this.age = age;
    }
}
//---------------------------------
Human tomas = new Human("Tomas",22);
```
C++
```C++
class Human{
    public:
        string name="";
        int age = 0 ;
        Human(string name , int age);  
};
Human::Human(string name,int age){
    this->name = name;
    this->age = age;
}
//---------------------------------
Human tomas("Tomas",22);
```
JavaScript
```JavaScript
const Human = class{
    constructor(name,age){
        this.name = name;
        this.age = age;
    }
}
let tomas = new Human("Tomas",22);
```

PythonとJavaScriptが似てる。
C++が他の言語と似ていない。

## まとめ
スクリプト言語同士、コンパイル言語同士はそれぞれ似ている所が多い。
## 思った
自作言語作るんだったら、トランスパイルが現実的だと思った。アセンブラだとアーキテクチャのことも考えないといけないし、今までのライブラリと互換性がないから、それに相当するものを自作しないと。。
