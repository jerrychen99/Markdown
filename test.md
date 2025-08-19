# ***TEST*** (level 1)

-----

## **test** (level 2)

------

>- bullet point

1. 333
2. 3334
   >- inside
3. 323
   
### *Format* (level 3)

|   |1  |2  |
|---|---|---|
|  1|  2|  3|
|  4|  5|  6|

- no
- order
- 123

> block 1
> 
> block 2
> 
> block 3
> 
> block 4

![MyCat](https://github.com/jerrychen99/yolo-food-server/blob/main/1.JPG?raw=true)

[Github](https://github.com/jerrychen99)



# 8/19 进度

-----

## 浏览6项工具概念及作用

>1. Markdown文件格式
>    - 已学习基础语法：'>', '#', 'Format', '>-', '##', '图片插入'......
>    - 编辑工具：VS Code Markdown Preview Enhanced
>    - bash 脚本语言 （平行运算处理调参数有使用过）
>2. git命令行与工具
>```mermaid
>flowchart TD
>
>第一次创建仓库 -->
>A1["cd 到目录"] --> A2["git init"]
>A2 --> A3["git add (file)"]
>A3 --> A4["git commit -m 'explain'"]
>A4 --> A5["git branch -M main"]
>A5 --> A6["git remote add origin (URL)"]
>A6 --> A7["git push -u origin main"]
>
>之后的修改 -->
>B1["git status 查看修改"] --> B2["git add (file)"]
>B2 --> B3["git commit -m 'explain'"]
>B3 --> B4["git log 查看历史"]
>B4 --> B5["git push 推送远程"]
>
>个人-->
>C1["git branch --show-current 查看分支"] --> C2["git remote -v 查看远端"]
>C2 --> C3["git pull 更新本地仓库"]
>
>团队协作-->
>D1["在 GitHub 上 Fork 官方仓库到自己账号"] --> D2["Clone 到本地"]
>D2 --> D3["git fetch 从官方仓库获取更新"]
>D3 --> D4["git pull 将更新整合到本地"]
>D4 --> D5["git add + commit + push 到自己的 fork"]
>D5 --> D6["在 GitHub 提 Pull Request 回官方仓库"]
>```
>    
>3. 基本MIDI协议
>    - 可选择乐器调试音色、力度、持续时间
>    - Note on delta = 0 为立刻发出声音
>    - Note off delta = 480 ticks 为延迟一个四分音符的时间关闭声音
>    - Velocity 为力度可控制声音大小 (0 - 127)
>4. Rtmidi RtAudio库
>    - Rtmidi管理port的连接并接收MIDI指令并发送，RtAudio连接device并且output声音
>5. ImGui库
>    - 只管UI逻辑如button、slider、checkbox需窗口与渲染的合作下才可发挥作用（ex. GLFW创建窗口，OpenGL3画出UI界面）
>6. Mermaid
>    - 能轻易撰写出图表的工具（ex. 流程图、时序图、类图......）

## 规划
```mermaid
timeline
    8/19 : MarkDown : 基本MIDI协议 : git 命令行与工具
    8/20 : RtMidi : RtAudio
    8/21 : ImGui
    8/22 : Mermaid绘制
```