# 🐾 Animal Detection with YOLOv8

[![GitHub stars](https://img.shields.io/github/stars/yourusername/animal-detection?style=social)](https://github.com/yourusername/animal-detection)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/Python-3.8%2B-green.svg)](https://www.python.org/)

本项目基于YOLOv8实现六种动物（鸟、猫、牛、狗、马、羊）的目标检测，提供从数据准备到模型部署的完整流程。

![Demo](https://user-images.githubusercontent.com/26833433/236667195-1b576c3e-45b2-42af-b412-703d4b96fd74.jpg)

## 📋 目录
- [功能特性](#-功能特性)
- [环境配置](#-环境配置)
- [数据集](#-数据集)
- [快速开始](#-快速开始)
  - [训练模型](#1-训练模型)
  - [执行检测](#2-执行检测)
- [结果示例](#-结果示例)
- [贡献指南](#-贡献指南)
- [许可证](#-许可证)

## 🌟 功能特性
- **多类别检测**：支持6种常见动物的识别
- **高效训练**：优化后的参数配置（30 epochs仅需1小时）
- **可视化结果**：生成带置信度标签的检测框
- **跨平台支持**：Windows/Linux/macOS 兼容

## ⚙️ 环境配置
```bash
# 创建conda环境（Python 3.8+）
conda create -n animal python=3.8 -y
conda activate animal

# 安装依赖
pip install ultralytics==8.3.99
pip install matplotlib opencv-python
