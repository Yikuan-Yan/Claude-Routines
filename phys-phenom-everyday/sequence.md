# 120-Day Physics Phenomenon Sequence

Pre-designed sequence ensuring no repetition, thematic coherence between adjacent days,
and systematic rotation across all subfields. Days are grouped into thematic arcs of 3-5 days,
with deliberate bridge connections between arcs.

Day 1 (glass transparency) is already completed.

## How to use this file

- When the user says "今天的物理现象" without a Day number, use `conversation_search` to find
  the most recent Day N they completed, then deliver Day N+1.
- When the user says "Day N", deliver that specific day.
- When the user says "换一个", skip to the next day in the sequence.
- When the user says "来个和X有关的", find the nearest future day matching that theme,
  deliver it, then resume the main sequence from where they left off.
- Each entry below gives: Day number, title, subfield tag, thematic arc, and a one-line
  bridge note explaining the connection to the previous day.

---

## Arc 1: Light & Matter (Days 1-4)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 1 | 为什么玻璃是透明的？ | Condensed matter / Optics | — (序列起点) |
| 2 | 为什么天空是蓝的，但日落是红的？ | Optics / Atmospheric | Day 1 讲了光穿过物质；Day 2 问光穿过大气时发生了什么——同样是光-物质相互作用，但机制从带隙吸收变成了 Rayleigh 散射 |
| 3 | 为什么彩虹是弧形的，而且你永远走不到它脚下？ | Optics / Geophysics | Day 2 的散射是波长选择的；Day 3 的彩虹也是波长选择的，但机制从散射变成了折射+内反射+色散 |
| 4 | 为什么肥皂泡是彩色的？ | Optics / Soft matter | Day 3 的色散分光；Day 4 的薄膜干涉——都是"白光被分解成彩色"，但一个靠折射率色散，一个靠几何路径差 |

## Arc 2: Surface & Interface (Days 5-8)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 5 | 为什么水滴是球形的（小的时候）？ | Soft matter / Fluid dynamics | Day 4 的肥皂泡也是球形的——表面张力最小化表面积。Day 5 深入问：为什么表面张力存在？ |
| 6 | 为什么湿了的头发会粘在一起？ | Soft matter / Capillarity | Day 5 的表面张力；Day 6 问它在毛细尺度上如何产生力——弯月面、Laplace 压差、毛细桥 |
| 7 | 为什么树能把水送到几十米高？ | Biophysics / Fluid dynamics | Day 6 的毛细作用；Day 7 问它能走多远——内聚力-张力理论，水柱负压，木质部的纳米级管道 |
| 8 | 为什么荷叶上的水珠是完美的球？ | Soft matter / Materials | Day 7 的水和植物；Day 8 问植物如何操控润湿性——超疏水表面、Cassie-Baxter 态、接触角 |

## Arc 3: Heat & Disorder (Days 9-12)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 9 | 为什么湿衣服晾干时你会觉得冷？ | Thermodynamics | Day 8 的水和表面；Day 9 问水离开表面时带走了什么——蒸发冷却、潜热、Maxwell-Boltzmann 高能尾 |
| 10 | 为什么你能在远处闻到咖啡的味道？ | Statistical mechanics | Day 9 的分子逃逸；Day 10 问分子在空气中如何传播——扩散、随机行走、为什么扩散慢得出人意料 |
| 11 | 为什么搅拌咖啡里的奶很容易，但"反搅"不行？ | Thermodynamics / Nonlinear | Day 10 的扩散；Day 11 问为什么扩散不可逆——熵增、相空间体积、Loschmidt 悖论 |
| 12 | 为什么冰箱背面是热的？ | Thermodynamics | Day 11 的不可逆性；Day 12 问如何强制让热"逆流"——Carnot 循环、制冷系数、热力学第二定律的代价 |

## Arc 4: Phase Transitions (Days 13-16)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 13 | 为什么水结冰时体积会膨胀？ | Condensed matter / Thermo | Day 12 的冰箱制冷；Day 13 问被冷却的水在 0°C 发生了什么——氢键网络、冰的异常密度、湖泊冬季生态 |
| 14 | 为什么你能过冷水但很难过热水？ | Thermo / Nonlinear dynamics | Day 13 的水结冰；Day 14 问为什么水可以不结冰——成核理论、能量势垒、亚稳态 |
| 15 | 为什么高压锅能更快煮熟食物？ | Thermo | Day 14 的相变势垒；Day 15 问压力如何改变沸点——Clausius-Clapeyron 方程、相图的斜率 |
| 16 | 为什么没有人见过临界乳光之后的"第四种水"？ | Condensed matter / Thermo | Day 15 的相图；Day 16 走到相图的终点——临界点、临界乳光、标度律、普适性 |

## Arc 5: Sound & Vibration (Days 17-20)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 17 | 为什么雷声隆隆而不是一声巨响？ | Waves / Atmospheric | Day 16 的临界现象在宏观尺度；Day 17 回到日常——声音在大气中的传播、温度梯度折射、雷电的几何延迟 |
| 18 | 为什么你在浴室唱歌声音更好？ | Waves / Acoustics | Day 17 的声传播；Day 18 问声音在封闭空间的行为——驻波、共振频率、混响时间 |
| 19 | 为什么小提琴和钢琴弹同一个音听起来不同？ | Waves / Acoustics | Day 18 的共振；Day 19 问基频相同时音色差异从何而来——泛音谱、Fourier 分析、弦的边界条件 |
| 20 | 为什么玻璃杯加水后音调变低？ | Waves / Fluid dynamics | Day 19 的振动模式；Day 20 问流体如何改变固体振动——耦合振子、附加质量效应、杯沿驻波 |

## Arc 6: Electricity in Everyday Life (Days 21-24)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 21 | 为什么冬天脱毛衣会噼里啪啦？ | Electromagnetism | Day 20 的杯沿振动；Day 21 跳到另一种日常"噼啪"——静电放电、摩擦起电、击穿电场 |
| 22 | 为什么闪电是锯齿形的？ | Electromagnetism / Plasma | Day 21 的放电；Day 22 问大尺度放电如何选择路径——逐步击穿、随机分支、分形维数 |
| 23 | 为什么鸟站在高压线上不会触电？ | Electromagnetism | Day 22 的高电压；Day 23 问电压差如何决定电流通路——等势体、并联电阻、跨步电压 |
| 24 | 为什么手机充电时会发热？ | Electromagnetism / Thermo | Day 23 的电流；Day 24 问电流流过电阻时发生什么——Joule 加热、锂电池的内阻与电化学、充电效率 |

## Arc 7: Magnetism & Spin (Days 25-28)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 25 | 为什么磁铁能隔着桌子吸回形针？ | Electromagnetism | Day 24 的电；Day 25 问电和磁的另一面——铁磁性、磁畴、为什么只有少数元素是铁磁的 |
| 26 | 为什么磁铁加热到一定温度就失效了？ | Condensed matter / Stat mech | Day 25 的铁磁性；Day 26 问温度如何摧毁有序——Curie 温度、Ising 模型、自发对称破缺 |
| 27 | 为什么 MRI 能看到你体内的软组织？ | Quantum / Biophysics | Day 26 的自旋有序；Day 27 问个体自旋如何被探测——核磁共振、Larmor 进动、弛豫时间对比度 |
| 28 | 为什么指南针指向北方（但不是正北）？ | Geophysics / EM | Day 27 的磁场；Day 28 问地球磁场从何而来——地核发电机理论、磁偏角、地磁逆转 |

## Arc 8: Gravity & Orbits (Days 29-32)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 29 | 为什么宇航员在太空站里"失重"但没有离开地球引力？ | Classical mechanics | Day 28 的地球物理；Day 29 问地球引力在轨道上的行为——自由落体参考系、等效原理、潮汐力 |
| 30 | 为什么月球总是同一面朝着我们？ | Classical mechanics / Astro | Day 29 的轨道力学；Day 30 问为什么自转被锁定——潮汐锁定、潮汐耗散、同步旋转的时间标度 |
| 31 | 为什么土星有环但地球没有？ | Astrophysics | Day 30 的潮汐力；Day 31 问潮汐力何时能撕碎卫星——Roche 极限、环的起源与稳定性 |
| 32 | 为什么 GPS 需要修正相对论效应？ | Relativity | Day 31 的轨道；Day 32 问高轨道上的时钟为什么走得不一样——引力红移、狭义相对论时间膨胀、38 μs/天的校正 |

## Arc 9: Quantum Weirdness (Days 33-37)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 33 | 为什么太阳的光谱上有暗线？ | Quantum / Astro | Day 32 的 GPS 频率修正；Day 33 问频率的量子化起源——原子吸收线、Bohr 模型、Fraunhofer 线 |
| 34 | 为什么霓虹灯是红色的而钠灯是黄色的？ | Quantum / Atomic | Day 33 的原子谱线；Day 34 问不同元素为什么发不同颜色——电子能级结构、选择定则 |
| 35 | 为什么隧道二极管能让电子穿过本不该穿过的势垒？ | Quantum | Day 34 的量子能级；Day 35 问量子力学最反直觉的预言——量子隧穿、衰减波函数、隧穿概率的指数敏感性 |
| 36 | 为什么铀-238 的半衰期是 45 亿年？ | Nuclear / Quantum | Day 35 的隧穿；Day 36 问隧穿在核物理中的角色——α 衰变 Gamow 模型、库仑势垒、半衰期的巨大变化范围 |
| 37 | 为什么量子计算机不只是"更快的经典计算机"？ | Quantum information | Day 36 的量子态；Day 37 问量子叠加和纠缠如何被利用——qubit、量子并行性、退相干为什么是大敌 |

## Arc 10: Friction & Contact (Days 38-41)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 38 | 为什么冰面滑而普通地面不滑？ | Condensed matter / Mechanics | Day 37 的量子世界；Day 38 回到经典——冰的表面预熔层、接触力学、摩擦的微观起源 |
| 39 | 为什么轮胎在湿路面上更容易打滑？ | Fluid dynamics / Mechanics | Day 38 的摩擦；Day 39 问水膜如何破坏摩擦——水动力润滑、挤压膜效应、轮胎花纹的物理学 |
| 40 | 为什么壁虎能在天花板上行走？ | Biophysics / EM | Day 39 的表面接触；Day 40 问微观接触如何产生宏观粘附——van der Waals 力、刚毛的分形层级、接触分裂原理 |
| 41 | 为什么胶带在黑暗中撕开时会发光？ | Condensed matter / EM | Day 40 的粘附；Day 41 问撕裂粘附界面时发生了什么——摩擦发光、电荷分离、甚至能产生 X 射线 |

## Arc 11: Fluids in Motion (Days 42-45)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 42 | 为什么蜂蜜倒出来会盘绕成圈？ | Fluid dynamics | Day 41 的界面力学；Day 42 问粘性流体的自由表面行为——液体绳卷效应、惯性-粘性-重力竞争 |
| 43 | 为什么在浴缸放水时总会形成漩涡？ | Fluid dynamics | Day 42 的粘性流；Day 43 问旋转从何而来——角动量守恒与放大、Coriolis 效应（及其被高估的程度） |
| 44 | 为什么飞机能飞？（不，不是因为"上方路径更长"） | Fluid dynamics / Mechanics | Day 43 的涡旋；Day 44 问环量如何产生升力——Kutta 条件、Joukowski 变换、真正的升力起源 |
| 45 | 为什么高尔夫球有凹坑？ | Fluid dynamics | Day 44 的绕流；Day 45 问粗糙表面如何减小阻力——边界层湍流转捩、分离点延迟、阻力危机 |

## Arc 12: Waves Beyond Sound & Light (Days 46-49)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 46 | 为什么地震的 P 波和 S 波到达时间不同？ | Geophysics / Waves | Day 45 的流体力学；Day 46 从流体波到固体波——纵波vs横波、地球内部分层的声学断层扫描 |
| 47 | 为什么海啸在深海几乎感觉不到？ | Fluid dynamics / Waves | Day 46 的波传播；Day 47 问浅水波和深水波的本质区别——色散关系、群速度、能量守恒如何让浅水区波幅暴增 |
| 48 | 为什么老式电视没信号时满屏雪花？ | Astrophysics / EM | Day 47 的波传播；Day 48 问电磁波的宇宙学背景——CMB 辐射、大爆炸的余晖、2.7 K 黑体谱 |
| 49 | 为什么微波炉加热不均匀？ | EM / Waves | Day 48 的电磁波；Day 49 问驻波如何在日常中制造麻烦——微波腔的模式、波节处冷点、转盘的物理学 |

## Arc 13: Nuclear & Stellar (Days 50-53)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 50 | 为什么太阳能燃烧几十亿年而不熄灭？ | Nuclear / Astro | Day 49 的微波能量；Day 50 问最强的能量源——pp 链反应、隧穿速率控制的燃烧、Kelvin-Helmholtz 时标为什么太短 |
| 51 | 为什么铁是恒星核合成的终点？ | Nuclear / Astro | Day 50 的核聚变；Day 51 问为什么不能一直聚变下去——结合能曲线的极值、铁峰、铁之后的元素从何而来 |
| 52 | 为什么香蕉有微弱的放射性？ | Nuclear | Day 51 的核物理；Day 52 回到日常——K-40 衰变、天然放射性本底、"香蕉等效剂量"与辐射恐惧的校准 |
| 53 | 为什么碳-14 能测定古物年龄？ | Nuclear / Geophysics | Day 52 的放射性衰变；Day 53 问衰变如何成为时钟——放射性定年、指数衰减、宇宙线产生 C-14 的稳态 |

## Arc 14: Materials & Structure (Days 54-57)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 54 | 为什么钻石和铅笔芯是同一种元素？ | Condensed matter | Day 53 的碳同位素；Day 54 问碳的不同面目——晶体结构、sp² vs sp³ 杂化、为什么结构决定性质 |
| 55 | 为什么金属能弯曲而陶瓷一弯就碎？ | Condensed matter / Mechanics | Day 54 的晶体结构；Day 55 问结构如何决定力学——位错滑移、脆性vs延性、Griffith 裂纹 |
| 56 | 为什么回形针弯来弯去会断？ | Mechanics / Materials | Day 55 的塑性变形；Day 56 问反复变形为什么致命——金属疲劳、位错堆积、S-N 曲线、Comet 客机空难 |
| 57 | 为什么记忆合金能"记住"形状？ | Condensed matter | Day 56 的金属变形；Day 57 问变形能否可逆——马氏体相变、形状记忆效应、超弹性 |

## Arc 15: Light-Matter Frontier (Days 58-61)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 58 | 为什么 LED 比白炽灯节能得多？ | Quantum / Condensed matter | Day 57 的材料科学；Day 58 问半导体如何发光——p-n 结、电致发光 vs 热辐射、Planck 效率极限 |
| 59 | 为什么激光笔的光束不会散开？ | Optics / Quantum | Day 58 的发光；Day 59 问受激辐射如何产生相干光——Einstein A/B 系数、粒子数反转、衍射极限束宽 |
| 60 | 为什么光纤能拐弯传光而水管拐弯会损失水？ | Optics | Day 59 的激光在光纤中的应用；Day 60 问全内反射如何引导光——波导模式、倏逝波、弯曲损耗 |
| 61 | 为什么防晒霜能阻挡紫外线？ | Optics / Chemistry | Day 60 的光引导；Day 61 问紫外吸收的分子机制——π-π* 跃迁、TiO₂ 纳米粒子散射、SPF 的物理含义 |

## Arc 16: Rotation & Angular Momentum (Days 62-65)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 62 | 为什么花样滑冰选手收手时转得更快？ | Classical mechanics | Day 61 的分子结构；Day 62 回到宏观——角动量守恒、转动惯量的变化、从 2 rps 到 6 rps |
| 63 | 为什么陀螺不倒？ | Classical mechanics | Day 62 的旋转；Day 63 问旋转如何产生稳定性——进动、角动量的矢量性、Euler 方程 |
| 64 | 为什么自行车骑起来比停着稳？ | Classical mechanics / Nonlinear | Day 63 的旋转稳定性；Day 64 问是不是陀螺效应——轮子的角动量贡献其实很小、前叉几何、自稳的真正机制 |
| 65 | 为什么扔出的名片会翻转（Dzhanibekov 效应）？ | Classical mechanics | Day 64 的旋转；Day 65 问中间轴旋转为什么不稳定——Euler 方程的三个特征频率、能量-角动量椭球交线 |

## Arc 17: Chaos & Patterns (Days 66-69)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 66 | 为什么天气预报超过两周就不准了？ | Nonlinear dynamics / Atmospheric | Day 65 的不稳定性；Day 66 问不稳定性如何限制预测——Lorenz 系统、Lyapunov 指数、蝴蝶效应 |
| 67 | 为什么心脏的跳动不是完美周期的？ | Biophysics / Nonlinear | Day 66 的混沌；Day 67 问混沌在生物系统中的角色——心率变异性、健康心脏更"混沌"、分岔和心颤 |
| 68 | 为什么沙丘有规则的间距？ | Nonlinear / Geophysics | Day 67 的生物节律；Day 68 问非生命系统如何自组织——沙波纹、风-沙反馈、最不稳定波长 |
| 69 | 为什么斑马有条纹？ | Biophysics / Nonlinear | Day 68 的自组织图案；Day 69 问生物图案形成——Turing 不稳定性、反应扩散方程、形态发生 |

## Arc 18: Thermal Radiation (Days 70-73)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 70 | 为什么铁块加热后先变红再变白？ | Thermo / Optics | Day 69 的生物颜色；Day 70 问无机物的颜色——黑体辐射、Wien 位移定律、为什么经典物理在这里失败（紫外灾难） |
| 71 | 为什么保温瓶能保温这么久？ | Thermo | Day 70 的热辐射；Day 71 问如何同时阻断三种热传递——传导、对流、辐射，以及真空的关键角色 |
| 72 | 为什么夏天黑色衣服比白色更热？ | Thermo / EM | Day 71 的辐射传热；Day 72 问吸收率和发射率的关系——Kirchhoff 定律、为什么最好的吸收体也是最好的辐射体 |
| 73 | 为什么温室效应不是"像温室一样"工作的？ | Atmospheric / Thermo | Day 72 的辐射平衡；Day 73 问大气如何困住热量——选择性吸收vs阻止对流、大气窗口、CO₂ 的 15 μm 吸收带 |

## Arc 19: Pressure & Buoyancy (Days 74-77)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 74 | 为什么吸管能吸水？ | Fluid statics | Day 73 的大气；Day 74 问大气压如何在日常中做功——真空吸力的真相、Torricelli 真空、大气压的定量感受 |
| 75 | 为什么氦气球会飘起来？ | Fluid statics / Thermo | Day 74 的大气压；Day 75 问浮力——Archimedes 定律、密度差、氦气球的最大高度 |
| 76 | 为什么热气球能飞但不能飞太高？ | Fluid statics / Thermo | Day 75 的浮力；Day 76 问加热空气如何产生浮力——理想气体定律、温差与升力、对流层顶的限制 |
| 77 | 为什么深海鱼被捞上来会膨胀？ | Fluid statics / Biophysics | Day 76 的大气压力梯度；Day 77 问水下的极端压力——静水压力、鱼鳔、每 10 米一个大气压 |

## Arc 20: Electricity & Life (Days 78-81)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 78 | 为什么你的神经信号传导速度只有 100 m/s？ | Biophysics / EM | Day 77 的生物在极端环境；Day 78 问生物电——动作电位、离子通道、髓鞘如何加速传导 |
| 79 | 为什么电鳗能放电 860 伏？ | Biophysics / EM | Day 78 的生物电；Day 79 问生物如何产生高电压——电板细胞的串联、阻抗匹配、为什么能电晕马 |
| 80 | 为什么心脏的 ECG 能在皮肤表面被测到？ | Biophysics / EM | Day 79 的生物电传导；Day 80 问电信号如何穿过组织——体积导体理论、Einthoven 三角、心电图的物理 |
| 81 | 为什么触摸屏知道你摸了哪里？ | EM / Materials | Day 80 的电场探测；Day 81 问电容式触摸的原理——人体作为导体、互电容矩阵、多点触控 |

## Arc 21: Oscillations & Resonance (Days 82-85)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 82 | 为什么秋千要在最低点蹬腿？ | Classical mechanics | Day 81 的触摸交互；Day 82 回到基础力学——参数共振、变惯量振荡器、为什么频率要匹配 |
| 83 | 为什么军队过桥要便步走？ | Waves / Mechanics | Day 82 的共振；Day 83 问共振何时致命——Tacoma Narrows 桥、强迫振动的振幅发散、阻尼的关键角色 |
| 84 | 为什么你能听到海螺里的"大海声"？ | Acoustics | Day 83 的共振；Day 84 问空腔共振——Helmholtz 共振器、宽频噪声的选频放大、人耳道也是一个共振腔 |
| 85 | 为什么荡秋千的小孩和钟摆的周期一样？ | Classical mechanics | Day 84 的共振频率；Day 85 问为什么单摆周期与质量无关——等时性、小角近似什么时候破坏、摆钟的精度极限 |

## Arc 22: Optics & Perception (Days 86-89)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 86 | 为什么沙漠里会看到海市蜃楼？ | Optics / Atmospheric | Day 85 的周期运动；Day 86 跳到光学——温度梯度折射率、Snell 定律的连续版本、弯曲光线 |
| 87 | 为什么水中的勺子看起来是弯的？ | Optics | Day 86 的折射；Day 87 问简单折射——Snell 定律、视深度、为什么鱼不在你看到的位置 |
| 88 | 为什么偏振太阳镜能减少路面反光？ | Optics / EM | Day 87 的光在界面的行为；Day 88 问反射光的偏振——Brewster 角、Fresnel 方程、LCD 屏幕的偏振原理 |
| 89 | 为什么你的眼睛能在极暗环境下看到单个光子？ | Biophysics / Quantum | Day 88 的光探测；Day 89 问生物光探测器的极限——视紫红质异构化、单光子信噪比、暗计数率 |

## Arc 23: Scaling Laws (Days 90-93)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 90 | 为什么大象不能跳而跳蚤能跳自身身高的 100 倍？ | Biophysics / Mechanics | Day 89 的生物物理；Day 90 问尺度如何改变一切——面积-体积标度律、肌肉力正比截面积 |
| 91 | 为什么蚂蚁掉下桌子不会摔死？ | Mechanics / Fluid dynamics | Day 90 的标度律；Day 91 问空气阻力如何随尺度变化——终端速度正比 √(m/A)、小动物的低终端速度 |
| 92 | 为什么小老鼠心跳比蓝鲸快得多？ | Biophysics / Thermo | Day 91 的尺度效应；Day 92 问代谢率的标度——Kleiber 定律 M∝m^(3/4)、表面积散热限制、寿命标度 |
| 93 | 为什么煮鸡蛋的时间不是和大小成正比？ | Thermo / Transport | Day 92 的标度；Day 93 问热传导的标度——扩散方程的时间标度 t∝L²、为什么大物体热得更慢、Biot 数 |

## Arc 24: Quantum Materials (Days 94-97)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 94 | 为什么有些材料电阻为零（超导体）？ | Condensed matter / Quantum | Day 93 的输运；Day 94 问电输运的极限——Cooper 对、BCS 理论的物理图像、Meissner 效应 |
| 95 | 为什么超导磁悬浮列车能浮起来？ | Condensed matter / EM | Day 94 的超导；Day 95 问 Meissner 效应如何产生悬浮——磁通排斥、磁通钉扎、Type I vs Type II |
| 96 | 为什么半导体能被"掺杂"成导体？ | Condensed matter / Quantum | Day 95 的量子材料；Day 96 回到更常见的量子材料——带隙、施主/受主能级、p-n 结整流 |
| 97 | 为什么石墨烯如此特殊？ | Condensed matter | Day 96 的能带结构；Day 97 问二维材料的电子行为——狄拉克锥、赝自旋、为什么载流子像无质量费米子 |

## Arc 25: Cosmological (Days 98-101)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 98 | 为什么夜空是黑暗的？（Olbers 悖论） | Astrophysics / Cosmology | Day 97 的基础物理；Day 98 问一个看似天真的问题——有限宇宙年龄、膨胀红移、光子地平线 |
| 99 | 为什么遥远星系的光是红移的？ | Cosmology | Day 98 的宇宙膨胀；Day 99 问如何直接观测膨胀——Hubble 定律、宇宙学红移 vs 多普勒红移 |
| 100 | 为什么宇宙大爆炸不是"某处的爆炸"？ | Cosmology | Day 99 的膨胀；Day 100 问膨胀的几何——没有中心的膨胀、葡萄干面包类比的局限、度规的膨胀 |
| 101 | 为什么暗物质"必须"存在（即使我们看不到它）？ | Cosmology / Astrophysics | Day 100 的宇宙学；Day 101 问引力透镜和旋转曲线为什么迫使我们接受看不见的物质——缺失质量问题、子弹星团 |

## Arc 26: Thermodynamics Depth (Days 102-105)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 102 | 为什么永动机不可能？ | Thermo | Day 101 的宇宙能量；Day 102 回到基础——第一类和第二类永动机、Carnot 效率上限、信息熵与 Landauer 原理 |
| 103 | 为什么你不能把一个鸡蛋"解炒"？ | Thermo / Stat mech | Day 102 的不可逆性；Day 103 深入——微观可逆性与宏观不可逆性的矛盾、Boltzmann H 定理、粗粒化 |
| 104 | 为什么激光冷却能把原子冻到接近绝对零度？ | Quantum / Atomic | Day 103 的温度与微观运动；Day 104 问如何用光减速原子——多普勒冷却、光子反冲力、低温极限 |
| 105 | 为什么绝对零度永远到不了？ | Thermo / Quantum | Day 104 的冷却极限；Day 105 问第三定律——Nernst 定理、低温时熵的行为、为什么最后一步无穷难 |

## Arc 27: Elastic Waves & Materials (Days 106-109)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 106 | 为什么铃声清脆而木块声沉闷？ | Acoustics / Materials | Day 105 的固态物理；Day 106 问材料如何决定声音——品质因子 Q、内耗机制、木材 vs 金属 vs 玻璃 |
| 107 | 为什么超声波能给胎儿做检查？ | Acoustics / Biophysics | Day 106 的声波在固体中；Day 107 问声波在软组织中的传播——阻抗失配反射、B 超成像原理 |
| 108 | 为什么声波在水中传播比空气中快 4 倍？ | Waves / Fluid dynamics | Day 107 的声速；Day 108 问声速由什么决定——Newton-Laplace 方程、体弹性模量 vs 密度的竞争 |
| 109 | 为什么协和飞机有音爆而亚音速飞机没有？ | Waves / Fluid dynamics | Day 108 的声速；Day 109 问超过声速时波前发生了什么——Mach 锥、激波、为什么音爆是锥面而不是球面 |

## Arc 28: Randomness & Statistics (Days 110-113)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 110 | 为什么放射性衰变的时间是随机的？ | Quantum / Nuclear | Day 109 的波动力学；Day 110 问量子力学中的根本随机性——泊松过程、半衰期的统计性质、Einstein 的不满 |
| 111 | 为什么布朗运动证明了原子的存在？ | Statistical mechanics | Day 110 的随机过程；Day 111 问热涨落——Einstein 1905 年的工作、均方位移∝t、Avogadro 数的测定 |
| 112 | 为什么大数据的统计直觉经常是错的？ | Statistical mechanics / Info | Day 111 的统计；Day 112 问统计悖论——Simpson 悖论、回归均值、小样本谬误与物理实验设计 |
| 113 | 为什么白噪声听起来像瀑布？ | Waves / Stat mech | Day 112 的统计；Day 113 问噪声的频谱——白噪声 vs 粉红噪声 vs 1/f 噪声、功率谱密度、热噪声的 Nyquist 定理 |

## Arc 29: Plasma & Extreme States (Days 114-117)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 114 | 为什么火焰是热的？（不，不只是"化学反应放热"） | Plasma / Thermo | Day 113 的热涨落；Day 114 问火焰的物理——等离子体边缘、自由基链式反应、为什么火焰有形状 |
| 115 | 为什么极光是绿色和红色的？ | Plasma / Atmospheric | Day 114 的等离子体发光；Day 115 问高层大气等离子体——太阳风磁重联、O 和 N₂ 的激发态发射线 |
| 116 | 为什么闪电温度比太阳表面还高？ | Plasma / EM | Day 115 的大气等离子体；Day 116 问等离子体通道的物理——电阻加热、30000 K 通道、空气快速膨胀产生雷声 |
| 117 | 为什么受控核聚变这么难？ | Plasma / Nuclear | Day 116 的高温等离子体；Day 117 问为什么约束等离子体如此困难——Lawson 判据、磁约束的不稳定性、60 年追逐的物理原因 |

## Arc 30: Grand Finale — Physics of Information (Days 118-120)

| Day | Title | Subfield | Bridge |
|-----|-------|----------|--------|
| 118 | 为什么擦除信息需要消耗能量？ | Thermo / Information | Day 117 的能量约束；Day 118 问信息的物理代价——Landauer 原理、kT ln2、Maxwell 妖的热力学解决 |
| 119 | 为什么黑洞有熵？ | Cosmology / Quantum / Thermo | Day 118 的信息与热力学；Day 119 问引力如何和信息纠缠——Bekenstein-Hawking 熵、全息原理的暗示 |
| 120 | 为什么物理学还没有完成？ | All subfields | Day 119 的前沿；Day 120 是总结——量子引力的缺口、暗能量、意识的物理学、测量问题——一张未完成的地图，指向继续探索的方向 |
