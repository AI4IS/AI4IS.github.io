---
layout: archive
title: "个人简历"
permalink: /cv_zh/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## 0. 自我介绍

- 2018.09 - 2022.06, 西北工业大学, 学士, 探测制导与控制技术, 10th/65
  - 论文：基于分层强化学习的无人机空战决策研究
  - 绩点：3.463/4
  - 理论力学、自动控制原理、计算方法课程满分

- 2022.09 - 至今，西北工业大学，硕士，控制科学与工程, 1st/16（保研）
  - 论文：基于强化学习的编队协同控制与对抗
  - 加权平均成绩：90.61/100
  - 雅思成绩：6.5 （小分>=6.0)

研究兴趣：深度强化学习、计算机视觉、智能系统、无人机、机器人、控制系统、博弈论

个人主页：https://ai4is.github.io

## 1. 联系

| 姓名   | 所在机构                 | 关系                    |
| ------ | ------------------------ | ----------------------- |
| 张建东 | 西北工业大学电子信息学院 | 硕士研究生导师          |
| 徐钊   | 西北工业大学电子信息学院 | 同一研究团队            |
| 胡劲文 | 西北工业大学自动化学院   | 共同发表ICCA会议一篇    |
| 李晓聪 | A*STAR SIMTech           | A*STAR SINGA奖学金 主管 |

## 2. 自身优势

### 2.1. 论文

#### 2.1.1. 国际期刊/会议

| 论文标题                                                     | 期刊名称                                                     | 发表年份 | 影响因子 | JCR分区 | 作者列表                                                     | 作者顺序 | 被引数量 | 荣誉                                                  | 是否主要贡献 | 本人贡献概述                                                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------- | -------- | ------- | ------------------------------------------------------------ | -------- | -------- | ----------------------------------------------------- | ------------ | ------------------------------------------------------------ |
| An Autonomous Attack Decision-Making Method Based on Hierarchical Virtual Bayesian Reinforcement Learning | IEEE Transactions on Aerospace and Electronic Systems        | 2024     | 5.1      | Q1      | Dinghan Wang, Jiandong Zhang, Qiming Yang, Jieling Liu, Guoqing Shi, Yaozhong Zhang | 共一第一 | 1        |                                                       | 是           | 负责空战自主攻防算法的研究与高保真仿真。主要提出了：1. 一种‘分层虚拟贝叶斯强化学习’方法；2. 一种基于自我博弈的训练算法。以实现在携带导弹的情况下，利用贝叶斯方法与融合先验信息，提升虚拟导弹命中数量预测的准确度，并通过分层方法分解优化目标，避免了训练无法收敛的问题。另外，通过开发一种基于自我博弈的训练算法，大幅提升了模型的泛化性，使其能够应对对手的任何策略。 |
| Loyal wingman task execution for future aerial combat: A hierarchical prior-based reinforcement learning approach | Chinese Journal of Aeronautics                               | 2024     | 5.3      | Q1      | Jiandong Zhang, Dinghan Wang, Qiming Yang, Zhuoyong Shi, Longmeng Ji, Guoqing Shi, Yong Wu | 共一第二 | 2        |                                                       | 是           | 负责忠诚僚机自主任务执行算法的研究与高保真仿真。主要提出了：1. 基于深度强化学习的三种任务算法模型的构建方法：目标搜索模型、目标锁定模型与中继制导模型；2. 一种‘先验化训练，去先验化执行’方法；3. 一种分层控制架构。以实现忠诚僚机的无人化与智能化，赋予无人机在目标脱锁后自主寻回目标的能力，提升系统的鲁棒性，减轻编队长机负担。另外，解决了强化学习在多目标优化任务中训练难，收敛慢的问题。 |
| Intelligent decision-making algorithm for airborne phased array radar search tasks based on a hierarchical strategy framework | Chinese Journal of Aeronautics                               | 2024     | 5.3      | Q1      | Xiaoyang Li, Teng Wang, Dinghan Wang, Hairuo Zhang, Ying Zhou, Deyun Zhou | 学生二作 | 0        | 亮点文章: https://www.youtube.com/watch?v=W593RVSBw3c | 是           | 与其他实验室合作完成了基于强化学习的机载相控阵雷达目标搜索算法。主要贡献了在该任务下分层模型的构建方法，分别完成目标搜索与雷达参数优化。参与了部分实验过程与程序编写，一部分论文撰写。最终该算法能够在指定区域下快速搜索全部目标，同时优化了底层雷达参数。 |
| Dogfight Advantage Occupancy Method Based on Imperfect Information Self-play | 2024 IEEE International Conference on Control & Automation   | 2024     |          |         | Dinghan Wang, Longmeng Ji, Jingbo Wang, Zhuoyong Shi, Jiandong Zhang, Qiming Yang, Guoqing Shi, Yong Wu, Yan Zhu, Jinwen Hu | 第一作者 | 0        |                                                       | 是           | 负责狗斗自主优势占位算法的研究与高保真仿真。主要提出了一种在不完美信息下进行自我博弈的训练算法，并将狗斗优势占位问题建模为零和博弈问题，该算法能够成功收敛至纳什均衡。 |
| Design of UAV Flight State Recognition System for Multi-sensor Data Fusion | IEEE Sensors Journal                                         | 2024     | 4.3      | Q1      | Zhuoyong Shi, Guoqing Shi, Jiandong Zhang, Dinghan Wang, Tianyue Xu, Longmeng Ji, Yong Wu | 4        | 5        |                                                       |              | 方法可行性探讨。                                             |
| Design of a UAV Trajectory Prediction System Based on Multi-Flight Modes | Drones                                                       | 2024     | 4.4      | Q1      | Zhuoyong Shi, Jiandong Zhang, Guoqing Shi, Longmeng Ji, Dinghan Wang, Yong Wu | 5        | 4        |                                                       |              | 方法可行性探讨。                                             |
| Design of motor skill recognition and hierarchical evaluation system for table tennis players | IEEE Sensors Journal                                         |          | 4.3      | Q1      | Zhuoyong Shi, Yetao Jia, Yong Wu, Kexin Zhang, Longmeng Ji, Dinghan Wang | 6        | 8        |                                                       |              | 方法可行性探讨。                                             |
| Design of motion pattern recognition system based on artificial intelligence methods | 2023 IEEE International Conference on Cyber-physical Social Intelligence | 2023     |          |         | Zhuoyong Shi, Liuming Yang, Yong Wu, Dinghan Wang, JianDong Zhang, Anli Zhang | 4        |          |                                                       |              | 方法可行性探讨。                                             |
| Autonomous Security Evaluation Model for UAV Based on Airborne Information | 2023 IEEE International Conference on Information Communication and Signal Processing | 2023     |          |         | Zhuoyong Shi, Mingyang Liu, Qiming Yang, Jieling Liu, Dinghan Wang, Jiandong Zhang | 5        |          |                                                       |              | 方法可行性探讨。                                             |

#### 2.1.2. 国内期刊/会议

| 论文标题                                     | 期刊名称     | 发表年份 | 是否国内顶刊 | 作者列表                                     | 作者顺序 | 被引数量 | 是否主要贡献 |
| -------------------------------------------- | ------------ | -------- | ------------ | -------------------------------------------- | -------- | -------- | ------------ |
| 基于分层强化学习的无人机空战多维决策         | 兵工学报     | 2023     | 是           | 张建东, 王鼎涵, 杨啟明, 史国庆, 陆屹, 张耀中 | 学生一作 | 2        | 是           |
| 基于一致性群组算法的多无人机自主协同任务分配 | 无人系统技术 | 2021     |              | 马云红, 刘云昊, 杨誉乔, 王鼎涵, 张健         | 4        | 11       |              |

#### 2.1.3. 软著/专利

| 名称                                   | 类型     | 年份 | 作者列表                                                     | 作者顺序 | 是否主要贡献 |
| -------------------------------------- | -------- | ---- | ------------------------------------------------------------ | -------- | ------------ |
| 一种忠诚僚机目标搜索与锁定任务执行方法 | 中国专利 | 2024 | 张建东; 王鼎涵; 纪龙梦; 史国庆; 张耀中; 杨啟明; 郑力会; 吴勇; 朱岩 | 学生一作 | 是           |
| 编队协同认知与决策、控制软件           | 软著     | 2023 | 杨啟明; 王鼎涵; 张建东; 史国庆; 张耀中                       | 学生一作 | 是           |
| 一种航空器大气数据安全监测评价方法     | 中国专利 | 2023 | 张安莉; 石卓勇; 王鼎涵; 谢檬; 李楠; 王娟; 徐微               | 3        |              |

### 2.2. 奖学金

| 名称               | 获得时间 |
| ------------------ | -------- |
| 国家奖学金         | 2024     |
| 一等学业奖学金     | 2024     |
| 一等奖学金         | 2024     |
| 一等学业奖学金     | 2023     |
| 二等奖学金         | 2023     |
| 电子信息学院奖学金 | 2020     |
| 电子信息学院奖学金 | 2019     |

### 2.3. 荣誉称号

| 名称         | 获得时间 |
| ------------ | -------- |
| 优秀毕业生   | 2022     |
| 院优秀学生   | 2021     |
| 优秀毕业设计 | 2022     |
| 优秀共青团员 | 2021     |

### 2.4. 竞赛经历

| 名称                                | 等级           | 成员列表               | 职责 | 获得时间 |
| ----------------------------------- | -------------- | ---------------------- | ---- | -------- |
| 全国研究生电子设计大赛              | 西北赛区二等奖 | 王鼎涵; 纪龙梦; 王腾   | 队长 | 2024     |
| Mathorcup高校数模挑战赛——大数据竞赛 | 全国三等奖     | 王鼎涵; 石卓勇         | 队长 | 2023     |
| 全国研究生电子设计大赛              | 西北赛区一等奖 | 王鼎涵; 纪龙梦; 石卓勇 | 队长 | 2023     |
| 全国研究生电子设计大赛（商业赛道）  | 西北赛区三等奖 | 纪龙梦; 王鼎涵; 石卓勇 |      | 2023     |

### 2.5. 项目经历

| 项目名称                                 | 机构                      | 职责               | 经验与成就                                                   |
| ---------------------------------------- | ------------------------- | ------------------ | ------------------------------------------------------------ |
| 编队智能协同战术决策模型和互操作设计研究 | 成都飞机设计研究所（611） | 学生负责人         | 负责方案撰写，项目实施，团队协调，实现了基于贝叶斯网络的编队协同决策与互操作接口规范设计，最终该项目成功完结。我收获到了如何作为负责人协调整个团队进行合理的任务分配与及时调整，跨平台项目开发与部署，如何开发应用基于DDS的可靠数据通讯等技术，夯实了编程基础。 |
| 对空精度评估                             | 沈阳飞机设计研究所（601） | 学生负责人         | 负责融合系统与数据链系统部分的方案撰写，项目实施以及与其他子系统的协调，实现了多传感器数据时间对准、滑窗与卡尔曼滤波两种数据融合等技术；飞机间，飞机与地面站之间数据链路的仿真构建。最终该项目成功完结。我收获到了如何与其他子系统(雷达、光雷、数据链、惯导、飞仿、大气机、火控）进行联合调试，问题排查，最终通过交流合作一步步完成整个庞大的项目。 |
| 数据融合                                 | 沈阳飞机设计研究所（601） | 仿真系统学生负责人 | 负责对接项目组开发的不同融合算法的数据接口，将融合结果进行实时显示，方便进行数据比对。最终该项目成功完结。我收获了如何使用MFC进行项目开发。 |
| 集群协同分布式系统簇技术研究             | 北京航天智能院            | 技术指导           | 负责进行技术指导。最终该项目成功完结。我收获了更好地与团队进行沟通，将自己的想法以通俗易懂的方式向他人阐述。 |

### 2.6. 参与基金

| 名称                                                         | 号码           |
| ------------------------------------------------------------ | -------------- |
| Natural Science Basic Research Program of Shaanxi            | 2022JQ-593     |
| Key R&D Program of Shaanxi Provincial Department of Science and Technology | 2022GY-089     |
| Aeronautical Science Foundation of China                     | 20220013053005 |
| 研究生创新种子基金                                           |                |

### 2.7. 开源项目

| 名称                                                         | 仓库网址                                                     | 视频网址                                    |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------- |
| Vision-based-Intelligent-Robot-Arm-Game                      | https://github.com/AI4IS/Vision-based-Intelligent-Robot-Arm-Game | https://www.youtube.com/watch?v=U5HBWdTwz8k |
| Intelligent-aircraft-battle-game-sb3-jsbsim-flightgear       | https://github.com/AI4IS/intelligent-aircraft-battle-game-sb3-jsbsim-flightgear | https://www.youtube.com/watch?v=Yg9QV8Y7KQU |
| Vision-based-Reinforcement-learning-control-for-aircraft     | https://github.com/AI4IS/Vision-based-Reinforcement-learning-control-for-aircraft | https://www.youtube.com/watch?v=Rn8_Yru5TRI |
| Multi-Dimensional-Decision-Making-for-UAV-Air-Combat-Based-on-Hierarchical-Reinforcement-Learning | https://github.com/AI4IS/Multi-Dimensional-Decision-Making-for-UAV-Air-Combat-Based-on-Hierarchical-Reinforcement-Learning | https://www.youtube.com/watch?v=hYS2ae7KZPc |
| stablebaselines3_quad_s2r                                    | https://github.com/AI4IS/stablebaselines3_quad_s2r           | https://www.youtube.com/shorts/YWVJsDn2Ia4  |

- Github: https://github.com/AI4IS
- Youtube: https://www.youtube.com/channel/UCJMRNVZrN_c_avI2IKq3GjA

### 2.8. 技能

| 种类      | 名称                                                         |
| --------- | ------------------------------------------------------------ |
| 编程语言  | Python; C; C++; Matlab                                       |
| 前端      | HTML; CSS; JavaScript                                        |
| 云&数据库 | MySQL; 腾讯云; 阿里云; Azure Cloud                           |
| 网络技能  | Docker; NAT(v4&v6); Nginx; HTTP; SSL                         |
| 操作系统  | Windows; Debian; Ubuntu; MacOS; OpenWRT; Proxmox VE          |
| 工具      | PyTorch; OpenCV; OpenDDS; Git; Vim; ROS; LATEX; Ps; Pr; 各类AI工具 |

- 软-硬件全栈DIY服务器，涵盖网络部分；
- 全流程智能避障无人机选配、组装与调试；
- 全流程完整项目代码编写，仿真环境测试与实机部署测试验证；

### 2.9. 学生工作/参与活动

| 条目                                                         |
| ------------------------------------------------------------ |
| 西工大数学建模协会活动部会员                                 |
| 参与未来AI大师国际夏令营暑期研学活动                         |
| 本硕阶段积极参与管理班级事务，均担任班级 心理委员，并在疫情时期担任志愿者搬运物资、 举办线上班会帮助心理辅导 |
| 大学生职业规划课程上分享读研经验                             |
| 作为毕业生代表，为本科生分享学习经验                         |
| 参加校内体育（拔河）活动                                     |
| 班级综测评定小组成员                                         |

