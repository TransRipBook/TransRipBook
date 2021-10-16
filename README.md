# TransRipBook
以部分机器可读的形式为离世的孩子们建立纪念碑。

## 编辑指南

### 索引 - index.json

格式如下。

```json
{
    "_comment": "一切涉及到本人的真实信息需本人生前同意才可收录。",
    "name": "虚拟身份用户名或真名（真名需本人生前同意才可记录）",
    "description": "关于TA生平数句话的简介",
    "age": "年龄",
    "date_of_born": "出生日期（Unix时间戳）",
    "date_of_death": "去世时间（Unix时间戳）",
    "contacts": {
        "qq": "QQ号",
        "wechat": "微信号",
        "twitter": "Twitter ID",
        "weibo": "微博账号",
        "zhihu": "知乎账号",
        "bilibili": "bilibili UID",
        "github": "GitHub ID",
        "_comment": "本项可以完全为空。"
    },
    "links": [
        {
            "name": "本人生前博客等相关站点。",
            "url": "http://blogspot.com",
            "_comment": "本项可以完全为空。"
        }
    ]
}
```

### 更多信息 - Folder {name}

保存相关更多信息，请建立与json中name同名文件夹，并自由放置内容于其中。

必须放置于其中的内容:

- description.md - 更详细的生平简介。

## 还是不会编辑？

请于 Issue 中提出自己想记录于纪念碑上的人。提供足够的信息并等待他人完成编辑工作。

## 本纪念碑中内容可能会在未来被用作 CI 自动生成静态纪念站点。周知。
