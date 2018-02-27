## \[XE\] 同一声库不同音高的实验 - 实验日志 - XAS-712的茶楼时光

### 实验目标
搞清在音高变换时哪些部分发生了改变，而哪些没有。

### 实验过程
#### 第一次实验
1. 用V4 Editor生成一段YANHE的声音（参数见图，未呈现者为默认）
![合成设定](/asset/explog/xe/img001.PNG)

2. 导入Audition CC删除前后空白并标准化
![删去前后空白](/asset/explog/xe/img002.PNG)
![标准化](/asset/explog/xe/img003.PNG)

3. 转到频谱图和音高图
![频谱图](/asset/explog/xe/img004.PNG)  
![音高图](/asset/explog/xe/img005.PNG)
![C3的a音频谱图](/asset/explog/xe/img006.PNG)

4. 频率分析
![频率分析图 线性](/asset/explog/xe/img007.PNG)
![频率分析图 对数](/asset/explog/xe/img008.PNG)

##### 反思与总结
1. 未将颤音设为0%，容易对频率分析产生干扰
2. V4编辑器可能做了自动连音处理，导致下一个音并不是独立的


### 实验结论
