# Tees_GroupProject
小组作业

> ### 各文件夹作用：
> 
> Blueprint文件夹全部丢程序相关的（程序用），Assert文件夹全部丢美术相关的资产，Map里面细分三个文件夹，每个策划各用一个，子文件夹啥的你们先自己来？


> ### 使用指南
> 1.在自己每次打开项目的时候，记得先拉取一下最新项目（Fetch Origin）
> 
> 2.每次推送（Commit to main）的时候写明白自己此次更改干了啥（在Summary中），在群里通知其他成员，
> 
> 3.不要去动除了自己的文件夹以外的其他项目






>### 如果有人要改readme，在此补充markdown常见语法
> 
> 不同级别标题  大概就是#+一个空格 ##+一个空格 ###+一个空格
> 
> **加粗** 两个* 你需要的内容 两个*
> 
> 换行：1.两次回车 2.在行尾在行尾输入”两个空格“然后按”回车“
> 


> # 程序部分使用说明
> >## 附身
> >
> >表现：当面前有可附身物品的时候,按E就可以化身为该物体，再次按E，即可变回女巫
> >
> >### 使用前提条件
> >
> >先把Gamemode里面的控制器改为“BP_SoulController”
> >
> >### 使用指南
> >
> >去/All/Game/ThirdPerson/Blueprints/BP_Actor/BP_SpecialActor里面拖出你需要的物品，检查并确定它细节里的Pawn Class一栏是你需要控制的Pawn（从actor变成对应的pawn）
> >
> >去/All/Game/ThirdPerson/Blueprints/BP_Actor/BP_Pawn中对应该物品的Pawn检查OriginalItemClass是不是绑定的该物品（从pawn变回对应的actor）
> >
> >将物品放在场景中，当操控的角色面前有可附身物品的时候,按E就可以化身为该物体，再次按E，即可变回女巫
> >
