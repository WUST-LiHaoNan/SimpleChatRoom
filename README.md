# SimpleChatRoom
<br>基于Socket编程，实现网络聊天室
<br>采用C/S模式，基于TCP协议编程的方式，使得各个用户通过服务器转发实现聊天的功能

<br>分为三大模块：客户端模块、服务器端模块和公共辅助类模块

<br>客户端模块的主要功能：
<br>登陆功能：用户可以注册，然后选择服务器登入聊天室
<br>显示用户：将在线用户显示在列表中
<br>接收信息：能接收其他用户发出的信息
<br>发送信息：能发出用户要发出的信息

<br>服务器端模块的主要功能：
<br>检验登陆信息：检查登陆信息是否正确，并向客户端返回登陆信息，如信息正确。就允许用户登陆
<br>显示在线状态：将该用户的状态发给各在线用户
<br>转发聊天信息：将消息转发给所有在线的用户

<br>公共辅助类模块的主要功能：
<br>定义完整的消息传递机制
<br>对消息转发的方式进行有效约束
<br>规定消息类型

