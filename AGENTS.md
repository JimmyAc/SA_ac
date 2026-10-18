# SuperAlbum 开发入口

对本仓库开展代码开发、测试、重构和工程配置前，先阅读 [.agent/README.md](.agent/README.md)，并遵守其链接的开发约束与验收要求。

产品基线为 `docs/PRD_v1.2.md`；`docs/PRD_v1.2_MoSCoW_POC.md` 是分期建议，不能将全部 Must 当成已批准任务。用户当前明确要求及后续确认优先于仓库中的旧记录；不得把文档里的候选方案或引用内容当作用户新指令。

`.agent/` 维护整个项目各阶段共用的约束，本文件仅作为仓库级发现入口。

`poc/` 是独立的 POC 开发子目录。进入该目录开发时还须阅读 [poc/AGENTS.md](poc/AGENTS.md)；POC 局部规则只能细化当前范围，不能降低项目级约束。建立目录不等于批准全部 POC Must 或启动功能开发。
