# CORDIC算法之直角坐标求反正切角
#### 代码介绍
    通过逐次逼近至纵轴坐标为零得到迭代次数，使ROM中的角度相加减对应的迭代次数即可得到角度。

* V1.0   2019.11.23
    * 输入信号位宽可定制；
    * 迭代次数可定制；
    * 结果为角度非弧度；
    * 精确到1°；
    * 输入的直角坐标精度为1；
    * 输入的直角坐标只能为第一象限。

* V1.1  2019.11.24
    * 输入提前左移16位，输出也为左移16位；
    * 输入坐标扩展为四个象限；
    * 精度提高到小于0.05°。


