# dota2-debugger-magpie
操作视频:https://www.bilibili.com/video/BV1Dk4y1T7Kv/
第一个版本肯定问题超级多的 我也没怎么测 
尽量当个玩具的心情来用这个
```json 
    "tstl": {
        "luaTarget": "JIT",
        "sourceMapTraceback": true,
        "luaPlugins": [
            {
                "ip":"192.168.3.17", //你的局域网IP
                "port":32392,  //你的端口
                "include":["/modules"],  //需要参与编译的文件夹
                "name": "../../scripts/tstl/magpie.ts" // magpie插件地址
            }
        ]
    }
```
![47429b7db3b81fcdf6375d0a0ffd76bb](https://github.com/unco999/dota2-debugger-magpie/assets/50286783/7775c684-05bb-4458-bbb5-e6fe9f6d358c)
![image](https://github.com/unco999/dota2-debugger-magpie/assets/50286783/693d65d2-1e52-49ce-a37d-d4222ee94b95)
![image](https://github.com/unco999/dota2-debugger-magpie/assets/50286783/3044cfe3-ab9c-42eb-9d83-608386ddee9c)
![image](https://github.com/unco999/dota2-debugger-magpie/assets/50286783/b1f33469-1e63-497f-911a-65ab3fa8ae0b)

