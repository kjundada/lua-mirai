# 群成员对象 (MiraiGroupMember)

## 属性

| 属性名 | 类型                                | 描述         |
| ------ | ----------------------------------- | ------------ |
| id     | Integer                             | 群员的qq号码 |
| bot    | [`MiraiBot`](/docs/miraibot.md)     | bot对象      |
| group  | [`MiraiGroup`](/docs/miraigroup.md) | 群员所在群   |

## 方法

### getNick (获取昵称)

#### 返回值：

| 类型   | 描述 |
| ------ | ---- |
| String | 昵称 |

### getNameCard (获取群名片)

#### 返回值：

| 类型   | 描述   |
| ------ | ------ |
| String | 群名片 |


### getMuteRemain (获取被禁言剩余时间)

#### 返回值：

| 类型    | 描述     |
| ------- | -------- |
| Integer | 剩余时间 |


### getSpecialTitle (获取群头衔)

#### 返回值：

| 类型   | 描述   |
| ------ | ------ |
| String | 群头衔 |

### isMuted (判断是否被禁言)

#### 返回值：

| 类型    | 描述       |
| ------- | ---------- |
| Boolean | 是否被禁言 |


### isAdministrator (判断是否为管理员)

#### 返回值：

| 类型    | 描述         |
| ------- | ------------ |
| Boolean | 是否为管理员 |


### isOwner (判断是否为群主)

#### 返回值：

| 类型    | 描述       |
| ------- | ---------- |
| Boolean | 是否为群主 |

### mute (禁言)

#### 参数列表：

| 参数 | 类型    | 描述     |
| ---- | ------- | -------- |
| id   | Integer | 禁言时间 |

### unMute (解除禁言)

### kick (移除群聊)

### isFriend (判断是否为好友)

#### 返回值：

| 类型    | 描述       |
| ------- | ---------- |
| Boolean | 是否为好友 |


### asFriend (转为MiraiFriend对象)

#### 返回值：

| 类型                                  | 描述                    |
| ------------------------------------- | ----------------------- |
| [`MiraiFriend`](/docs/miraifriend.md) | 转换后的MiraiFriend对象 |


### getPermission (获取群员权限)

#### 返回值：

| 类型   | 描述   |
| ------ | ------ |
| String | 权限名 |

### sendMsg (发送私聊消息)

#### 参数列表：

| 参数 | 类型                            | 描述     |
| ---- | ------------------------------- | -------- |
| msg  | [`MiraiMsg`](/docs/miraimsg.md) | 消息对象 |
