
### 这是一个基于UI自动化的微信AI机器人，写的不是很好
## 依赖库
- openai
- uiautomation
- pyautogui
- pyperclip
## 使用步骤
1. 尽量创建虚拟环境
2. pip安装所需的库：
   pip install -r requirements.txt
3. 将你的API网址、密钥等填入11、37行
4. 修改代码中的target_users(92行)列表，以指定哪些联系人的消息将被自动回复。


## PS
- 运行后会在程序目录下生成historys文件夹，存储聊天记录（只有AI和对方说的）。
- 你自己说的话不会被记录。
- 必须保持程序在前台运行。
- 对方快速发消息可能会导致问题（1-2条消息可能会无效）。
