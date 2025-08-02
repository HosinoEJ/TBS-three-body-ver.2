# TBS Three Body ver.2用戶手冊

## 什麽是TBS Three Body?

這是一個來自中國大陸的伺服器，開服於民國111年12月15日。所謂ver. 2是指第二周目。而ver. 1在112年因為玩家數據丟失關閉。在時間的冲刷下，已經完全無法找到那時的檔案了。

##伺服器基本資訊

| 核心數 | 内存 | 存儲 | 地域 | 帶寬 | Minecraft Version | Mods Loader |
|---|---|---|---|---|---|---|
| 2 | 4GiB | 60GB | 新加坡 | 200Mbps | 1.21.6 | Fabric |

## Rule之類的

伺服器沒有嚴格的規則去約束玩家，只要求作為玩家的基本底綫和道德。

## 伺服器位址
Discord：請向Owner傳送[郵件](mailto:hosinoeiji@gmail.com?subject=獲取伺服器ip位址&body=您好，我想加入您的伺服器。)申請伺服器位址。

QQ Group：請直接at群主或者at```@淋淋``` ```@世界拒绝了冤种Sm_mu```

## 客戶端

完全不去安裝任何mod是可以進入伺服器的，但是我建議您使用已經配置好的[整合包](https://github.com/HosinoEJ/TBS-three-body-ver.2/releases/tag/ceach)

## 獨特功能

### MCDReforged

#### 這是什麽

> 這是一個基於 Python 的 Minecraft 伺服端控制工具
>
>>MCDReforged（以下簡稱 MCDR）是一個可以在完全不對 Minecraft 伺服端進行修改的情況下，通過可自訂義的插件系統，提供對伺服端的管理能力的工具
>>
>>小至計算機、高亮玩家、b 站彈幕姬，大至操控記分板、管理結構文件、自助備份回檔，都可以通過 MCDR 及相配套的插件實現
>>
>>非常感謝 chino_desu 以及他的 [MCDaemon 1.0](https://github.com/kafuuchino-desu/MCDaemon) 提出了這樣一個超棒的 Minecraft 伺服端控制工具的點子

#### 功能

1.Beep

@某人，@ all可作用于所有玩家。使用两个@@小心被打
```
@ PlayerName
@@ PlayerName
@ all
```

2.bot
最好用的地毯模组假人管理器！
```
!!bot
```

3.ColorfulID
可以让玩家通过以下命令来选择自己的名字颜色
```
這個得找伺服器owner（臨時）
```

4.G0d of Heads
一个简单的获取任意数量玩家头颅的插件。
```
!!head <玩家X名称> [数量Y]
```
5.gamemode
高级版灵魂出窍(切旁观, 切回生存传送回原位置)
```
!!spec / !s 旁观/生存切换

!!tp <dimension> [position] 传送至指定地点

!!back 返回上个地点
```

6.Hat
提供一个命令```!!hat``` , 允许玩家将手上的物品戴到头上
```
!!hat
```

7.Homo calculator
恶臭数字论证器，使输入的数字变得恶臭。
```
!!homo <int>
```

8.Seed
获取服务器种子，无需手动在配置文件中指定种子，插件可以自动获取
```
!!seed
```

9.tnt roulette plugin
一个基于python随机数的赛博轮盘赌插件
```
!!add 加入/创建一场轮盘赌
!!tnt 开始游戏
!!tnt leave 离开已加入的赌局
!!tnt list 查看已经加入赌局的玩家
!!tnt clear 清除已经加入的玩家（仅mcdreforged admin级权限以上可使用）
```

10.ToDolist
适用于MCDR的ToDoList插件，可查看项目名称、描述、进度及创建者等
![!!td list](https://raw.githubusercontent.com/Flash-Z/MCDR-ToDoList/main/assets/Snipaste_2023-03-19_10-01-20.png)
![!!td tag](https://raw.githubusercontent.com/Flash-Z/MCDR-ToDoList/main/assets/Snipaste_2023-03-19_10-01-54.png)
| 指令 | 用途 |
| - | - |
| !!td | 展示帮助界面 |
| !!td list | 展示ToDo列表 |
| !!td add \<name> (\<detail> \<progress>) | 添加项目,后两项为可选参数 |
| !!td del \<name> | 删除名为\<name>的项目 |
| !!td reload | 重载配置文件 |
| !!td tag | 列出所有tag |
| !!td tag \<tag> | 列出\<tag>下的项目 |
| !!td tag add \<name> \<tag> | 为\<name>项目添加\<tag> |
| !!td tag del \<name> \<tag> | 为\<name>项目删除\<tag> |
注：指令第二项也可只输入首字母，如 !!td list->!!td l

11.urlparser
服务端接收并处理玩家信息，将其中的url单独提取出来发送至服务器聊天栏中，以提供点击即可打开url的功能
