# exp-win-clipboard-hack
WindowsのクリップボードをNode.js + HSP3でハックする

## 考えてること
1. HSP の user32 などを使ってクリップボードの`Format ID`を指定したらそれに合致したテキストが吐き出されるコマンド exe を作る
2. Node.js の child_process から cmd を呼び出して、返ってくる値を読み取る
