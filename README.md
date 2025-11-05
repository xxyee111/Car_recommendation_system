# Car_recommendation_system
# 🚗 智能汽车推荐系统

<div align="center">

![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)

基于随机森林算法的智能汽车推荐系统，根据用户的预算、乘客数量和使用场景，推荐最适合的车型。



## ✨ 功能特点

- 🎯 **精准推荐**: 基于随机森林算法，准确率高
- 🔄 **实时预测**: 快速响应用户输入
- 📊 **可视化分析**: 提供混淆矩阵、特征重要性等可视化图表
- 💾 **模型持久化**: 支持模型保存和加载，无需重复训练
- 📈 **性能监控**: 交叉验证确保模型稳定性

---

## 🛠️ 技术栈

| 技术 | 版本 | 用途 |
|------|------|------|
| Python | 3.8+ | 核心语言 |
| scikit-learn | 1.3+ | 机器学习框架 |
| pandas | 2.0+ | 数据处理 |
| numpy | 1.24+ | 数值计算 |
| matplotlib | 3.7+ | 数据可视化 |
| seaborn | 0.12+ | 统计图表 |
| joblib | 1.3+ | 模型序列化 |

---


## 📁 项目结构
```
car-recommendation-system/
│
├── data/
│   └── training_data.csv          # 训练数据
│
├── models/
│   └── car_recommendation_model.pkl  # 训练好的模型
│
├── src/
│   ├── __init__.py
│   ├── model.py                   # 核心模型类
│   ├── predictor.py               # 预测功能
│   └── visualizer.py              # 可视化工具
│
├── notebooks/
│   └── Untitled.ipynb             # 训练笔记本
│
├── tests/
│   └── test_model.py              # 单元测试
│
├── requirements.txt               # 依赖列表
├── README.md                      # 项目文档
├── main.py                        # 命令行入口
├── app.py                         # Web应用入口 (可选)
└── LICENSE                        # 许可证
```

---

## 📊 模型性能

### 评估指标

| 指标 | 值 |
|------|-----|
| 测试集准确率 | 100.00% |
| 交叉验证均值 | 96.89% |
| 交叉验证标准差 | ±5.77% |

### 特征重要性
```
using (用途):              33.79%
budget_purpose (交互项):   27.88%
budget (预算):             17.86%
passenger_purpose (交互项): 11.43%
budget_passenger (交互项):  7.11%
passenger (乘客数):         1.93%
```

### 混淆矩阵

![Confusion Matrix](confusion_matrix.png)

---

## 🎯 支持的车型(可扩充)

| 车型 | 价格区间 | 适用场景 |
|------|----------|----------|
| 比亚迪海豚 | 10-15万 | 城市通勤 |
| 丰田卡罗拉 | 12-16万 | 家用代步 |
| 领克03 | 15-20万 | 运动时尚 |
| 本田CR-V | 18-27万 | 家用SUV |
| 奥迪A4L | 30-40万 | 商务轿车 |
| 奔驰E级 | 45-65万 | 豪华商务 |
| 丰田汉兰达 | 25-35万 | 7座家用 |
| 坦克300 | 20-30万 | 硬派越野 |
| 五菱宏光 | 5-10万 | 实用工具车 |

---

## 📝 更新日志

### v1.0.0 (2025-11-5)
- 初始版本发布
- 实现基于随机森林的推荐算法
- 添加可视化功能
- 支持模型持久化

---

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

---


## 🙏 致谢

- 感谢 scikit-learn 团队提供优秀的机器学习框架

---

## 📮 联系方式

- 📧 Email: 1372988366@qq.com
