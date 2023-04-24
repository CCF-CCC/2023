---
layout: page
toc: false
title: 
---

#  {{ site.class_name}}

CCF定制计算挑战赛由中国计算机联合会主办，旨在发掘计算机体系结构方面的人才，激发学生对计算机体系结构研究的兴趣，培养学生的创新精神。今年比赛的目标是探索AI引擎在数字信号处理和视觉领域的处理能力。比赛的硬件平台将使用搭载了高性能加速核心AI引擎阵列的AMD VCK5000板卡。前三名队伍将获得高额奖金。颁奖典礼将在2023 CCFSys大会上举行。

## 赛事亮点

* 硬件平台搭载高度优化的计算密集型应用与AMD的新的高性能加速核心AI引擎阵列，与传统的可编程逻辑实现相比，AI引擎具有高计算密度低功耗的优势，同时使用C/ c++级别的编程范式，显著提高开发人员的生产力和硬件设计能力

* 深入体验真正的异构平台，该平台结合了AI引擎(矢量和标量引擎)，可编程逻辑(PL)，自适应引擎(DSP)，集成DDR内存控制器和可编程片上网络(NoC)，以最大限度地提高编程灵活性和易于重新配置

<p align="middle">
    <img src="{% link media/AIE1.png %}" width="300" class="center">
    <img src="{% link media/AIE2.png %}" width="300" class="center">
</p>

## 赛事安排

CCC2023的赛制以团队进行，每队最多3人，可跨单位组队，赛题分为两个方向：DSP方向的FFT算法实现，CV方向的Filter2D算法实现。参赛队伍需要在两题中选择一个题目完成，如果两题都完成选择完成度更高的题目进行评分，最终选出积分排名前3的队伍进入现场决赛完成实际硬件性能的评测。其中设计性能和设计报告都很重要，鼓励参赛者从设计和AI引擎架构的角度提出进一步探索异构平台架构和开发流程优化的方法。

本次比赛的决赛将与2023年中国计算机学会系统大会（CCFSys 2023）同步举行，并在现场决出前三名，第一名将获得10000元人民币奖金，第二名将获得5000元人民币奖金，第三名将获得
3000元人民币奖金。

本次比赛自4月26日开发报名，5月12日报名截止，5月22日开始开放设计作品在线提交, 并于6月30日提交截止，入围决赛的队伍将在7月10日公示。

<p align="middle">
    <img src="{% link media/CCC_2023_flow.png %}" width="800" class="center">
</p>

## 开发环境

本次竞赛将开发使用AMD异构加速计算集群(HACC)平台，配备了包含VCK5000板卡的最新的自适应计算硬件和软件技术，旨在支持高性能计算(HPC)自适应计算加速的研究。
关于HACC的详细内容，请参考[链接](https://www.amd-haccs.io/index.html)

## 链接

  * [Contest Dates]({% link _pages/schedule.md %})
  * [Registration](https://www.wjx.top/vm/tbXtzkR.aspx#)
  * [Participant Info]({% link _pages/info.md %})
  * [Problems]({% link _pages/problems.md %})
  * [Submission Instructions]({% link _pages/submission.md %})
  * [Contest Results]({% link _pages/results.md %})