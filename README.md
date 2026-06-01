<div align="center">

# 基于STM32的智能净水机控制系统设计与实现

**2026届本科毕业论文 | 成都大学自动化专业**

[![项目状态](https://img.shields.io/badge/项目状态-已完成-brightgreen?style=for-the-badge)](https://github.com/csq66666666/my_theis)
[![论文状态](https://img.shields.io/badge/论文状态-终稿-blue?style=for-the-badge)](https://github.com/csq66666666/my_theis/blob/main/thesis.pdf)
[![硬件平台](https://img.shields.io/badge/硬件-STM32F103-orange?style=for-the-badge)](https://www.st.com/en/microcontrollers-microprocessors/stm32f103-series.html)
[![开发环境](https://img.shields.io/badge/软件-KEIL5-red?style=for-the-badge)](https://www.keil.com/download/product/)
[![最后更新](https://img.shields.io/github/last-commit/csq66666666/my_theis?style=for-the-badge)](https://github.com/csq66666666/my_theis/commits/main)

</div>

---

## 📑 目录
- [基于STM32的智能净水机控制系统设计与实现](#基于stm32的智能净水机控制系统设计与实现)
  - [📑 目录](#-目录)
  - [📖 项目简介](#-项目简介)
  - [📁 文件结构](#-文件结构)
  - [🛠️ 技术栈](#️-技术栈)
  - [🏗️ 系统架构](#️-系统架构)
  - [✨ 核心功能](#-核心功能)
  - [📊 实验结果](#-实验结果)
  - [🙏 致谢](#-致谢)

---

## 📖 项目简介
本设计针对传统净水机智能化程度低、无法远程监控、滤芯寿命提醒不精准等问题，开发了一套基于STM32F103单片机的智能净水机控制系统。系统通过多种传感器实时采集水质、流量、压力等数据，利用ESP8266模块基于MQTT协议将数据上传至中国移动OneNET云平台，实现了手机端的远程监控和控制功能。

**主要创新点：**
- 采用霍尔流量计实现精准流量统计，测量误差小于2%
- 基于累计用水量的智能滤芯寿命算法，提醒准确率提升40%
- 低功耗模式设计，设备待机电流小于10mA，延长电池使用寿命
- 异常情况自动报警机制，保障用水安全

---



---

## 📁 文件结构

---

## 🛠️ 技术栈
<div align="center">

| 类别 | 技术/工具 |
|:---:|:---:|
| **核心控制器** | STM32F103C8T6 |
| **通信模块** | ESP8266-01S |
| **传感器** | TDS水质传感器、霍尔流量计、压力传感器 |
| **开发环境** | KEIL5、Arduino IDE |
| **云平台** | 中国移动OneNET |
| **通信协议** | MQTT、UART、I2C |
| **设计工具** | Altium Designer、Visio、Matlab |

</div>

---

## 🏗️ 系统架构


---

## ✨ 核心功能
- ✅ **实时水质监测**：TDS值、水温、水压实时显示
- ✅ **精准流量统计**：累计用水量和瞬时流量计算
- ✅ **滤芯寿命提醒**：基于用水量的智能寿命计算
- ✅ **远程控制**：手机端远程开关净水机
- ✅ **数据历史**：7天水质和用水量历史曲线
- ✅ **异常报警**：漏水、水质超标自动报警
- ✅ **低功耗模式**：待机状态自动进入低功耗

---

## 📊 实验结果
<div align="center">

| 测试项目 | 测试结果 | 行业标准 |
|:---:|:---:|:---:|
| TDS检测精度 | ±5ppm | ±10ppm |
| 流量测量误差 | <2% | <5% |
| 通信成功率 | >98% | >95% |
| 待机电流 | 8.6mA | <20mA |
| 响应时间 | <2s | <5s |

</div>

---

## 🙏 致谢
感谢我的导师**胡林老师**在整个毕业设计过程中的悉心指导和耐心帮助，从课题选择到最终完成，邹老师都给予了我很多宝贵的建议。感谢实验室各位同学在硬件调试和代码编写过程中提供的帮助。

---

<div align="center">
  <sub>本项目仅用于学术研究，请勿用于商业用途</sub>
  <br><br>
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4-red.svg" alt="Made with love">
</div>