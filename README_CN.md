## Cherish-75

<p align="left">
  <a href="./README.md">English</a> |
  <a href="./README_CN.md">简体中文</a>
</p>

Cherish-75，Gasket结构客制化机械键盘，PCB已打样验证.

* **License**：MIT，随心取用修改

* **主控**: STM32F072CBT6, Type-C分离小板（保证软弹）

* **硬件PCB**：开槽PCB，可选阻焊开窗(沉金),  立创工程: [链接](https://oshwhub.com/caiyahoho/Cherish-75)

* **配列**：75%，门牙配列

* **轴座**: 同时支持焊接&热插拔

* **RGB:** 大写键下一个RGB贴片灯

* **固件**：QMK & VIA，查看 `fireware` 目录

* **外壳**: 3D打印，**磁吸上下盖设计**，查看 `3d-model`目录

```bash
├── case-and-plate
│   ├── top-case-with-X.stl 
│   ├── top-case.stl
│   ├── bottom-case.stl
│   ├── slotted-plate.dwg
│   └── plate.dxf
├── firmware
│   ├── bin  
│   └── cherish-75-via.json # Via Config
├── hardware
│   ├── bom.xlsx # BOM
│   └── gerber # PCB  Gerber 
```

## 电路板
### 黑色
![top](./imgs/top.png)

![bottom](./imgs/bottom.png)

### 白色:
![top](./imgs/white-top.png)

![bottom](./imgs/white-bottom.png)

### 子板

![daughterboard](./imgs/daughterboard-1.png)

![daughterboard](./imgs/daughterboard-2.png)

## 配列

![layout](./imgs/layout.png)

**Via**
![layout](./imgs/cherish-75-via.png)

## 外壳
### 上壳 样式1

![top-case](./imgs/top-case.png)

### 上壳 样式2

右下角去除一个按键，增加 `X` 装饰，无限可能

![top-case-x](./imgs/top-case-x.png)

![top-case-x](./imgs/top-case-x-2.png)


### 整体效果
![top-case](./imgs/3d-1.png)

![top-case](./imgs/3d-2.png)

 
## 实体
### PCB打样

![pic-3](./imgs/pcb-3.jpg)

![pic-4](./imgs/pcb-4.jpg)

**焊接：**
![pic](./imgs/pcb-1.jpg)

### 组装实体
![pic](./imgs/bd-1.jpg)

### 视频
**BiliBili**

[![bilibili](https://res.cloudinary.com/marcomontalbano/image/upload/v1717640150/video_to_markdown/images/youtube--ES9FB7N3KS8-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.bilibili.com/video/BV1CS4y1W7Da/)
 
**Youtube**
[![Cherish-75](https://res.cloudinary.com/marcomontalbano/image/upload/v1717640150/video_to_markdown/images/youtube--ES9FB7N3KS8-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=ES9FB7N3KS8&t=7s "Cherish-75")