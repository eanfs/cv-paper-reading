# CV 经典论文每周精读 · 大纲

资料来源：[SnailTyan/deep-learning-papers-translation](https://github.com/SnailTyan/deep-learning-papers-translation)（仓库实际仅含 `README.md`，中文版与中英对照托管在译者博客 noahsnail.com；下列链接均已用 HTTPS 抽检可访问）。

仓库内唯一 blob 文件：
- https://github.com/SnailTyan/deep-learning-papers-translation/blob/master/README.md

阅读顺序由浅入深：分类骨干 → 轻量/注意力 → 检测 → OCR → 分割 → 超分生成。共 20 篇。

---

## 阅读顺序

### 1. AlexNet（2012）
- 中文版：https://noahsnail.com/2017/07/18/2017-07-18-AlexNet%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2017/07/04/2017-07-04-AlexNet%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91/
- 理由：深度学习在 ImageNet 上的破冰之作，后续分类网络几乎都从其结构与训练技巧出发。

### 2. VGG（2014）
- 中文版：https://noahsnail.com/2017/08/17/2017-08-17-VGG%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2017/08/17/2017-08-17-VGG%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：用小卷积核堆深网络，结构极规整，是理解「加深」最干净的范例。

### 3. GoogLeNet / Inception（2014）
- 中文版：https://noahsnail.com/2017/07/21/2017-07-21-GoogleNet%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2017/07/21/2017-07-21-GoogleNet%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：Inception 多分支并行卷积，引入「加宽」与计算效率视角。

### 4. Batch Normalization（2015）
- 中文版：https://noahsnail.com/2017/09/04/2017-09-04-Batch%20Normalization%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2017/09/04/2017-09-04-Batch%20Normalization%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：训练稳定性关键件；读 ResNet / Inception-v3 前必须掌握。

### 5. ResNet（2015）
- 中文版：https://noahsnail.com/2017/07/31/2017-07-31-ResNet%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2017/07/31/2017-07-31-ResNet%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：残差连接解决退化问题，成为检测、分割等几乎所有任务的默认骨干。

### 6. Inception-v3（2015）
- 中文版：https://noahsnail.com/2017/10/09/2017-10-09-Inception-V3%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2017/10/09/2017-10-09-Inception-V3%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：系统化分解卷积与正则化，把 GoogLeNet 思想工程化到更强版本。

### 7. SENet（2017）
- 中文版：https://noahsnail.com/2017/11/20/2017-11-20-Squeeze-and-Excitation%20Networks%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2017/11/20/2017-11-20-Squeeze-and-Excitation%20Networks%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：通道注意力的经典入口，为后续注意力与轻量设计铺路。

### 8. MobileNetV2（2018）
- 中文版：https://noahsnail.com/2018/06/06/2018-06-06-MobileNetV2-%20Inverted%20Residuals%20and%20Linear%20Bottlenecks%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2018/06/06/2018-06-06-MobileNetV2-%20Inverted%20Residuals%20and%20Linear%20Bottlenecks%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：倒残差与线性瓶颈，移动端高效骨干的代表。

### 9. Faster R-CNN（2015）
- 中文版：https://noahsnail.com/2018/01/03/2018-01-03-Faster%20R-CNN%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2018/01/03/2018-01-03-Faster%20R-CNN%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：两阶段检测与 RPN 的奠基作，检测框架的「坐标系」。

### 10. YOLO（2015）
- 中文版：https://noahsnail.com/2017/08/02/2017-08-02-YOLO%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2017/08/02/2017-08-02-YOLO%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：单阶段端到端实时检测的开端，与 Faster R-CNN 形成对照。

### 11. SSD（2016）
- 中文版：https://noahsnail.com/2017/12/11/2017-12-11-Single%20Shot%20MultiBox%20Detector%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2017/12/11/2017-12-11-Single%20Shot%20MultiBox%20Detector%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：多尺度特征图默认框，单阶段精度与速度的经典折中。

### 12. YOLO9000（2016）
- 中文版：https://noahsnail.com/2017/12/26/2017-12-26-YOLO9000,%20Better,%20Faster,%20Stronger%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2017/12/26/2017-12-26-YOLO9000,%20Better,%20Faster,%20Stronger%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：YOLOv2 改进与 WordTree 联合训练，展示检测可扩展到更大词表。

### 13. R-FCN（2016）
- 中文版：https://noahsnail.com/2018/01/22/2018-01-22-R-FCN%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2018/01/22/2018-01-22-R-FCN%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：位置敏感得分图，两阶段检测全卷积化。

### 14. FPN（2017）
- 中文版：https://noahsnail.com/2018/03/20/2018-03-20-Feature%20Pyramid%20Networks%20for%20Object%20Detection%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2018/03/20/2018-03-20-Feature%20Pyramid%20Networks%20for%20Object%20Detection%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：自顶向下特征金字塔，小目标与多尺度检测的标准组件。

### 15. Deformable ConvNets（2017）
- 中文版：https://noahsnail.com/2017/11/29/2017-11-29-Deformable%20Convolutional%20Networks%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2017/11/29/2017-11-29-Deformable%20Convolutional%20Networks%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：可变形卷积增强几何建模，检测/分割骨干的重要增强模块。

### 16. CRNN（2015）
- 中文版：https://noahsnail.com/2017/08/21/2017-08-21-CRNN%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2017/08/21/2017-08-21-CRNN%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：CNN+RNN+CTC 端到端序列识别，场景文字识别入门。

### 17. CTPN（2016）
- 中文版：https://noahsnail.com/2018/02/02/2018-02-02-Detecting%20Text%20in%20Natural%20Image%20with%20Connectionist%20Text%20Proposal%20Network%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2018/02/02/2018-02-02-Detecting%20Text%20in%20Natural%20Image%20with%20Connectionist%20Text%20Proposal%20Network%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：文本提案网络，自然场景文字检测的经典流水线。

### 18. U-Net（2015）
- 中文版：https://noahsnail.com/2019/05/13/2019-05-13-U-Net-Convolutional%20Networks%20for%20Biomedical%20Image%20Segmentation%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2019/05/13/2019-05-13-U-Net-Convolutional%20Networks%20for%20Biomedical%20Image%20Segmentation%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：编码器–解码器 + 跳跃连接，医学与通用分割的标杆结构。

### 19. SRGAN（2017）
- 中文版：https://noahsnail.com/2020/04/10/2020-04-10-Photo-Realistic%20Single%20Image%20Super-Resolution%20Using%20a%20Generative%20Adversarial%20Network%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2020/04/10/2020-04-10-Photo-Realistic%20Single%20Image%20Super-Resolution%20Using%20a%20Generative%20Adversarial%20Network%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：对抗损失用于超分，感知质量导向生成式视觉任务的入口。

### 20. ESRGAN（2018）
- 中文版：https://noahsnail.com/2020/04/13/2020-04-13-ESRGAN%20-%20Enhanced%20Super-Resolution%20Generative%20Adversarial%20Networks%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E6%96%87%E7%89%88/
- 中英对照：https://noahsnail.com/2020/04/13/2020-04-13-ESRGAN%20-%20Enhanced%20Super-Resolution%20Generative%20Adversarial%20Networks%E8%AE%BA%E6%96%87%E7%BF%BB%E8%AF%91%E2%80%94%E2%80%94%E4%B8%AD%E8%8B%B1%E6%96%87%E5%AF%B9%E7%85%A7/
- 理由：对 SRGAN 的网络与损失增强，收束生成式超分主线。

---

## 第 1 篇（AlexNet）七课章节切分

依据中文译文实际结构：摘要；§1 引言；§2 数据集；§3 架构（3.1 ReLU / 3.2 多 GPU / 3.3 局部响应归一化 / 3.4 重叠池化 / 3.5 整体架构）；§4 减少过拟合（4.1 数据增强 / 4.2 Dropout）；§5 学习细节；§6 结果（含 6.1 定性评估）；§7 探讨。

| 课次 | 标题 | 覆盖章节 |
|------|------|----------|
| 第1课 | 背景与摘要 | 摘要 + §1 引言（问题背景、CNN 动机、本文贡献概述） |
| 第2课 | 数据与加速训练 | §2 数据集 + §3.1 ReLU 非线性 + §3.2 多 GPU 训练 |
| 第3课 | 架构细节与整体网络 | §3.3 局部响应归一化 + §3.4 重叠池化 + §3.5 整体架构 |
| 第4课 | 抗过拟合 | §4.1 数据增强 + §4.2 Dropout |
| 第5课 | 训练细节与实验结果 | §5 学习细节 + §6 结果 + §6.1 定性评估 |
| 第6课 | 结论与局限 | §7 探讨 |
| 第7课 | 整周回顾 + 知识卡片 | 串讲 1–6 课要点，整理可背诵卡片 |

说明：第1课正文见 `lessons/01-1.md`。
