---
layout: default
title: 范坤鹏的个人主页
---

# 你好，我是范坤鹏

## 基本信息

- **姓名**: 范坤鹏
- **生日**: 2005-6-24
- **联系方式**:
  - QQ:2964924015
  - 微信：qq2964924015
  - 邮箱：2023112091@my.swjtu.edu.cn

---

##  我的教育背景——西南交通大学 \| 通信工程 \| 本科（2023.09 - 至今）



- **核心学业数据（前五学期）**
  
  | 课程均分 | 绩点 (GPA) | 专业排名 |
  | :--- | :--- | :--- |
  | **91.44** | **3.78** | **8 / 137** |
  
- **获得证书**
  
  | 英语四级 (CET-4) | 英语六级 (CET-6) | 计算机二级 (C语言) |
  | :--- | :--- | :--- |
  | **540** | **464** | **优秀** |
  
- **主修课程**: 
嵌入式系统设计与应用、模拟电子技术、数字电子技术、电路分析、电子系统设计与实践、计算机组成原理、计算机网络、信号与系统、信息论与编码、人工智能算法基础、复变函数与积分变换、数字信号处理、电磁场理论、计算机程序设计等

- **研究兴趣**:
  - 智能机器人与群体智能系统
  - 机器人控制技术
  - 机器人集群协同控制
  - 嵌入式系统

👉 [**查看我的详细教育经历与竞赛奖项**](details.md)

---

## 个人优势

以下是我在学术与实践中积累的核心竞争力：

- **学习能力突出**：在校总成绩位居前列，具备扎实的专业理论基础；
- **团队协作经验**：曾担任校机器人队电控组长及社团主席，拥有高效的团队沟通与组织协调能力；
- **工程实践能力**：积极投身于机器人领域各类高水平竞赛与科研项目，积累了丰富的工程调试经验；
- **抗压与解决问题能力**：具备在压力环境下独立分析并解决复杂工程问题的能力，能够快速适应高强度的科研节奏。

---

##  核心技能

### 编程语言
<p>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
</p>

### 嵌入式控制
<p>
  <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white">
  <img src="https://img.shields.io/badge/FPGA-792B48?style=for-the-badge&logo=xilinx&logoColor=white">
  <img src="https://img.shields.io/badge/ESP32-E65282?style=for-the-badge&logo=espressif&logoColor=white">
  <img src="https://img.shields.io/badge/FreeRTOS-00A9E0?style=for-the-badge&logo=freertos&logoColor=white">
</p>

### 工具与工程
<p>
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white">
  <img src="https://img.shields.io/badge/Keil5-487625?style=for-the-badge&logo=arm&logoColor=white">
  <img src="https://img.shields.io/badge/CLion-143157?style=for-the-badge&logo=clion&logoColor=white">
  <img src="https://img.shields.io/badge/MATLAB-ED7123?style=for-the-badge&logo=matlab&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white">
  <img src="https://img.shields.io/badge/嘉立创-1C77E8?style=for-the-badge&logo=microchip&logoColor=white">
</p>

---

## 科研项目
-✨ [第二十四届全国大学生机器人大赛ROBOCON]
<p align="center">
  <img src="../25RC合影.jpg" alt="合影照片" width="400"/>
</p>   
  - 项目简介：围绕“飞身上篮”赛季主题，研发高度自主协同机器人系统。实现机器人在复杂赛场下自动取球、高精度传接球、高速运球及全自动投射，攻克了高动态工况下机构控制精度、全空间实时定位及多机协同动作等工程难题。
    - 系统架构与硬件驱动： 基于 STM32 设计分布式控制架构，通过 CAN 总线调度 10 枚异构电机。融合了大疆电机、达妙电机与 VESC 驱动器，将控制周期稳定在 1ms，确保底层执行层的高带宽响应。
    - 运动控制与算法优化： 完成 4 全向轮底盘 逆运动学建模，设计带前馈补偿的改进型 PID 算法。结合高频 IMU 反馈实时解算位姿，在 3m/s 高速移动中有效补偿底盘打滑，确保路径跟踪偏差控制在 2cm 以内。
    - 数据处理与精准定位： 构建基于环形缓冲队列的异步数据流处理框架，解决了数据延迟与粘包丢包问题。通过插值算法融合码盘与激光雷达数据，消除通信延迟与非同步误差，实现全空间高精度实时定位。
    - 高动态射击系统优化： 针对赛季“飞身上篮”需求，采用 VESC 电调控制无刷电机驱动高速摩擦轮方案。利用 VESC 的高频采样特性实现了高精度的转速闭环控制，显著提升了射球初速度的稳定性与一致性，支撑机器人实现全自动化、高频率的精准投射。

  
-✨ [国家级大学生创新训练计划项目“基于矢量底盘的多功能篮球训练机器人”]
  - 简要描述：

-✨ [全国大学生创新年会 “球类辅助训练与物资运送一体化机器人” ]
<p align="center">
  <img src="../创新年会合影.jpg" alt="合影照片" width="400"/>
</p>  
  - 简要描述：
---
[我的 GitHub 主页](https://github.com/boli235)
