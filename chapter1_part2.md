（1）完成一级保养。

（2）检查设备电源开关，检查线路是否完好。

（3）启动设备，检查程序是否能正常运行。

（4）检查设备的功能。

填写设备维护保养记录表：

表 1-2-4 设备点检日保养表

<table>
<tr>
<td>**序号**<br/></td><td>**设备名称**<br/></td><td>**型号/规格**<br/></td><td>**设备编号**<br/></td><td colspan="2">**维护保养级别**<br/></td><td>**维护保养人(单位)**<br/></td><td>**维护保养时间**<br/></td><td>**备注**<br/></td></tr>
<tr>
<td rowspan="3">1<br/></td><td rowspan="3">高低温冲击箱<br/></td><td rowspan="3">ShockEvent T/120/V2<br/></td><td rowspan="3">CX0333<br/></td><td>一级<br/></td><td><br/></td><td><br/></td><td><br/></td><td><br/></td></tr>
<tr>
<td>二级<br/></td><td><br/></td><td><br/></td><td><br/></td><td><br/></td></tr>
<tr>
<td>三级<br/></td><td><br/></td><td><br/></td><td><br/></td><td><br/></td></tr>
</table>

在现代电子系统中，芯片的温度适应性直接决定了设备的可靠性。未经充分温度循环测试的芯片，在面临剧烈或频繁的温度变化时，可能会因材料膨胀系数不匹配、焊点疲劳或内部结构应力累积而逐渐失效。例如，在汽车电子领域，极端温差可能导致控制单元的焊点开裂，引发传感器误报或动力系统异常，可能引发严重的安全事故；在航天应用中，芯片若无法承受太空环境的高低温循环，可能因金属迁移或封装开裂而造成关键功能中断，从而导致整个航天计划的失败；而消费电子产品（如智能手机）在寒冷或高温环境下的性能下降、随机重启等问题，往往也源于芯片的热可靠性不足。

为确保芯片的长期稳定运行，工程师会通过反复循环测试筛选合格产品，并在设计阶段优化材料选择和封装工艺。此外，在系统层面采用散热设计、温度补偿电路等措施，也可以进一步提升电子设备的环境适应性。这些技术手段共同保障了从日常家电到工业设备、航空航天器等各类电子产品的可靠运行。

### **1.2.7 技能训练**

1. 测试其他封装类型芯片，如 QFP、BGA、QFN 等。
2. 参考表 1-2-5，完成其他温度条件下的温循测试。

表 1-2-5 温度循环实验条件

<table>
<tr>
<td rowspan="2">**步骤①**<br/></td><td rowspan="2">**每步时间 min**<br/></td><td colspan="6">**试  验  温  度 ℃**<br/></td></tr>
<tr>
<td>A<br/></td><td>B<br/></td><td>C<br/></td><td>D<br/></td><td>E<br/></td><td>F<br/></td></tr>
<tr>
<td>第 1 步<br/>冷<br/></td><td>≥10<br/></td><td>-550-10②<br/></td><td>-550-10<br/></td><td>-650-10<br/></td><td>-650-10<br/></td><td>-650-10<br/></td><td>-650-10<br/></td></tr>
<tr>
<td>第 2 步<br/>热<br/></td><td>≥10<br/></td><td>85+100<br/></td><td>125+150<br/></td><td>150+150<br/></td><td>200+150<br/></td><td>300+150<br/></td><td>175+150<br/></td></tr>
<tr>
<td colspan="8">① 步骤1和步骤2可互换，在转换期间，负载温度可超过0容限，不可超过表中其他容限。<br/>② 上下标代表未激活温度相对于测试温度的变化程度，其中上标代表高于测试温度，下标代表低于测试温度。<br/></td></tr>
</table>

3. 了解其他温循测试仪器，对比其与本实验所需仪器在性能和操作上的差别

### **1.2.8 思考题**

1. 筛选测试与可靠性测试的区别是什么？如何确定适当的温度循环参数，既能有效筛选出潜在问题器件，又不会对合格器件造成损伤？
2. 在半导体器件筛选测试中，温度循环条件的严苛程度与筛选效率和误判率之间存在什么关系？如何确定最优的筛选条件？
3. 温度循环测试中，温度变化率(°C/min)对测试结果有何影响？为什么筛选测试中使用的温度变化率通常比实际使用条件高？这会带来哪些解释结果时需要注意的问题？
4. 若某功率模块的热循环寿命模型为

请计算以下条件下的预期寿命，并分析温度循环幅值和平均温度的变化对寿命的影响。

a) _ΔTj_ = 120°C，_Tm _= 65°C

b) _ΔTj_ = 80°C，_Tm _= 65°C

c) _ΔTj_ = 120°C，_Tm _= 85°C

5. 在进行半导体器件温度循环测试时，为节省时间，有时会采用“加速测试”方法（如增大温度幅值或加快变化速率）。这种加速测试结果能否准确预测实际使用寿命？存在哪些潜在问题？如何合理设计加速测试方案？
6. 随着宽禁带半导体（如 SiC、GaN）器件的应用日益广泛，它们在温度循环条件下的可靠性表现是否与传统 Si 器件有显著差异？查阅相关文献，分析其中的机理。

### **参考文献**

[1] 戎珂, 黄成, 周迪, 等. 后摩尔时代中国集成电路产业生态发展进路[J/OL]. 科学学研究, 1-12[2025-06-06]. [https://doi.org/10.16192/j.cnki.1003-2053.20250114.001](https://doi.org/10.16192/j.cnki.1003-2053.20250114.001).

[2] 王阳元. 发展中国集成电路产业的“中国梦”[J]. 科技导报, 2019, 37(3): 49-57.

[3] 孙玲, 黎明, 吴华强, 等. 后摩尔时代的微电子研究前沿与发展趋势[J]. 中国科学基金, 2020, 34(05): 652-659. DOI:10.16262/j.cnki.1000-8217.20200825.004.

[4] Institute of Electrical and Electronics Engineers (IEEE), 2018, “Beyond CMOS: The Future of Semiconductors,” IEEE IRDS, [https://irds.ieee.org/home/what-is-beyond-cmos](https://irds.ieee.org/home/what-is-beyond-cmos).

[5] 宋孝霖, 项卓. 集成电路的失效分析技术研究[J]. 中国设备工程, 2024, (23):236-237.

[6] 张大为. 集成电路器件的可靠性测试与失效分析[J]. 集成电路应用, 2024, 41(08):33-35.DOI:10.19339

[7] 杨妙林, 任瑛. 集成电路分层的失效分析[J]. 电子产品可靠性与环境试验, 2022, 40(S1):36-40.

[8] 倪宋斌, 马美铭. 集成电路成品测试的常见问题分析[J]. 电子与封装, 2023, 23(12):24-27. DOI:10.16257

[9] 谈向萍, 俞云强. 浅谈集成电路的测试技术[J]. 无锡职业技术学院学报, 2006, (02):67-68+88.

[10] Ciappa M. Selected failure mechanisms of modern power modules[J]. Micro-electronics Reliability, 2002, 42(4-5): 653-667.

[11] Lutz J, Schlangenotto H, Scheuermann U, et al. Semiconductor Power Devices: Physics, Characteristics, Reliability[M]. 2nd Edition. Springer, 2018.

[12] IEC 60749-25:2003. Semiconductor devices - Mechanical and climatic test methods - Part 25: Temperature cycling.

[13] JEDEC Standard JESD22-A104D. Temperature Cycling. JEDEC Solid State Technology Association, 2009.

[14] GB/T 2423.22-2012 电工电子产品环境试验 第 2 部分: 试验方法 试验 N:  温度变化.

[15] Downing S D, Socie D F. Simple rainflow counting algorithms[J]. International Journal of Fatigue, 1982, 4(1): 31-40.

[16] Scheuermann U, Schmidt R. Impact of load pulse duration on power cycling lifetime of Al wire bonds[J]. Microelectronics Reliability, 2013, 53(9-11): 1687-1691.

[17] Infineon Technologies. Application Note AN2010-02: Use of Power Cycling Curves for IGBT4[R]. 2010.

[18] ASTM E1049-85(2017). Standard Practices for Cycle Counting in Fatigue Analysis.

[19] Coquery G, Lefranc G, Licht T, et al. High temperature reliability on automotive power modules verified by power cycling tests up to 150°C[J]. Microelectronics Reliability, 2003, 43(9-11): 1871-1876.

[20] Ma K, Liserre M, Blaabjerg F. Lifetime estimation for the power semiconductors considering mission profiles in wind power converter[C]//IEEE Energy Conversion Congress and Exposition. IEEE, 2013: 2962-2971.

[21] Choi U, Blaabjerg F, Jørgensen S. Power cycling test methods for reliability assessment of power device modules in respect to temperature stress[J]. IEEE Transactions on Power Electronics, 2018, 33(3): 2531-2551.

[22] 刘成海, 付林, 王凯等. IGBT 模块温度循环可靠性试验与分析[J]. 电工技术学报, 2014, 29(8): 90-96.

[23] Schulz M. Thermal management details and their influence on the aging of   power semiconductors[C]//International Exhibition and Conference for Power Electronics, Intelligent Motion, Renewable Energy and Energy Management. VDE, 2014: 1-6.

## 

**项目一**

## 任务 1.3 集成电路老炼测试

任务描述

waeofiajo

杜工程师的智能手表最近“闹脾气”了——常温下走时精准，可一到烈日当头的户外，屏幕就突然黑屏“装死”！返厂拆解后发现，罪魁祸首竟是主控芯片上一处​​肉眼看不见的氧化层裂缝​​。高温下裂缝扩张，电流“抄近道”引发短路，整块芯片直接“中暑昏迷”。

为什么芯片如此“娇气”？答案藏在出厂前的​​终极压力测试——老炼试验​​里！

想象一下，新诞生的芯片被送进一间​​125℃ 的“高压桑拿房”​​。这里没有 relaxation，只有持续 168 小时以上的“电流马拉松”：电源电压超负荷加压（额定值的 1.1–1.3 倍），信号引脚高频脉冲“疯狂轰炸”，让芯片内部数亿晶体管像跑马拉松一样不停翻转。

这场“魔鬼特训”专治各种潜伏的​​制造微缺陷​​：

“虚焊刺客”​​——像没拧紧的水龙头，高温下焊点膨胀脱落；

​“离子流浪汉”——芯片和导线连接不牢靠；

“氧化层脆皮”——薄弱介质层被高压击穿，火花四溅。

只有扛住电热“双毒打”、全程不“摆烂”的芯片，才能拿到​​可靠性毕业证书，确保您的爱车在 50℃ 地表温度下充电稳如磐石，智能手表暴晒不“宕机”！

老炼测试是集成电路重要的筛选测试方法之一。老炼测试是对集成电路施加高温和电应力，模拟长期使用环境，提前剔除因材料缺陷、工艺瑕疵或设计薄弱导致的早期失效产品，即“婴儿期失效”，将市场失效率降低 10–100 倍。总的来说，老炼测试是集成电路可靠性的“终极守门员”。

本实验项目先对老炼测试有个简单的任务描述，让读者对集成电路的老炼测试有一个初步了解，然后介绍老炼测试的意义、工作原理、工作流程与安全操作以及老炼测试准备工作操作、老炼测试和常温电测（老炼后）。通过老炼测试实验，使读者进一步了解集成电路的可靠性。

<table>
<tr>
<td>**知识目标**<br/></td><td>1. 理解老炼测试的原理与应用场景。<br/>2. 掌握老炼测试的类型与流程。<br/>3. 学习参数设计核心要素。<br/>4. 掌握数据判断与失效分析。<br/></td></tr>
<tr>
<td>**技能目标**<br/></td><td>了解并掌握老炼测试设备装置，掌握老炼测试准备工作操作、老炼测试和常温电测（老炼后）的一系列操作，进行老炼测试实验数据的记录、分析和处理。<br/></td></tr>
<tr>
<td>**素质目标**<br/></td><td>1. 具有独立实验能力，能够独立完成从参数设计到设备操作以及失效分析的全流程。<br/>2. 进行数据记录、分析和处理过程中，能够针对出现的问题制定合适的解决方案，同时可以高效处理实验数据。<br/>3. 具有技术适应能力，能够掌握新型技术，适应智能化老炼趋势。<br/></td></tr>
<tr>
<td>**教学重点**<br/></td><td>1. 老炼设备的分类与选择。<br/>2. 老炼测试的实验方式和设备操作方法。<br/>3. 老炼测试的参数设计。<br/>4. 未通过老炼测试的后果：早期失效导致汽车充电故障、航天设备宕机。<br/></td></tr>
<tr>
<td>**教学难点**<br/></td><td>老炼测试参数的设计。<br/></td></tr>
<tr>
<td>**建议学时**<br/></td><td>4-6 学时<br/></td></tr>
<tr>
<td>**推荐教学方法**<br/></td><td>采用“任务驱动法”，根据知识目标、技能目标、素质目标从任务入手，通过老炼测试实验，让读者了解集成电路老炼测试的基本原理和方法。<br/></td></tr>
<tr>
<td>**推荐学习方法**<br/></td><td>采用“边做边学”，一边动手操作，一边勤于思考，完成一个完整的老炼测试实验。<br/></td></tr>
</table>

知识准备

### **1.3.1 老炼测试的意义**

老炼测试是高可靠性集成电路的筛选实验之一。老炼测试的目的是为了筛选或剔除那些勉强合格的器件，这些器件或是本身具有固有的缺陷，或是制造工艺控制不当产生缺陷，这些缺陷会造成时间和应力有关的失效。如不进行老炼测试，这些有缺陷的器件在使用条件下会出现初期致命失效或早期寿命失效。因此，筛选时用最大额定工作条件或在最大额定工作条件之上对微电路施加应力，或施加能以相等的或更高的灵敏度的等效筛选条件以诱发电路产生失效，并将之剔除。

老炼测试的试验条件有六种，工作方式可以根据不同的电路类型来选择其中一种条件进行试验。

1. 稳态、反偏。适用于各类线性和数字电路。稳态模式如图 1-3-1 所示，采用该模式时应使尽可能多的结都加上规定的电压。
2. 稳态、正偏。适用于所有数字电路和某些线性电路。
3. 稳态、功率和反偏。适用于各种数字电路和输入端可以反偏置、输出端可以偏置在最大功耗上的某些线性电路。
4. 并行激励。适用于各类电路。并激模式如图 1-3-2 所示，采用该模式时，所有电路必须施加合适的激励信号以尽可能模拟实际应用，而且所有电路均应采用最大的外加负载。激励频率不得小于 60Hz。
5. 环行振荡器试验。
6. 温度加速试验。

![](static/Q4rtbjSxaoC6E0xHaIvcCrRhnKb.png)

图 1-3-1 稳态模式

![](static/X6zFbkoyBoKpdcxokrmcim9fnNh.png)

图 1-3-2 并激模式

有时，为了加快电路的筛选进程，使电路在大大超过其最高额定温度的环境温度条件下进行试验。此时，由于温度高，电路异常，不能正常工作。因此必须要注意选择偏置线路和条件，以避免对电路造成过应力。

老炼试验是一种非破坏性试验，能够诱发器件内部的潜在缺陷出现失效现象，而不改变其失效分布，也不会引入不同的失效机理。根据一般要求，所有器件在交付给用户前，都应该进行老炼试验，通过筛选提高器件的使用可靠性，但这并不能提高单个电路的固有可靠性。

### **1.3.2 老炼测试的工作原理和主要指标**

#### **1. 老炼测试的工作原理**

老炼试验的本质是通过加速应力暴露早期缺陷，根据浴盆曲线理论。老炼试验的目标是使产品跳过浴盆曲线的左侧高峰，直接进入稳定工作期。

实践证明大多数设备的故障率是时间的函数，典型故障曲线称之为浴盆曲线，如图 1-3-3 所示。如果取产品的失效率作为产品的可靠性特征值，则它是以使用时间为横坐标，以失效率为纵坐标的一条曲线。曲线具有明显的阶段性，失效率随使用时间变化分为三个阶段：早期失效期、偶然失效期和损耗失效期。

第一阶段是早期失效期，表明产品在开始使用时，失效率很高，但随着产品工作时间的增加，失效率迅速降低，这一阶段失效的原因大多是由于设计、原材料和制造过程中的缺陷造成的。为了缩短这一阶段的时间，产品应在投入运行前进行试运转，以便及早发现、修正和排除故障；或通过试验进行筛选，剔除不合格品，这一试验在集成电路领域正是老炼试验。

![](static/S6p5b3Q6Xotx93xkHMacvEDQnRh.png)

图 1-3-3 浴盆曲线

元器件发生失效的内在原因为构成其最小物质的化学和物理反应，而导致出现电迁移、击穿、腐蚀等失效现象。老炼试验的主要依据为经典反应速率理论，内部物理、化学反应随着电、热等应力的增加而加速。在实际工程研究中，最常用的是阿伦尼乌斯模型。

在老炼试验加速模型中主要关注激活能（）和加速因子（）两个参数。激活能是指将器件的潜在缺陷激发为失效所需的能量，即发生失效时必须达到的能量门限。加速因子定义为器件处于老炼应力和正常应力下，达到同一失效率分别花费时间的比率。在集成电路老炼试验中，常使用温度应力加速因子（）和电应力加速因子（）。试验中施加的应力越大，加速因子也相应的越大，元器件的失效速度也就越快，也就能使器件越早进入浴盆曲线中的偶然失效期。总的来说，浴盆曲线锁定“何时失效”，阿伦尼乌斯方程解决“如何加速失效”，这二者共同构成老炼试验的物理化学基础。

老炼试验主要有四种类型，分别为静态老炼、动态老炼、高温反偏老炼以及超高温老炼。

**静态老炼**：主要用于数字电路、线性电路及对动态信号要求不高的器件以及表面沾污、引线虚焊、沟道漏电等与污染相关的缺陷。其工作原理为仅对器件施加直流电源电压，其电压值通常为额定值的 1.1-1.3 倍，输入引脚通过电阻接地或接电源使内部晶体管处于反偏状态。在高温环境下，电场驱动杂质离子迁移至器件表面，诱发漏电或短路失效。

**动态老炼**：主要用于氧化层针孔、导电通路断裂、内部节点失效等缺陷。其工作原理为除电源电压外，向输入引脚施加高频脉冲信号，使内部晶体管频繁翻转，模拟实际工作状态。节点翻转产生动态热梯度，可以加速氧化层击穿、硅片裂纹等深层缺陷暴露。

**高温反偏老炼**：主要用于功率器件、二极管等反向应用器件以及表面离子污染、钝化层缺陷、PN 结漏电等缺陷。其工作原理为在高温下对 PN 结施加反向偏压，强化电场效应。电场力驱动可动离子向敏感区域聚集，引发表面漏电或钝化层失效。

**超高温老炼**：主要用于宇航级等高可靠性芯片，需特种耐高温 PCB 以及封装材料失效、焊点疲劳、深层晶格缺陷等缺陷。其工作原理为采用极端温度加速深层晶格缺陷，高温下原子扩散速率呈指数级增长，促使微裂纹、界面分层等缺陷快速扩展。

这四种不同老炼方法的适用性对比如表 1-3-1 所示。

表 1-3-1 不同老炼方法适用性对比

<table>
<tr>
<td>方法<br/></td><td>适用场景<br/></td><td>应力组合<br/></td><td>典型参数<br/></td></tr>
<tr>
<td>静态老炼<br/></td><td>数字/线性电路<br/></td><td>高温+直流电压<br/></td><td>125℃、1.2V、168h<br/></td></tr>
<tr>
<td>动态老炼<br/></td><td>CPU/存储器<br/></td><td>高温+动态信号<br/></td><td>125℃、100MHz、240h<br/></td></tr>
<tr>
<td>高温反偏<br/></td><td>功率器件<br/></td><td>高温+反向偏压<br/></td><td>150℃、80V、168h<br/></td></tr>
<tr>
<td>超高温老炼<br/></td><td>宇航/车规芯片<br/></td><td>超高温+电应力<br/></td><td>300℃、1000h<br/></td></tr>
</table>

最后，还需了解老炼试验是一种通过电-热应力加速暴露电子元器件潜在缺陷的可靠性筛选技术，其工作流程主要分为三个阶段：老炼前准备、应力施加和老炼后处理。

**老炼前准备**：需先对器件进行基础功能测试，如接触测试、漏电流、驱动电流等，剔除有明显缺陷的产品以避免资源浪费。还需确认好器件无物理损伤，并做好静电防护。样品预筛选完之后，还需进行设备校准，如检查老炼箱温度精度、电源电压范围、信号源频率等，确保设备在计量有效期内。除此之外，需重点进行老炼板验证，具体有检查线路连接、焊点的牢固性、金手指无污染、试验座无松动以及验证阻容器件参数匹配应力要求。最后进行参数配置，温度设定通常为 125℃，升温速率 ℃/分钟防止热冲击。电应力模式则应根据静态老炼和动态老炼进行分别设置。

**应力施加**：这一阶段的操作顺序很为关键，在启动时，应先加电应力再升温，可以避免冷启动电流冲击；在结束时，应先降温至小于 35℃ 时再断电，可以防止离子回迁掩盖失效。在施加阶段，还需持续记录温度、电压、信号频率，与预设值对比并标记偏差。当发现有失效器件时应立即取出，避免影响其他器件，但是对应的还需要补足因中断缺失的老炼时间。

**老炼后处理**：应降温至小于 35℃ 时再断电，可以避免热应力损伤。在取样时应该防静电、防物理损伤，及时存入防静电载具。还需进行全参数复测及失效分析，对参数异常的器件解剖，定位具体的缺陷类型。最后应该记录筛选率、失效模式分布，输出浴盆曲线对比图，展示早期失效率降低效果。

总的来说，老炼试验是通过电-热应力耦合加速缺陷暴露，流程核心在于前置筛查，时序控制及时效复测。其效果显著体现在浴盆曲线左移，使早期失效率降低 90% 以上，为高可靠性领域提供首道质量防线。

#### **2. 老炼测试的主要指标**

针对需要进行老炼试验的器件，首先应确定对应的老炼条件，包括老炼温度和时间。一般在确定条件时需综合考虑性能及成本，为尽可能实现高性价比，明确合适的老炼时间非常重要。假设器件的失效率符合浴盆曲线，早期失效期与偶然失效期转折点为，偶然失效期与损耗失效期转折点为。若仅考虑器件性能的影响，不考虑任何成本的因素情况下，老炼后得到的器件整体平均寿命最高。结合浴盆曲线中经过转折点后失效率基本为常数，继续进行老炼试验没有意义，故老炼时间应控制在之前。

集成电路失效分布模型一般采用威布尔分布，相关失效分布函数、失效密度函数、失效率函数为：

```
        (3-1)

      (3-2)

            (3-3)
```

式中，为形状参数，为特征寿命。当小于 1 时，分布曲线单调下降，符合早期失效期特点；当为 1 时，分布曲线随时间呈现出恒定值，符合偶然失效期特点；当大于 1 时，分布曲线单调上升，符合损耗失效期的特点。根据有关研究，集成电路早期失效期的值为 0.2~0.6。

对于同一款元器件而言，相应失效机理、激活能等参数是定值，需找到拐点时间。为确定某器件的特征寿命和激活能，一般需开展加速寿命试验，获取不同样品在不同加速应力下的特征参数退化数据；再利用退化方程拟合，计算各应力条件下各样品的伪寿命数据，确定伪寿命分布函数，计算各应力条件下的平均寿命。利用加速模型推算常温工作寿命，进而可计算得到激活能。

完成老炼试验之后，早期失效率可降低 10-100 倍，这可通过浴盆曲线左移实现。且动态老炼可覆盖 85% 以上潜在缺陷，而静态老炼仅针对表面缺陷。

### **1.3.3 老炼设备的分类与选择**

在老炼测试中，老炼测试设备承担着核心的可靠性筛选职能。这类设备通过耦合高温环境与电应力，加速激发元器件内部的潜在缺陷，如表面污染、焊接不良或氧化层击穿等，从而高效剔除早期失效产品。面对静态老炼、动态老炼、高温反偏等不同原理的设备，以及军工、车规、消费电子等差异化的应用需求，如何精准匹老炼测试设备成为了测试工程师的关键挑战。下文将系统介绍老炼测试设备的分类方式，并详细阐述选择时需要考量的关键因素。

#### 1.** 老炼设备的分类方式与选择**

老炼测试设备虽然种类繁多，但可以根据工作原理、应用对象及技术先进性分为三大类。

按工作原理划分，静态老炼设备仅施加直流电源，适用于电阻、电容等无源元件的表面污染筛选；动态老炼设备则是通过叠加高频脉冲信号，来驱动 CPU、存储器等逻辑器件内部节点翻转，模拟元器件的实际应用，使受试元器件处于最大额定工作条件或以上，一般可覆盖 85% 以上的潜在缺陷；高温反偏（HTRB）设备针对功率器件，在高温下施加近击穿的反向偏压以激发漏电缺陷；超高温老炼设备则支持 175–300℃ 极端温度，用于宇航级芯片的封装疲劳测试。

按应用对象分类，集成电路老炼系统需满足动态信号与高温耦合，分立器件系统侧重反向偏压与功率循环，无源元件设备聚焦高温电压应力，功率模块系统则需兼容高反压与超长时测试。

从技术先进性维度上来看，传统设备仅提供基础电热应力。而智能系统，如 XR8238A，融合 TDBI 技术，实现老炼中实时监测电参数与功能状态，并采用充氮保护防止器件管脚氧化，同时支持多通道并行测试，可显著提升筛选效率。

老炼测试设备的选择同样需要综合考虑多个技术参数，大体上需要聚焦四项关键技术指标。首先是应力参数，常规的民用级的器件的老炼测试的温度需要达到 1253℃ ，车规及宇航级的温度更是要达到 175–300℃，电压一般都为额定值 1.1–1.3 倍。

时间控制方面，常规器件老炼 96–168 小时，宇航级至少需要 240 小时，且老炼后测试需在 96 小时内完成以防参数复原。针对具体的应用场景，需要结合测试成本以及测试精度等多方面考虑，按照老炼测试相关的理论计算测试时间。

在防护与安全方面，充氮系统为表面贴装器件（如 BGA）必备，设备电压波动需小于 1%，温度均匀性控制在 2℃ 以内。并且设备适配性要求兼顾封装兼容性、散热设计及标准符合性。

关于现代测试系统，行业公认的要求不断变的严苛，优秀的现代老炼测试设备需要支持自动化数据接口及可编程控制，以适配高可靠性场景的零容忍需求。

不同应用场景对老炼测试设备的需求呈现显著差异：​​消费电子领域​​主要采用经济型静态老炼设备，通过基础电热应力实现 96 小时常规筛选，以低成本覆盖电阻、电容等无源元件的表面污染缺陷，满足早期失效剔除的基本需求；汽车电子领域​​则需符合 AEC-Q100/Q104 等车规标准，设备需兼具动态老炼与高温反偏功能，并集成 TDBI 技术实时监测电流/电压波动，确保对 CPU、功率器件等复杂元件的早期失效率降低 10–100 倍，同时满足 168 小时严苛测试要求；军工与航天领域​​要求设备支持极端可靠性，例如超高温范围配合充氮保护以防止 BGA 封装管脚氧化，并符合 MIL-STD-883G/GJB548B 标准，实现对宇航级器件 1000 小时封装疲劳测试的零失效保障；而​​研发实验室场景​​更侧重灵活性与扩展性，需设备兼容多协议接口、支持可编程向量编辑及并行测试，并集成参数测量单元实时生成浴盆曲线报告，以辅助失效机理研究与工艺优化。各场景选型的本质差异体现为：消费电子以成本优先，汽车电子以标准驱动组合测试，军工航天追求极限可靠，研发实验聚焦数据深度与迭代支撑。

一些市面上的设备如图 1-3-4 至图 1-3-6 所示。图 1-3-4 所示为北京新润泰思特测控技术有限公司的 XR8240 集成电路老炼测试系统，其特性包含：温度支持 85℃~200℃，电压动态范围 0-100V、真彩触摸屏 PLC 控制系统，支持多温区并行编程、TDBI 实时电流追踪、氮气保护防止氧化等。图 1-3-5 所示为湖南易升仪器设备有限公司的车规级功率器件老炼柜 H3TRB，其特性包含：温度 150℃2℃ 和反向偏压 0-1200V、独立液冷模块防止过温，湿度控制 3%RH、低热耗设计（待机功耗 <500W），省电率 35%。图 1-3-6 所示为 ATiS 杭可仪器的超大规模集成电路老化测试系统 LSIC-2001，其特性包含：采用数字信号发生单元，通过特定的编程手段，能够在老化过程中持续地施加激励信号，器件根据激励信号做出相应的工作状态调整，并且设备会持续地监测器件的输出状态；整机采用一个独立式充氮高低温试验箱，烘箱内部采用强排风设计通过冷风带走老化器件的多余热量；单区提供 32 路独立温控平台，可同时适应不同温度要求的器件老炼测试。驱动板采用模块化设计，采用母板和子板对插的方式，便于系统后期升级与维护等。

![](static/D90xbHx4uoKLmNxsbsyc2b4Fnhf.jpeg)

图 1-3-4  XR8240

![](static/Y74yb2ngxo7GSzxFex7cI4X2nMb.jpeg)

图 1-3-5  H3TRB

![](static/BWa8buRrRoAZjWxEpCucC8ROnb9.png)

图 1-3-6  LSIC-2001

#### **2. 本实验所需仪器设备**

本实验所需仪器设备如图 1-3-7 所示，型号为 SPIC-TS 集成电路高温动态老化箱，具有温度控制能力、动态测试功能及并行处理能力。其温度范围一般为 10℃~150℃（最高可扩展至 200℃），还支持平均升温速率 3~7℃/min。在动态测试时可以实时监测，同步采集电压、电流、温度曲线，当发生异常时可以自动切断电源。总的来说，SPIC-TS 类设备以高精度温控和多通道动态应力为核心，通过并行测试架构提升筛选效率，尤其适合车规/航天芯片的可靠性验证。

![](static/YFkVbrohnoRlrJxDH9HcF3THnug.png)

图 1-3-7 SPIC-TS 集成电路高温动态老化箱

### **1.3.4 老炼测试的工作流程**

老炼测试的本质是“浴盆曲线左移”，也就是通过加速应力将早期失效阶段压缩在出厂前完成，确保交付产品进入偶然失效期。这一测试广泛应用于电子元器件、汽车电子及军工航天等领域。

本次试验的标准化工作流程大致可分为三个阶段，分别为老炼测试前准备、应力施加及老炼后处理。

老炼测试前准备主要有样品预筛选与检查、设备与试验板校验以及应力条件设定，包括温度与电应力。

应力施加主要需要注意的是应力加载的顺序以及需要缓升缓降，避免热冲击导致损伤，还需要再应力施加时进行实时监测与记录。

老炼后处理主要有冷却取样、全面复测与失效分析以及交付。需要注意的是样品需在烘箱内自然冷却至 35℃ 以下再断电取出，避免因为骤冷而导致参数漂移。

将上述过程进行总结，老炼测试的工作流程如图 1-3-8 的流程图所示。

![](static/OOXVbw6dModO43x6MRocNDnqnag.png)

图 1-3-8 老炼测试的工作流程

#### **1. 确定老炼条件，设计老炼图**

根据要老炼电路的类型，选择适当的老炼条件。再根据电路和老炼条件，设计老炼图。

#### **2. 制作老炼板**

按照设计的老炼图制作老炼板。但在制作老炼板时，布线时需要考虑到电路在工作过程中产生的电流大小，又要考虑到布线时产生的电阻的影响。所以设计时要兼顾到既能满足电路工作时的电流要求，又要使电压和信号的传递衰减最小。

#### **3. 调好信号，电压。设好电压电流保护**

设定电路老炼所需的电压及信号。

#### **4. 常温调试老炼板**

在常温下，按照电路工作时的条件进行老炼板调试。但在常温调试老炼板时经常会遇到噪声干扰等问题。如在数字电路的老炼时，由于很多的开关动作会使电路本身产生噪声。因此在调试老炼板时必须注意到这一点。并且在设计老炼板时就要引起注意。

#### **5. 调好温度，并设报警温度**

按照电路老炼要求，设定所需的环境温度。对于环境温度的设计及控制一定要严格。温度过高，会使电路遭受过应力；温度过低，可能会达不到老炼的效果。因此要注意温度的设定。

#### **6. 放入电路，高温老炼**

将电路进行老炼试验，并设定好老炼时间。在老炼过程中，一定要观察电路的运行情况，主要是通过观察电路的信号、电压、电流及电路的输出。因为有些缺陷明显的电路在经过一段时间的高温工作后，就会显露出来。这时一定要查出有问题的电路并取出，以免影响到其他电路的老炼。

#### **7. 结束老炼，取出电路，测试**

老炼试验结束，测试。除了需要在老炼结束时注意的冷却问题，取出电路后在常温下进行的电性能和参数测试必须在规定的时间内测试完毕，否则还需要按照规定再次进行老炼试验。

老炼试验一般需要几天的时间，而且在这个时间段内，电路不能从烘箱内拿出来，除非在老炼过程中电路发生异常现象，但是缺的老炼时间要按照规定的时间来补足。经过老炼试验的电路由于是模拟了电路的真实运行状态，而且电路又是在工作在其所能承受的最大环境温度中，所以电路本身的电性能参数可能会发生变化。这时，那些本身具有固有的缺陷或者其由于制造工艺的控制不当而造成缺陷的电路，就可能通过参数的变化而表现出来。

### **1.3.5 集成电路高温动态老化箱安全操作规程**

#### **1. 目的**

在保证设备稳定运行的同时，确保人员安全、测试结果准确可靠，并可以有效的暴露芯片的潜在缺陷。对于设备，可以维持热、电系统的稳定性，延长使用寿命；对于人员，可以很好的规避高温、电气等多重风险；对于数据，可以确保缺陷暴露轨迹可追溯，支撑失效分析；对于样品，可以防止因非测试因素而导致的二次损伤。

#### **2. 适用范围**

适用于所有操作集成电路高温动态老化箱的技术人员和工程师。

#### **3. 安全操作步骤**

（1）环境核查与设备安全检查

在使用设备前，应先进行环境核查，确保地面平整防静电以及环境中无腐蚀性气体和震动源。

环境核查结束后，进行设备安全检查。需要确保电气安全，确认电源电压匹配，配备漏电断路器。还应检查所有安全装置都处于正常工作状态。

（2）防护装备穿戴

操作人员需要穿戴防护服、隔热手套、防电弧面罩、绝缘鞋等，以及需要持电工证及操作证上岗，禁止单独作业。

（3）样品装载规范

样品应均匀分布，禁止叠放或者遮挡风道。当需要用到特殊物品如锂电池时，需要单独分区，并配备防爆盒和灭火毯。且还需要进行防静电措施。

（4）参数设置

控制温度时，应升温速率 5℃/min，温度均匀性 2℃，避免超温损伤。

进行电应力配置时，动态老化时，应先通电再升温，最后加载高频信号，关闭时反向操作即可。

（5）异常处置

当发生参数异常时，应该暂停测试，检查控制系统；当设备发生局部冒烟时，应立即切断电源，启动应急排风；当出现明火时，应迅速用灭火毯覆盖着火物，这时禁止开门，操作人员及时疏散后报警。

（6）测试结束

测试结束后，应先停止加热，待温度自然冷却至 35℃ 时再断电取样，这可以避免热冲击导致参数漂移。且操作人员在开门时应侧身开门防止高温气体冲出，并佩戴隔热手套取出样品。

测试结束后，对集成电路高温动态老化箱进行清洁和维护，确保设备处于良好状态。

#### **4. 注意事项**

安全操作的核心是防止设备损坏、保证人员安全以及确保数据有效。

测试完成后，还需对设备进行维护保养，这需要进行日常清洁、部件检查以及专业维护以确保下次测试的准确性与安全性。

#### **5. 责任和监督**

操作人员必须经过专业培训，了解设备操作规程并且能够独立操作设备。并且操作人员需要制定应急措施并定期接受安全操作的培训，特别是对于车规级和军工级的应用场景，操作人员的责任更为严格。

除此之外，主管人员还应提供多级监督以确保设备状态可以实时监测和应急预案的有效性。

任务实施

### **1.3.6 老炼测试准备工作操作**

#### **1. 穿戴防静电服**

进入实验室前，根据地面指引进入换衣室，先穿戴好防静电服,防静电帽,防静电鞋子。然后双手佩戴两层防静电手指套，至少三根手指，分别拇指，食指，中指，和戴好防静电手环。最后将防静电手环一端插在工位上，确保人身安全。

#### **2. 产品信息确认**

核对随工单信息与产品是否一致：产品型号，封装，批次，数量，外观等信息。确认无误则在相应位置填写签名。

#### **3. 产品老化板确认**

打开老化板台，根据型号封装搜索老化板位置编码，如 15-B-01。再根据老化板位置编码找到对应的老化板，最后核对老化板详细规范，型号，封装与产品一致，如图 1-3-9 所示。

![](static/GErKbFxdeoAFYgxs6vscDspNnyf.jpeg)

图 1-3-9 确认老化板信息

#### **4. 老化板保险测试**

准备好万用表，将万用表开关拧到蜂鸣档位置。按下蓝色按钮后，确认出现蜂鸣档符号，如图 1-3-10 所示。

![](static/E2slbkYqoo2lPKxZi2zcDjAxnge.png)

图 1-3-10 万用表准备工作

接着确认老化板保险位置。若老化板保险两端无孔洞，则将两只表笔分别贴紧保险两端，发出蜂鸣声为正常；若老化板保险两端有孔洞，则将两只表笔分别贴紧保险两端的孔洞，发出蜂鸣声为正常。如图 1-3-11 所示。

![](static/SzAVbSS18o4wWqxX1FMcVsAdnUb.png)

图 1-3-11 老化板保险测试

#### **5. 老化板短路测试**

黑笔笔尖紧贴 GND 金手指区域固定不动，红笔紧贴 +VCC 金手指区域，无蜂鸣声为正常。再将红笔紧贴 +VMUX 金手指区域，无蜂鸣声为正常。然后将红笔紧贴-VEE 金手指区域，无蜂鸣声为正常。最后将红笔笔尖贴着 +VCC 金手指区域往 GND 一端滑动，滑到-VEE 金手指区域，无蜂鸣声为正常。

#### **6. 产品装载**

首先进行首件确认，即将每批次首只芯片正确放进夹具盖好后，打开夹具取出，交由组内目检人员进行确认，经确认芯片无误后方可进行批量装载。然后根据产品尺寸选取合适的装载工具，优先选取吸笔，如图 1-3-12 所示，然后防滑镊子，最后尖镊子。需要注意的是吸笔不能有破损，且不能有灰尘；防滑子夹取芯片力道适中，力道过小容易掉落，力道过大容易夹飞；尖头镊子一般用于特别小的产品，使用时注意防止划伤芯片。

![](static/GODqbBpvloEWAAxEkYycIvXPnDe.png)

图 1-3-12 磁吸笔

#### **7. 再次老化板保险测试**

操作方法与步骤 4 老化板保险测试相同。

#### **8. 再次老化板短路测试**

操作方法与步骤 5 老化板短路测试相同。

#### **9. 产品装入转运车**

双手平拿老化板，将老化板插入转运车，需要注意的是将金手指方向朝向转运车，且左右两侧的拨字必须相对应，然后查看转运车轮子是否锁住，最后双手推动或拉动转运车到达指定位置并锁住转运车。

### **1.3.7 老炼测试**

### 老炼测试准备工作完成之后，就要进行老炼测试。

#### **1. 开机**

按照相关顺序依次开机。然后打开电脑开关，并翻转集成电路高温动态老化箱的运行状态卡为运行状态，如图 1-3-13 所示。

![](static/PYv8br0YsorAxwxAN42ca0rEnub.png)

图 1-3-13 设备运行状态卡

#### **2. 确认试验条件**

#### 确认老化箱温度和老化箱温度保护设置是否符合产品要求，注意温度保护设置一般比产品试验温度高 10℃，如不符合产品要求，请反馈组长。

#### **3. 选取插槽**

点击电脑桌面，打开软件。根据随工单的信息来选择对应的程序。首先点击参数设置，如图 1-3-14 所示。

![](static/OVQEbZvRtoB9yXxYRgocQJown3W.png)

图 1-3-14 点击参数设置

本次试验产品信息为：产品型号 HWD3232-A；产品封装 CSOP16；实验条件：125℃，160h。具体点开的的参数设置如图 1-3-15 所示。在设置时还需注意操作人员需要根据随工单选取对应的器件库文件夹和器件程序，如图 1-3-16 所示。最后，需要确认试验箱温度上限是否符合要求，有问题的话进行修改，若无问题可点击发送。在本次实验时，就需将 145℃ 改为 135℃。至此，老炼程序设置完成。

![](static/LOPobd1vRoKWHcxhVChc63bIn9s.png)

