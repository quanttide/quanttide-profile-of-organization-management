# AGENTS.md

## 概览

量潮组织管理档案，记录组织管理相关产品的产品级思考与需求地图。参考 quanttide-product/data/profile 的建设思路。

## 目录结构

每个产品一个目录，目录名与领域仓库 `apps/` 或 `packages/` 中的子模块名保持一致：

```
<product-name>/
├── index.md        # 产品档案：产品级思考
├── requirement.md  # 需求档案：用户故事地图
└── evaluation.md   # 评估档案：业务目标验证（可选）
```

## 约定

- 档案随迭代更新，反映当前理解，不追求一次写全
