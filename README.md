# ruler
标尺元素，用于利用调节尺度选择身高和体重<br>
<img src="http://www.wware.org/img/rulers.png" width="400px"><br>
普通属性<br>
data-rulerid	每个元素必须设置一个属于自己的id值，不能重复使用	ruler<br>
data-rulermax	刻度尺最大的刻度(非必须，默认为1000)	1000<br>
data-minunit	刻度尺最小刻度(非必须，默认为1)	0.1<br>
data-unitset	刻度尺单元长度(非必须，默认是10)	10<br>
data-rulervalue	刻度尺初始化数值(非必须，默认为1)	1<br>
data-mult	刻度值倍数，默认是最小刻度值为10px，如果定mult为3则最小刻度为30px(非必须，默认为1)	1<br>
data-rulermin	刻度尺最小的刻度(非必须，默认为50)	50<br>
输出属性<br>
data-x-rulerdata	输出选中的数值	50<br>

# 注意事项
1、如果想显示0.1这样的数值，就设置 data-minunit 属性值为0.1（刻度尺最小刻度）
2、标尺上的刻度元素可以任意修改
