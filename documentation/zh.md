<!-- ELUCENIA technical documentation · escala-de-fisher-modificada · zh · no clinical/professional/rights approval -->

# 改良 Fisher 分级

[条件、来源与许可](https://elucenia.org/zh/tools/escala-de-fisher-modificada)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 入院时 CT 所见

`grau`

- `0` — 0 – 无蛛网膜下腔出血及脑室内出血
- `1` — 1 – 薄层蛛网膜下腔出血（局灶或弥漫），无脑室内出血
- `2` — 2 – 脑室内出血，伴无蛛网膜下腔出血或薄层蛛网膜下腔出血（局灶性或弥漫性）
- `3` — 3 – 厚层蛛网膜下腔出血（局灶或弥漫），无脑室内出血
- `4` — 4 – 厚层蛛网膜下腔出血，伴脑室内出血

## 方法版本

改良Fisher分级 — Frontera等，2006，表1：无、薄层或厚层蛛网膜下腔出血以及脑室内出血；0–4级

## 已记录的公式

根据入院CT中是否存在蛛网膜下腔出血（SAH）、血液层厚度以及是否存在脑室内出血（IVH）进行分级。0级：无SAH且无IVH；1级：薄层SAH，无IVH；2级：IVH伴无SAH或薄层SAH；3级：厚层SAH，无IVH；4级：厚层SAH，伴IVH。Frontera等（2006）的研究中，各地研究者根据总体印象将血液分为薄层或厚层，未采用明确的厚度标准。工具记录检查者选择的等级，不解读图像。

## 限制与适用人群

该CT分级旨在预测蛛网膜下腔出血后的症状性血管痉挛。所查阅研究纳入了四项试验安慰剂组的患者。该分级本身不能诊断血管痉挛、预测所有结局或确立治疗指征。

## 参考文献

- [Frontera JA et al. Prediction of symptomatic vasospasm after subarachnoid hemorrhage: the modified Fisher scale. Neurosurgery, 2006.](https://doi.org/10.1227/01.NEU.0000218821.34014.1B)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
