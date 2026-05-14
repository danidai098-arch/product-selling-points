# product-selling-points
Help FMD product managers quickly refine product selling points and issue products from 0-1 to solutions.
# References 目录说明

## 目录结构

```
references/
├── README.md              # 本文件，目录说明
├── jtbd-framework.md      # JTBD 需求分析框架
├── fabe-matrix.md         # FABE 卖点矩阵
├── competitor-analysis.md # 竞品分析指南
├── output-templates.md    # 输出模板库
├── visual-analysis.md     # 视觉分析指南
├── error-handling.md      # 错误处理与边界情况
├── browser/               # 浏览器抓取相关
│   ├── jd-product-page.md     # 京东商品页抓取
│   ├── taobao-product-page.md # 淘宝商品页抓取
│   └── fallback-strategy.md   # 抓取降级策略
└── examples/              # 案例库
    ├── skincare.md        # 儿童防晒霜案例
    ├── food.md            # 健康零食案例
    └── electronics.md     # 无线耳机案例
```

## 使用方式

在 SKILL.md 中通过相对路径引用：

```markdown
## 参考资料

- JTBD 框架详见 [references/jtbd-framework.md](references/jtbd-framework.md)
- FABE 矩阵详见 [references/fabe-matrix.md](references/fabe-matrix.md)
```

## 文档说明

| 文档                   | 用途                | 使用场景             |
| ---------------------- | ------------------- | -------------------- |
| jtbd-framework.md      | JTBD 方法论详解     | 步骤2.2 用户需求收集 |
| fabe-matrix.md         | FABE 矩阵模板与案例 | 步骤6 卖点发散       |
| competitor-analysis.md | 竞品分析框架        | 步骤3-4 竞品分析     |
| output-templates.md    | 各阶段输出模板      | 全流程输出规范       |
| visual-analysis.md     | 主图视觉分析方法    | 步骤3.1 主图分析     |
| error-handling.md      | 错误处理策略        | 异常情况处理         |
| browser/*.md           | 电商平台抓取指南    | 步骤3 竞品数据抓取   |
| examples/*.md          | 完整案例参考        | 参考/学习            |

## 维护说明

1. **新增案例**：在 examples/ 目录下创建新的 .md 文件
2. **更新模板**：直接修改对应 .md 文件
3. **新增平台**：在 browser/ 目录下创建新的抓取指南

---

## 快速索引

### 按阶段查找

| 阶段             | 相关文档                           |
| ---------------- | ---------------------------------- |
| 步骤1-2 信息收集 | jtbd-framework.md                  |
| 步骤3 竞品抓取   | browser/*.md, fallback-strategy.md |
| 步骤3.1 视觉分析 | visual-analysis.md                 |
| 步骤4 信息解读   | competitor-analysis.md             |
| 步骤6 FABE 矩阵  | fabe-matrix.md                     |
| 步骤7-8 输出     | output-templates.md                |
| 异常处理         | error-handling.md                  |

### 按问题查找

| 问题                   | 查阅文档                           |
| ---------------------- | ---------------------------------- |
| 不知道怎么问 JTBD 问题 | jtbd-framework.md → 三、提问技巧  |
| FABE 矩阵写不好        | fabe-matrix.md → 三、常见问题     |
| 竞品页面抓取失败       | browser/fallback-strategy.md       |
| 主图分析不知道看什么   | visual-analysis.md → 一、分析维度 |
| 输出格式不统一         | output-templates.md                |
