# 贡献指南 / Contributing

欢迎补充 Claude Fable 5.2 的公开案例。Please add public Fable 5.2 cases.

## 提交要求

1. 案例必须与 **Claude Fable 5.2**（或来源明确写出的 earlier version of Fable 5.2）直接相关，并附上原始来源 URL（官方博文、公司/研究者文章、X 帖、GitHub、可核验的新闻并指向一手来源）。
2. 不要编造姓名、引言、数字、链接或日期。数字请按来源原样转述，并标明那是作者或页面自述，不要写成我们已经独立验证。
3. 不要把 **Claude Mythos 5.2** 专属工作（网络安全攻防、生命科学中的分子设计等，且来源只写了 Mythos）当作 Fable 案例，除非同一来源清楚写明 Fable 做了这件事。
4. 一条案例 = 一个独立项目、演示或结果，不要把同一条能力介绍改写后重复提交。同一篇文章里彼此独立的结果可以分成多条，但要写清来源中的原话。
5. 请同时更新 `README.md`、`README.en.md`（如适用）和 `cases.json`。`cases.json` 字段：`id`, `title_zh`, `title_en`, `category`, `summary`, `source_url`, `author`, `date`（ISO `YYYY-MM-DD`，未知则 `null`）, `source_type`。
6. 分类建议：`coding-agents`, `science`, `finance`, `legal-compliance`, `3d-hardware-robotics`, `community-demos`, `benchmarks`。如需新分类，请在 PR 里说明。

## 修改方式

小修正可直接开 Pull Request。失效链接、错误署名、误把 Mythos 结果算进 Fable、以及版权问题也可以开 Issue。

This project is licensed under the MIT License. Linked case material stays with its original authors; see NOTICE.md.
