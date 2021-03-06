---
layout: post
title: JennyPrinter2 从零开始搭建
category: 开发版本
tags: [jennyprinter , 开发版]
description: JennyPrinter2
---

## 第一章 材料清单(BOM)

### 电路部分

------------

>1		交流插座	  大陆标准	   1	        只
>
>2		220V交流电源线	大陆地区标准	1	根
>
>3		船型开关	10*15	2	只
>
>4		开关电源	12V 360W	1	只
>
>5	    电路板套装	RAMPS1.4	官方版本	1	片
>
>6		Arduino Mega2560	官方版本	1	片
>
>7		A4988+散热片+双面胶带	官方版本	4	片
>
>8		LCD2004SD控制板	官方版本	1	片
>
>9		LCD旋钮	黑色	1	片
>
>10		USB方口转母头		1	根
>
>11		USB双公头		1	根
>
>12		限位开关带线	1长2中	3	只
>
>13		12V电源供电芯线		4	根
>
>14		4cm静音风扇		1	只
>
>15		涡轮风扇	50mm	2	只
>
>16		双绞线		4	米

>18		XY轴电机+接插件	42步进40高度	2	台
>
>19		丝杆电机+螺母	40高度，出轴260mm	1	台
>
>20		E轴电机	42步进60高度	1	台

### 喷头
------------
>21		E3D V5散热器		1	个	31
>
>22		喉管		1	个	6
>
>23		加热铝块	方形	1	个	6.5
>
>24		喷嘴	孔径0.4mm	1	个	10
>
>25		气动接头	内孔3	1	个	1
>
>26		热敏电阻	NTC 100K	1	个	2.8
>
>27		加热管	45W 12V	1	只	10
>
>28		送料管	95cm	1	根	2.5

### 送料
------------
> 29		压力弹簧		1	根	1
>
> 30		手拧螺母		2	个	1
>
> 31		金属电机支架		1	个	3.5
>
> 32		55mm 螺丝		4	只	0.5
>
> 33		凹槽轴承		1	个	2.5
>
> 34		送丝轮		1	个	8
>
> 35		气动接头		1	个	1
>
> 36		M3六角螺母		1	个	0.5
>
> 37		M3*12mm		1	个	0.5

### 机械部分
------------
> 38		十字架X光轴	6*436mm	2	根	23
>
> 39		十字架y光轴	6*296mm	2	根
>
> 40		X导轨光轴	8*465mm	2	根
>
> 41		Y导轨光轴	8*347mm	2	根
>
> 42		Z导轨光轴	12*322mm	2	根
>
> 43		同步轮1	内径8mm	10	个	5
>
> 44		同步轮2	内径5mm	2	个	5
>
> 45		100齿皮带	6.5mm宽	2	根	4
>
> 46		开口皮带	6.5mm	3.5	米	6
>
> 47		滚珠轴承	8*16*5	8	只	1.2
>
> 48		直线轴承		8	只	1.7
>
> 49		法兰轴承		2	只	11
>
> 50		石墨轴承		4	只	6.5
>
> 51		轮滑油		1	若干

### Z平台
------------
> 51		4mm铝底板		1	块
>
> 52		2mm加热板+带热敏		1	块	20
>
> 53		2mm玻璃		1	块	4
>
> 54		压力弹簧		3	根	1
>
> 55		手拧螺母		3	只	1
>
> 56		平头螺丝		3	个	0.5
>
> 57		夹子		4	只	0.5
>
> 57      悬梁臂		2	块

### 接插紧固
------------
> 58		M3*10螺丝	沉头 开口皮带紧固	8	只
>
>  58		M3*10螺丝	圆头	16	只
>
> 59		M3*12螺丝	圆头	16	只
>
> 60		M3*16螺丝	圆头	18	只
>
> 61		M3*25螺丝	圆头	10	只
>
> 61		M3*20螺丝	圆头 LCD紧固	6	只
>
> 62		M3*30螺丝	圆头	14	只
>
> 63		M3*35螺丝	圆头	1	只
>
> 63		M3*55螺丝	圆头	4	只
>
> 64		M3垫片		56	只
>
> 65		M3六角螺母		130	只
>
> 66		M3方片螺母		20	只
>
> 67		M2*14螺丝	圆头	4	只
>
> 67		M2*16螺丝	圆头	2	只
>
> 68		扎带		40	根	0.2
>
> 69		定线片		15	片	0.2
>
> 70		黑色套线管		1.5	米	0.75
>
> 70		M4*20螺丝	内六角	7	只
>
> 70		M4*12螺丝	内六角	4
>
> 70		M4螺母	带法兰	11	只
>
> 70		M3*14	内六角	45	只
>

### 外壳部分
------------
>
> 71	亚克力	前板		1	块
>
> 72		后板		1	块
>
> 73		左板		1	块
>
> 74		右板		1	块
>
> 75		上板		1	块
>
> 76		下板		1	块
>
> 77		送料支架带光轴	光轴6*13MM	1	套
>
> 78		简易卡尺		2	把
>
> 79		XY轴端紧固块		7	块
>
> 80	白色喷塑板	前板	LCD屏幕安装朝右	1	块
>
> 81		后板	限位开关孔朝左	1	块
>
> 82		左板	电机安装孔朝后	1	块
>
> 83		右板	开关位置朝后	1	块
>
> 84		上板		1	块
>
> 85		下板	限位穿孔朝左	1	块
>
> 86		平台挡板		1	块
>
> 87		左电机挡板		1	块
>
> 88		右电机挡板		1	块

### 打印件
------------

> 左滑块		1	个	200
>
> 右滑块		1	个
>
> 前滑块		1	个
>
> 后滑块		1	个
>
> 喷头支架		1	套
>
> XY电机支架		2	只


## 第二章 收集材料及选择参考
------------
###外壳

[外壳切割文件下载](https://github.com/warriorlious/JennyPrinter2/tree/master/Cut_file)

1.亚克力
缺点： 亚克力激光加工工艺导致锥形孔误差、加工燃烧气体有毒有害、太脆，不便搬运

优点：色泽光亮

结论，单用亚克力作为3D打印机外壳华而不实。


2.木板
缺点： 亚克力激光加工工艺要求高，切割功率大烧黑木板影响装配精度、易烂、不美观

优点：有韧性，易装配

结论，单用木板作为3D打印机外壳不华，实用。


3.金属板
缺点： 工艺复杂，表面需处理、笨重


优点：雕刻加工精度高

结论，单用金属板作为3D打印机外壳加重桌面机重量



4.铝合金复合材料

优点：表面光洁无需处理、强度大、重量适中、适应温度范围大


结论，可以作为3D打印机外壳

JennyPrinter2采用木板+金属板 或 亚克力+金属板



###打印件
或称为非标准件，采用打印件价格便宜，强度适中。

[JennyPrinter2打印文件下载]()

切片参考：

填充80%以上，关键受力部件（如挤出机臂，后滑块）采用100%填充以增加强度。

材料选择上，采用高熔点耗材，打印温度略高于耗材熔点，以保证层间的更紧密配合。

####挤出机打印

![挤出机打印放置](https://github.com/warriorlious/JennyPrinter2/blob/master/STL_Print_File/Extruder/Extruder.jpg)



## 第三章 开始装配

###挤出机装配
准备：


- 快接气动头1个
- 凹槽轴承1个
- 打印件2片
- 手拧螺母2只
- 电机支架1只
- 步进电机1台
- 弹簧1只
- 16mm M3螺丝2只
- 25mm M3螺丝3只
- 22mm M3螺丝1只


![挤出机装配完成图](https://raw.githubusercontent.com/warriorlious/JennyPrinter2/master/STL_Print_File/Extruder/%E5%AE%89%E8%A3%85%E5%AE%8C%E6%88%90%E5%9B%BE.jpg)

![安装参考图](https://raw.githubusercontent.com/warriorlious/JennyPrinter2/master/STL_Print_File/Extruder/IMG_20150526_101551.jpg)



## 第四章 手动校准及上电前检查

## 第五章 JennyPrinter固件解析及刷板方法

## 第六章 校准

## 第七章 切片

## 第八章 打印第一个模型

## 第九章 打印模型失败的原因

## 第十章 日常维护

## 第十一章 分享及完善


