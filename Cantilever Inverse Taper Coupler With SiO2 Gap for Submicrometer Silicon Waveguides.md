# Cantilever Inverse Taper Coupler With SiO2 Gap for Submicrometer Silicon Waveguides



## 一、自己的总结、评价和应用



## 二、文章的主要问题

（在摘要中找到、疑问句）



## 三、结论

（摘要、结尾处）

The result shows that the input spot size of 5 m can be coupled to 500 nm×240 nm silicon waveguide with a coupling loss less than 0.49 dB/facet and a 3-dB misalignment tolerance larger than 1.8 m for both TE and TM modes. The coupling loss for a standard cleaved fiber with the input spot size of 10.5 m is 3.72 dB/facet (TE) and 2.12 dB/facet (TM).

--- due to the introduction of SiO2 gap

- 输入光斑尺寸
- 耦合损耗
- 3dB失调容差



## 四、思想脉络

（写下小标题以及各标题的关键句、画出重要的概念性名词、过渡句和关键句）

### Abstract

a cantilever inverse taper coupler with SiO2 gap for coupling optical beam between an optical fiber and a sub-micron Si waveguide

### 1. Introduction

- 专有名词

PICs（Photonic Integrated Circuits）光激性 光子集成电路；

SOI（Silicon-On-Insulator）硅基绝缘体；

MFD（Mode Field Diameter）模场直径；

- 关键句

1. 光栅和倒锥形耦合器是用来提高SiW和单模光纤之间耦合效率的主要方法。Granting and inverse taper couplers are the main approaches that have been employed to improve the coupling efficiency between a SiW and a single-mode optical fiber.
2. 为了提高耦合效率和失调容限，已经提出了悬臂倒锥形耦合器来将光束限制在包层材料中。Cantilever inverse taper couplers have been proposed to confine a beam in a cladding material in order to improve coupling efficiency and misalignment tolerance.
3. 因此，非常需要这样一种耦合器，其对于大的输入光斑尺寸可减少耦合损耗，并且对于小的输入光斑尺寸可增加错位容差，而且不需要指数匹配油和复杂的制造工艺。Therefore, a coupler that reduces coupling loss for large input spot sizes and increase misalignment tolerance for small input spot sizes without requiring index-matching oil or complicated fabrication process is highly desirable.
4. 在这封信中，我们报道了这样一种耦合器，它由嵌入在具有二氧化硅间隙的二氧化硅悬臂波导中的倒锥形硅结构组成。In this letter, we report such a coupler consisting of an inverse taper silicon structure embedded in a SiO2 cantilever waveguide with a SiO2 gap.

### 2. Design

- 专有名词

PECVD（plasma enhanced chemical vapor deposition）等离子增强的化学蒸发沉积

​       -- 作用：在硅片表面镀上一层深蓝色的氮化硅膜，可以充分吸收太阳光，降低反射，并且氮化硅膜有钝化的作用，保护电池片不受污染。

​      -- 原理：利用硅烷SiH4与氨气NH3在等离子体中反应，生成Si3N4沉积到硅片表面。

- 关键句

1. 所提出的悬臂倒锥形耦合器由100米长的二氧化硅悬臂波导、嵌入在二氧化硅波导中间的倒线性锥形SiW以及二氧化硅波导面和锥形端之间的二氧化硅间隙组成。The proposed cantilever inverse taper coupler consists of a 100um long SiO2 cantilever waveguide, an inverse linear taper SiW embedded in the middle of the SiO2 waveguide and a SiO2 gap between the SiO2 waveguide facet and the taper end.
2. 组成：SiW（波导管、锥形部分、SiO2间隙）

### 3. Simulation

- 研究方法：三维时域有限差分模拟 a 3D Finite Difference Time Domain 

- 1550nm高斯模式源在耦合器面发射，并作为输入源           A 1550nm Gaussian mode source is launched at the coupler facet and acts as an input source.

- 研究内容：

  1. 耦合器的耦合损耗：由源端的输入功率和SiW的功率测量值计算得出。The coupling loss of the coupler is calculated from the input power at the source and power measurement in the SiW.

  2. 失调容差：通过在垂直和水平方向的不同位置启动输入源。Misalignment tolerances are investigated by launching the input source at various positions in vertical and horizontal directions.

  3. 输入光斑尺寸 input spot sizes：5m、10.5m（TE和TM模）

- 研究方式：

  1. 为了获得最佳的二氧化硅波导宽度，模拟并绘制耦合损耗与具有1mSiO2间隙的SiO2波导的函数关系 In order to obtain SiO2 waveguide width(Same as height), the coupling loss as a function of SiO2 waveguide with 1m long SiO2 gap is simulated and plotted.

     | 输入光斑尺寸 | 最佳宽度  |
     | :----------: | :-------: |
     |      5m      |    6m     |
     |    10.5m     | 6m  /  8m |

       图像分析： 随着硅氧间隙长度从1米进一步增加，6米宽的耦合器开始产生比8米宽的耦合器更多的耦合损耗。

       得到的结论：选择8 m的宽度作为10.5 m输入光斑尺寸的最佳宽度。
     
  2. 为了研究不同长度的硅氧间隙 对0m和2m水平失调耦合损耗的影响，模拟了为5m输入光斑尺寸设计的6m*6m耦合器。
  
        二者关系：硅氧间隙增加，耦合损耗减小（论文中有数据证明）the SiO2 gap allows improvement in misalignment tolerance； 耦合损耗保持不变或增加时，硅氧间隙长度变化不会有改善。
  
        数据：10米SiO2间隙在垂直方向上的3dB失调容差提高到2.5米。
  
        存在的不足：由于SiO2间隙导致的TE模式失调容差改善无法观察。

### 4. Fabrication



### 5. Measurement



### 6. Conclusion

- 通过在硅波导的锥形端前引入具有最佳长度和宽度的二氧化硅间隙。introduce a SiO2 gap with an optimal length and width in front of a tapered end of silicon waveguide for a desired input spot size. 
- 数据：

| 耦合器 | SiO2间隙 | 输入光斑尺寸 | 耦合损耗 | 失调容差 |
| :----: | :------: | :----------: | :------: | :------: |
| 6m*6m  |   10m    |      5m      | <0.49dB  |  >1.8m   |
|   8m   |   15m    |              |          |          |

- 15m二氧化硅间隙和8m宽耦合器的引入 将TM模式 耦合损耗从4.05dB/刻面 提高到2.12dB/刻面；10.5m的输入光斑尺寸 可保持较大的未对准容差。

### Reference

- "Highly efficient nonuniform grating coupler for silicon-on-insulator nanopho-tonic circuits,"  用于绝缘体上硅纳米线电路的高效非均匀光栅耦合器

- "High coupling efficiency etched facet tapers in silicon waveguides,"   硅波导中高耦合效率蚀刻刻面锥

-  "Study on inverse taper based mode transformer for low loss coupling between silicon wire waveguide and lensed fiber,"    用于硅波导与透镜光纤低损耗耦合的倒锥形模式变换器的研究

- "Compact cantilever couplers for low-loss fiber coupling to silicon photonic integrated circuits,"    用于低损耗光纤耦合到硅光子集成电路的紧凑型悬臂耦合器

-  "Suspended optical fiber-to-waveguide mode size converter for silicon photonics,"   硅光子学中的悬浮光纤-波导模式尺寸转换器

-  "Low-loss and broadband cantilever couplers between standard cleaved fibers and high-index-contrast Si3N4 or Si waveguides,"   标准解理光纤与高折射率对比Si3N4或Si波导之间的低损耗和宽带悬臂耦合器

  





