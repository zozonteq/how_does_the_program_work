# アセンブラ
## 環境
```
OS:Ubuntu 20.04
CC:g++
CPU:x86
```
## 解ったこと
例)
```asm
.intel_syntax noprefix
.globl main
main:
;メイン関数
    mov rax,255

```
255を返すコード。終了コードはraxに入る。

