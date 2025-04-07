## 4WD Microbit麦克纳姆轮智能小车的安装步骤

安装1

安装所需零件:

![Img](./media/img-20230428160048.png)

安装:

![Img](./media/img-20230428160108.png)

完成:

![Img](./media/img-20230428160119.png)

安装2

安装所需零件:

![Img](./media/img-20230428160132.png)

安装:

![Img](./media/img-20230428160143.png)

完成:

![Img](./media/img-20230428160221.png)

安装3

安装所需零件：

![Img](./media/img-20230428160244.png)

安装：

![Img](./media/img-20230428160254.png)

完成：

![Img](./media/img-20230428160325.png)

安装4

**舵机初始化：**

安装前需要先设置舵机角度为90°。设置舵机角度时，将舵机连接在Microbit扩展板的G、V、P14，在Microbit主控板上上传对应代码，外接电源供电后，按下Microbit主控板上的复位按键，舵机就转到90°的位置。

| 舵机 | Microbit扩展板 |
| :--: | :--: |
| 棕线 | G |
| 红线 | V |
| 橙线 | P14 |

![Img](./media/img-20230523113829.png)

![Img](./media/img-20230428160816.png)

我们提供的舵机初始化角度的代码位置如下图：

![Img](./media/img-20230428161043.png)

安装所需零件：

![Img](./media/img-20230428163728.png)

安装：

<span style="color: rgb(255, 76, 65);">(注意安装方向)</span>
![Img](./media/img-20230428163800.png)

完成：

![Img](./media/img-20230428163827.png)

安装5

安装所需零件：

![Img](./media/img-20230428163859.png)

安装：

![Img](./media/img-20230428163917.png)

完成：

![Img](./media/img-20230428163926.png)

安装6

安装所需零件：

![Img](./media/img-20230428164033.png)

安装：

![Img](./media/img-20230428164040.png)

完成：

![Img](./media/img-20230428164048.png)

安装7

安装所需零件：

![Img](./media/img-20230428164114.png)

安装：

<span style="color: rgb(255, 76, 65);">（注意电机安装方向，线材方向朝内）</span>

![Img](./media/img-20230428164218.png)

完成：

![Img](./media/img-20230428164226.png)

安装8

安装所需零件：

![Img](./media/img-20230428164353.png)

安装：

![Img](./media/img-20230428164440.png)

完成：

![Img](./media/img-20230428164459.png)

安装9


安装所需零件：

![Img](./media/img-20230428164516.png)

安装：

![Img](./media/img-20230428164531.png)

完成：

![Img](./media/img-20230428164546.png)

安装10

安装准备零件：

![Img](./media/img-20230428164604.png)

安装：

![Img](./media/img-20230428164612.png)

完成：

![Img](./media/img-20230428164627.png)

接线

舵机接线：

| 舵机 | Microbit扩展板 |
| :--: | :--: |
| 棕线 | G |
| 红线 | V |
| 橙线 | P14 |

![Img](./media/img-20230523113903.png)

![Img](./media/img-20230504084018.png)

超声波模块接线：

| 超声波模块 | Microbit扩展板 |
| :--: | :--: |
| Vcc | 5V|
| Trig | P15 |
| Echo | P16|
|Gnd|G|

![Img](./media/img-20230523115314.png)

![Img](./media/img-20230504083927.png)

控制红外模块接线：

| 驱动板 | Microbit扩展板 |
| :--: | :--: |
| GND | G|
| 5V | 5V |
| S5 | P0|

![Img](./media/img-20230523132234.png)

![Img](./media/img-20230504085353.png)

控制WS2812RGB接线：

| 驱动板 | Microbit扩展板 |
| :--: | :--: |
| GND | G|
| 5V | 5V |
| S4 | P7|

![Img](./media/img-20230523133024.png)

![Img](./media/img-20230504085601.png)

控制电机和七彩灯接线:

| 驱动板 | Microbit扩展板 |
| :--: | :--: |
| SCL | P19|
| SDA | P20 |
|5V | 5V|
|GND|G|

![Img](./media/img-20230523133904.png)

![Img](./media/img-20230504085147.png)

控制三路循迹模块接线:

| 驱动板 | Microbit扩展板 |
| :--: | :--: |
| S1 | P10|
| S2 | P4 |
|S3| P3|
| | |
|GND|G|
![Img](./media/img-20230523134552.png)
![Img](./media/img-20230504090137.png)

电源接线:

![Img](./media/img-20230504091010.png)

电机接到对应的接口上:

![Img](./media/img-20230504091336.png)

电池安装示范:

![Img](./media/img-20230504091422.png)


