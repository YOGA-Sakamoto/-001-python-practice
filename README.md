# 001-python-practice

## Date
25/09/28
### Q
PracticeA - Welcome to AtCoder
### A
a = int(input())
b, c = map(int, input().split())
s = input()
total = a + b + c
print(total, s)
### Tips
- input(): 1行分の文字列を受け取る関数
- int(): 文字列を整数に変換する関数
- split(): 文字列をスペースで区切って、リストにする関数
- map(int,・・・): リストの各要素すべてにint()を適用し、整数に変換する関数
