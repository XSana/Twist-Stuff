TST 任务书

使用 DeepSeek 机翻版本，目前没有人工校对，你可以 fork 这个仓库创建自己的翻译或者，提交你觉得有问题的翻译到这里

使用方法

将 zh_CH.lang 内容最追加到./config/txloader/load/betterquesting/lang/zh_CN.lang 文件末尾，注意是追加不要覆盖，然后重启游戏即可，如果翻译未变化，可以输入 /bq_admin default load 重新加载任务书

# Twist-Stuff

My Twist Space Repo - QBs &amp; Info

Instructions for how to download the Twist Questbook using the Easy Way:

The DefaultQuests is the entire QuestBook from GTNH, including a chapter on Twist that I made.

To add it to your pack:

First, click the blue `<> CODE` button and download the ZIP

1. Go to configs
2. Navigate to the betterquesting folder
3. DELETE the "DefaultQuests" folder.
4. Download the "DefaultQuests" Folder that exists on this repository
5. Copy it to the betterquesting folder; this will add the Twist Quest Page
6. Go in-game and type the command `/bq_admin default load` (YOU DO NOT NEED OP FOR THIS), this will load the questbook with all the Twist Quests added. Because quests are saved world side, you will not lose any progress with your current quests, but please contact Aditya if you run into any troubles

To install it the Hard Way (manually, not recommended):

1. Download all the folders separately so as not to get confused, including the QuestLinesOrder.txt
2. Copy the Twist Space Technology Folder in the QuestLines folder from this repository to the `QuestLines` folder in the `DefaultQuests` Folder.
3. Copy the Twist Space Technology Folder in the Quests folder from this repository to the `Quests` folder in the `DefaultQuests` Folder.
4. Replace the `QuestLinesOrder.txt` in your INSTANCE folder with the one you downloaded from this repository.

Reload the QuestBook after using the default load command. This should work, but please don't hesitate to contact me in my Discord or the Twist Discord if you have any questions.
