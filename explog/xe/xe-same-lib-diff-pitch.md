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

#### 第二次实验
1. 用V4 Editor生成一段YANHE的声音（参数见图，未呈现者为默认）
![合成设定](/asset/explog/xe/img009.PNG)

2. 导入Audition CC删除前后空白并标准化
![删空白并标准化](/asset/explog/xe/img010.PNG)

3. 转到频谱图和音高图
![频谱图](/asset/explog/xe/img011.PNG)  
![频谱图12](/asset/explog/xe/img012.PNG)  
![频谱图34](/asset/explog/xe/img013.PNG)  
![音高图](/asset/explog/xe/img014.PNG)

4. 频率分析
频率分析图 线性
![频率分析图 线性](/asset/explog/xe/img015.PNG)
频率分析图 对数
![频率分析图 对数](/asset/explog/xe/img016.PNG)
频率分析图 对数C3
![频率分析图 对数C3](/asset/explog/xe/img017.PNG)
频率分析图 对数D3
![频率分析图 对数D3](/asset/explog/xe/img018.PNG)
频率分析图 对数G3
![频率分析图 对数G3](/asset/explog/xe/img019.PNG)
频率分析图 对数A2
![频率分析图 对数A2](/asset/explog/xe/img020.PNG)
频率分析图 对数C3与G3
![频率分析图 对数C3与G3](/asset/explog/xe/img021.PNG)
频率分析图 对数C3与D3
![频率分析图 对数C3与D3](/asset/explog/xe/img022.PNG)
频率分析图 对数C3与A2
![频率分析图 对数C3与A2](/asset/explog/xe/img023.PNG)

##### 反思与总结
1. 实验的音频跨度不够大，应扩展C2、C4与C5进行合成实验

#### 第三次实验
1. 用V4 Editor生成一段YANHE的声音（参数见图，未呈现者为默认）
![合成设定](/asset/explog/xe/img024.PNG)

2. 导入Audition CC删除前后空白并标准化
![删空白并标准化](/asset/explog/xe/img025.PNG)

3. 转到频谱图
![频谱图](/asset/explog/xe/img026.PNG)  
![频谱图5](/asset/explog/xe/img027.PNG)  

4. 频率分析
频率分析图 线性  
![频率分析图 线性](/asset/explog/xe/img028.PNG)
频率分析图 对数  
![频率分析图 对数](/asset/explog/xe/img029.PNG)
频率分析图 对数C3  
![频率分析图 对数C3](/asset/explog/xe/img017.PNG)
频率分析图 对数C2  
![频率分析图 对数C2](/asset/explog/xe/img031.PNG)
频率分析图 对数C4  
![频率分析图 对数C4](/asset/explog/xe/img032.PNG)
频率分析图 对数C5  
![频率分析图 对数C5](/asset/explog/xe/img033.PNG)
频率分析图 对数C3与C2  
![频率分析图 对数C3与C2](/asset/explog/xe/img030.PNG)
频率分析图 对数C3与C4  
![频率分析图 对数C3与C4](/asset/explog/xe/img034.PNG)
频率分析图 对数C3与C5  
![频率分析图 对数C3与C5](/asset/explog/xe/img035.PNG)
频率分析图 对数C4与C5  
![频率分析图 对数C4与C5](/asset/explog/xe/img036.PNG)

##### 反思与总结
1. 从“频率分析图 对数C3与C2”中可以看出，C2的第一泛音正好落在C3基音位置，第三泛音落在C3的第二泛音位置。从图中来看，C2的波峰每隔一个就会落在C3的波峰上，*但1.4k出不明原因的没有命中*。  
2. 从“频率分析图 对数C3与C4”中可以发现谐波与基波**在频域形状相似**，但越到高频*带宽越窄*（？），且形状损失严重。  
3. 从“频率分析图 对数C4与C5”中的基波形状类似可以推测，这两个音**来自同一个原始采样**。  
4. **到目前为止仍然没有找出共振峰的规律，下次加上清辅音与浊辅音进行实验。**  
5. 可以尝试用手动变调的方式人工制造C5并与真实C5对比。  

#### 第四次实验
1. 用Audition CC将C4移调至C5
![移调后的视图](/asset/explog/xe/img037.PNG)  

2. 频率分析
频率分析图 人工C5（8号）与真实C5（6号）  
![频率分析图 人工C5与真实C5](/asset/explog/xe/img038.PNG)
人工合成的听起来像口琴，而真实的听起来没有什么大毛病.  

##### 反思与总结
1. C5实在是有些高，一般演唱用不到，下次换用C4实验

### 实验结论

### 参考资料
[基音与泛音](http://tieba.baidu.com/p/3552553058)
