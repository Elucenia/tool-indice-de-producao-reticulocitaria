<!-- ELUCENIA technical documentation · indice-de-producao-reticulocitaria · zh · no clinical/professional/rights approval -->

# 校正网织红细胞与网织红细胞生成指数（RPI）

[条件、来源与许可](https://elucenia.org/zh/tools/indice-de-producao-reticulocitaria)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 网织红细胞

`ret`

% · 范围: 0–50

### 红细胞比容

`ht`

% · 范围: 5–65

## 方法版本

Hillman 1969：参考比容45%；成熟1/1.5/2/2.5，本地分界40/30/20

## 已记录的公式

校正网织红细胞 (%) = 网织红细胞 (%) × 血细胞比容 ÷ 45.

RPI = 校正网织红细胞 ÷ 成熟系数, 系数为血中成熟时间（天）: 1.0 (血细胞比容 ≥ 40%); 1.5 (30–39%); 2.0 (20–29%); 2.5 (\< 20%).

## 限制与适用人群

网织红细胞校正取决于贫血严重程度所伴随的成熟时间变化。原始研究在正常人中通过静脉放血诱发贫血；摘要未确认本地简化区间。该指数不能单独确定任何疾病中的病因或骨髓储备。

## 参考文献

- [Hillman RS. Characteristics of marrow production and reticulocyte maturation in normal man in response to anemia. J Clin Invest, 1969.](https://doi.org/10.1172/JCI106001)

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
