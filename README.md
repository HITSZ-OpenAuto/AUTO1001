# AUTO1001 - 自动化认知与实践

<!--
1. 通过 [Shields.io](https://shields.io/) 生成如下的徽章，标注课程的基本信息。尽情发挥你的颜色审美！
2. 请根据课程的具体内容增删仓库的子文件夹。子文件夹建议使用小写英文，并且添加 README.md。
3. 关于课程的描述可以不止以下几个方面，酌情增删。
4. 当 hoa.moe 生成本课程对应页面后，请将页面链接复制到 GitHub 仓库的 About/Website 中。
5. 可以在 GitHub 页面的 About/Topics 中为课程添加话题名称。
-->

![Static Badge](https://img.shields.io/badge/考查课-green)
![Static Badge](https://img.shields.io/badge/%E5%AD%A6%E5%88%86-4-moccasin)

![Static Badge](https://img.shields.io/badge/%E6%88%90%E7%BB%A9%E6%9E%84%E6%88%90(2022级)-gold)
![Static Badge](https://img.shields.io/badge/%E4%BD%9C%E4%B8%9A%E4%B8%8E%E8%AE%BA%E6%96%87-10%25-wheat)
![Static Badge](https://img.shields.io/badge/%E8%AF%BE%E5%A0%82%E5%AE%9E%E9%AA%8C-30%25-wheat)
![Static Badge](https://img.shields.io/badge/%E6%9C%BA%E5%99%A8%E4%BA%BA%E8%80%83%E6%A0%B8-30%25-wheat)
![Static Badge](https://img.shields.io/badge/%E6%9C%9F%E6%9C%AB%E8%80%83%E8%AF%95-30%25-wheat)

![Static Badge](https://img.shields.io/badge/总学时-64-gold)
![Static Badge](https://img.shields.io/badge/讲课学时-40-wheat)
![Static Badge](https://img.shields.io/badge/实验学时-24-wheat)

<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=3000&color=F71717&center=true&multiline=true&repeat=false&random=false&width=435&height=100&lines=%E6%AC%A2+%E8%BF%8E+%E6%9D%A5+%E5%88%B0;AUTO1001;自 动 化 认 知 与 实 践" alt="Typing SVG: Welcome"/>
  </a>
</div>

本课程开设自 2022 年，合并了过去工程制图基础、自动化专业导论、机器人设计与实践、机械设计基础 4 门课程。

## 授课教师

自动化专业导论、工程制图、机器人设计与实践部分分别由不同的老师先后负责讲授。

- 自动化专业导论：楼云江
- 工程制图：袁晗、杨月
- 机器人设计与实践：陈浩耀、黄瑞宁 / 熊昊、熊小刚
- 实验课：葛亚明

## 关于考试

> by [Maxwell](https://github.com/MaxwellJay256)

2022 级自动化专业学生参与了这门课第一次考试，笔试内容主要来自课堂教学，例如电机驱动，电阻色环识别，Arduino 编程知识。
考试难度对于从未接触过机器人或单片机的同学来说并不是很友好，而且主要考的都是死记硬背的东西，因此在学生间的评价很差。

## 课程简介

### 关于导论部分

> by [Oliver Wu](https://github.com/OliverWu515)

> 此为2021级内容。新的导论部分对原来内容有了较大程度的裁剪，但是仍然建议有兴趣的同学仔细阅读有关“自动化基本原理”的内容，对自动控制系统的思想、构成、实现方式有个初步认识。
> 课件放在校内网盘。

主要内容：
- 自动化的概念与发展简史
- 自动化基本原理（这部分原来由吴爱国教授负责讲授），包括：
  - 两类自动控制：开环与闭环
  - 自动控制的定性描述（方框图等）与定量描述（数学模型，如传递函数）
    - 建立控制对象的数学模型是自动化专业的核心知识
  - 自动控制系统的基本要求——稳、快、准，及描述方式
  - 自动控制系统的控制方式（前馈、反馈、串级、多回路……）
  - PID控制律，PID各环节的作用
  - 反馈的重要性，关注**不确定性**等概念，自动化与控制的关系
- 现代自动化初览（科普）
- 自动化专业培养目标、课程体系、学术体系、发展前景

### 关于机器人设计与实践的理论课

> by [Oliver Wu](https://github.com/OliverWu515)

主要内容：
- 电学基本知识（电路基础）
- 直流电机驱动基本知识（重点关注H桥）
- 实验中会用到的各种模块（如超声波传感模块等）的用法
- Arduino编程入门
  - 基本I/O（Input输入、Output输出）、串口
  - 延时函数、中断（采集编码器信号等）
  - 其他外围设备编程
  - 参考网站：https://www.arduino.cc/reference/en/
- PID控制律作用于实际系统，每个环节的作用
- 轮式机器人基本运动学

### 关于实验

> by [Maxwell Jay](https://github.com/MaxwellJay256)

> 以下内容仅代表 2022 级的情况

#### 前期

前期的实验课比较简单，是使用电子元件和 Arduino 开发板制作一些简单的项目，可以参考课件文件夹中的实验指导书提前了解。如果做这些项目时遇到了问题，建议在 [CSDN](https://www.csdn.net/) 和 [Arduino官网](https://www.arduino.cc/) 上查找有关资料。老师布置的项目，别人肯定也做过。

如果是用到 Arduino 的实验，建议在上课前提前准备好程序，现场敲代码会比较浪费时间。实验虽然会发实验代码，但不建议直接照抄，理解代码会对后期小车代码的编写调试大有裨益。

实验的打分由老师或者助教完成，就是看实际的运行效果，要求并不非常严格。完成实验课上的附加题可获得额外加分。

#### 后期

后期老师会把实验室开放给学生，自行使用已有的零件搭建一辆能够——
- 使用红外线传感器巡线
- 使用使用机械臂抓放物体
- 使用超声波避障

——的小车。小车会在期末进行考核，根据完成任务的情况打分。

关于这个部分，**每一届自动化的学生都有很多故事想说😅**，但是就不在这里展开了。

不过我们搜集了一些 2022 级同学的代码仓库，里面不仅有实用的代码，还有同学们分享的学习经历、经验和教程！

- [Maxwell Jay - mega_12800](https://github.com/MaxwellJay256/mega_12800)
- [longlin li - HITSZ_lab_project](https://github.com/longlin10086/HITSZ_lab_project)
- [Chenx Dust - AutoCar](https://github.com/chenxijun/AutoCar)

> by [Oliver Wu](https://github.com/OliverWu515)

希望同学们认真完成实验，体会由物理系统——数学模型——物理实现的路径（如，针对物理系统的特性，设计PID控制律，再结合传感器将物理信号转换成电信号，利用单片机实现数字式的增量式PID控制算法），巩固C语言编程的知识。
希望同学们在实验过程中养成良好的习惯，爱护实验器材，维护好实验室的环境。
