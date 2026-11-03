# 数据集下载指南

本项目使用 **MIMII 数据集**（Malfunctioning Industrial Machine Investigation and Inspection）。
该数据集包含工业设备（如水泵 pump、风机 fan、滑轨 slider、阀门 valve）的正常与异常声音。

## 下载地址
由于数据集较大，请前往官方仓库下载：
- [MIMII Dataset 官方 GitHub](https://github.com/MIMII-Dataset/mimii-dataset) 
- 或 DCASE 官网任务 2 的相关数据集。

## 数据预处理步骤（待更新）
1. 解压后选取 `pump` (水泵) 的 `id_00` 设备数据。
2. 采样率统一为 16kHz。
3. 切分为 4 秒的音频片段。
4. 训练集仅放正常音频，测试集包含正常与异常音频。
