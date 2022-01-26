# YGO-MasterDuel-Translator-GUI
GUI for various YGO MD Python translating tools

# 使用方法
1.编辑search_engine.py, 在其中载入你需要的python翻译工具及功能
2.建立pics文件夹，在其中放入你想要的卡图（我是直接从ygopro里拷过来。无卡图也可以用，只会显示卡名。
3.运行gui.py

# GUI设置方法
修改 config.py
字号和字体
```
FRONT_SIZE = 15
FRONT = '微软雅黑'
```
无翻译结果时默认卡图，你也可以改为"卡背"，然后另外加入你想要的卡背.jpg.
```
DEFAULT_PIC = "10000"
```

窗口宽度，可以根据你所用卡图文件宽度来修改，一般高清卡图是400像素
```
WINDOW_WIDTH = 400
```
窗口更新间隔，默认每100毫秒（0.1秒）检查一次翻译结果，结果有变化就更新卡图和描述
```
UPDATE_INTERVAL = 100
```


# 载入翻译工具
编辑search_engine.py, 在其中载入你需要的python翻译工具及功能就行了

