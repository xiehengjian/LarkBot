## 安装

```shell
$ pip3 install LarkBot
```

## 使用

### 初始化

```python
from LarkBot import LarkBot
bot=LarkBot.Bot(AppID=<AppID>,AppSecret=<AppSecret>)
```

### ID

#### 获取用户ID

```python
bot.userId(emails=<emails>)
```

#### 获取群组ID

```python
bot.groupId(name=<name>)
```

### 消息

#### 发送文本消息

```python
bot.textMessage(open_id=<open_id>,text=<text>)
```

#### 发送图片消息

```python
bot.imageMessage(open_id=<open_id>,image_path=<image_path>)
```

