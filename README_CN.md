# Hi 👋

## 🚀 关于我

> 🤖 嵌入式/机器人系统工程师 | AGV/机器人电控系统专家

- 📊 **教育背景**：机械设计制造及自动化 · 山东大学
- 🌐 **个人主页**：https://ts-sound.github.io/
- 📧 **联系邮箱**：tonghansen@foxmail.com | tong.han.sen@outlook.com
- 💼 **专业领域**：多年自动化/嵌入式/机器人开发经验，专注于 AGV/机器人 电气系统设计、控制软件开发及硬件驱动开发

### 核心能力

- 🏗️ **系统架构**：精通 C/C++、Python，熟悉 Linux/STM32 开发环境，掌握 ROS2 框架（调度器/lifecycle/ros_control）
- 🔌 **通信协议**：CAN/CANopen、EtherCAT、Modbus、RS485/232、SPI、MQTT
- 🎯 **运动控制**：差速/双舵轮/阿克曼模型开发，PID/MPC 控制算法，Kalman 滤波算法
- 🤖 **机器人系统**：gomros 核心模块开发（线程池/组件化启动/版本管理），SLAM 等算法集成（GTSAM/Cartographer）
- ⚡ **实时优化**：RT_PREEMPT/Xenomai 实时补丁，Linux 内核调优（锁核定频/内存锁定/网卡直驱）
- 🚀 **DevOps**：Jenkins+Docker+CMake 多架构交叉编译（x64/arm64），组件版本管理与自动化部署

---

## 🏢 工作经历

### 山东亚历山大智能科技有限公司 (2019.06 - 至今)

**职位**：嵌入式/机器人系统工程师

**核心职责**：
1. AGV 电控系统设计：主导磁导航、二维码导航、SLAM 导航 AGV 电气系统设计与开发
2. 控制软件开发：负责 STM32 控制板程序及 Linux 工控机软件开发
3. 硬件驱动开发：电机驱动器、IMU、读码器、磁传感器等设备接入及控制
4. 运动模型开发：差速模型、舵轮模型等运动控制算法实现与调优
5. gomros 系统开发：线程池、组件化启动、组件版本管理等核心模块设计与实现
6. 设备驱动适配：基于 gomros 完成电机、雷达、IMU、RFID 等设备驱动开发
7. 自动化部署平台：搭建 Jenkins + Docker + SVN 多架构交叉编译部署系统
8. Linux EtherCAT 集成：实时内核调优（锁核定频/内存锁定/网卡直驱），抖动 < 10μs
9. 人形机器人集成：关节驱动适配及系统模块集成
10. 无人机集成：PX4 飞控系统适配及集成

---

## 🤺 项目经验

### 工业 AGV 系列项目

| 项目 | 时间 | 职责 |
|------|------|------|
| 华盛中天磁导航 AGV | 2019.06 - 2020.06 | 电气设计、STM32 控制程序、调度系统对接 |
| 滨海活塞厂磁导航 AGV | 2019.06 - 2020.06 | 电气设计、STM32 控制程序、调度系统对接 |
| 山重建机重载磁导航 AGV | 2020.06 - 2021.06 | 电气设计、STM32 控制程序、调度系统对接 |
| 新华医疗二维码 AGV | 2021.04 - 2021.08 | 电气设计、STM32 控制程序、调度系统对接 |

### gomros 机器人系统开发 (2022.03 - 2024.10)

**项目描述**：自主研发类 ROS 机器人软件系统，支持组件化开发与部署

**核心贡献**：
- 线程池模块：设计高性能任务调度机制，支持优先级队列与动态扩缩容
- 组件化启动模块：实现组件依赖管理与生命周期控制
- 组件版本管理：建立版本兼容矩阵，支持灰度发布与回滚
- 自动化部署平台：Jenkins + Docker + SVN 多架构交叉编译系统（支持 x86/ARM）
- 设备驱动适配：完成电机、雷达、IMU、读码器、磁传感器、RFID 等驱动开发
- 质量保障：使用 C++ 编写核心模块，进行单元测试与集成测试
- 技术沉淀：编写模块文档并进行团队技术分享（文档托管于个人笔记网站）

### Linux EtherCAT 主站开发集成 (2024.08 - 2025.04)

**项目描述**：基于 Nvidia NX/RK3588 平台的 EtherCAT 主站系统集成

**核心贡献**：
- 实时内核优化：移植 RT 实时补丁，实现锁核定频、内存锁定、网卡直驱
- 自动化编译系统：Jenkins + Docker 实现 Linux 内核与 EtherCAT 主站自动打包
- 自动化部署：Python 脚本实现内核更新与 EtherCAT 主站一键安装
- 测试验证：完成单元测试、集成测试、稳定性测试（抖动 < 10μs）
- 技术沉淀：编写 EtherCAT 主站模块使用文档并进行技术分享

---

## 🛠️ 技术栈

### 编程语言

<div align="center">  
<a href="https://www.cprogramming.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/c-original.svg" alt="C" height="50" /></a>  
<a href="https://www.cplusplus.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/cplusplus-original.svg" alt="C++" height="50" /></a>  
<a href="https://www.python.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/python-original.svg" alt="Python" height="50" /></a>  
<a href="https://www.java.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/java-original-wordmark.svg" alt="Java" height="50" /></a>  
<a href="https://www.javascript.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" alt="JavaScript" height="50" /></a>  
</div>

**熟练程度**：C/C++（熟练）> Python（熟练）> Java/JavaScript/Rust（熟悉）

### 开发工具

<div align="center">  
<a href="https://www.docker.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/docker-original-wordmark.svg" alt="Docker" height="50" /></a>  
<a href="https://github.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/git-scm-icon.svg" alt="Git" height="50" /></a>  
<a href="https://about.gitlab.com/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/gitlab.svg" alt="GitLab" height="50" /></a>  
<a href="https://www.jenkins.io/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/jenkins-icon.svg" alt="Jenkins" height="50" /></a>  
<a href="https://www.linux.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/linux-original.svg" alt="Linux" height="50" /></a>
<a href="https://www.raspberrypi.org/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/raspberrypi.png" alt="Raspberry Pi" height="50" /></a>  
<a href="https://www.arduino.cc/" target="_blank"><img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/arduino.png" alt="Arduino" height="50" /></a>
</div>

**IDE/编辑器**：VS Code、Visual Studio、Eclipse、Jupyter

**Windows 工具**：MobaXterm、WinSCP、Wireshark、VMware、CANtools、网络调试助手、SSCOM

**Linux 工具**：tmux、htop、iotop、strace、gdb、perf、systemd、CMake、Make

### 硬件驱动开发

#### 通信协议
- **工业总线**：CAN、CANopen、EtherCAT、Modbus RTU/TCP
- **串行通信**：RS485、RS232、SPI、I2C、UART
- **网络协议**：MQTT、TCP/IP、UDP

#### 设备类型
- **执行器**：伺服驱动器、步进驱动器、直流无刷驱动器
- **传感器**：激光雷达（LiDAR）、IMU、编码器、磁传感器
- **识别设备**：二维码读码器、RFID 读卡器
- **其他**：温度传感器、气体传感器等

---

## 📬 联系方式

| 渠道 | 信息 |
|------|------|
| 📧 邮箱 | tonghansen@foxmail.com / tong.han.sen@outlook.com |
| 🌐 个人主页 | https://ts-sound.github.io/ |
| 💻 GitHub | https://github.com/Ts-sound |

---

## 📊 GitHub 统计

| <a href="https://github.com/anuraghazra/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api?username=Ts-sound&show_icons=true&include_all_commits=true&theme=vue-dark" alt="Ts-sound's github stats" /></a> | <a href="https://github.com/anuraghazra/github-readme-stats"><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ts-sound&layout=compact&theme=vue-dark&hide_border=true&hide=HTML,Shell" /></a> |
| ------------- | ------------- |
