# 人物档案

量潮组织体系的核心人物档案——一个文件夹是一个"人物"，`index.md` 为该人物的档案入口。

## 结构

```
people/
└── <person-id>/          # 手拍拼音 slug（如 zhangguo）
    └── index.md          # 人物档案：职务表、角色定位
```

## 约定

- 人物是一等实体：同一人可跨组织持有多个职务，在职务表中逐条列出
- 目录名即人物 ID（拼音 slug），与站点 `/people/<id>` 路由对应
- 职务的单一事实源在各组织的 `title.md`（orgs/*/structure/title.md 或 orgs/*/title.md）；人物档案引用不复制，职务变动时两处同步