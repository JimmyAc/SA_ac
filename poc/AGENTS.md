# SuperAlbum POC 开发入口

本目录用于 SuperAlbum POC 的实际代码开发，继承根目录 [AGENTS.md](../AGENTS.md) 及 [.agent/README.md](../.agent/README.md) 指向的全部项目约束。

开始本目录工作前，再阅读 [README.md](README.md)、[SCOPE.md](SCOPE.md) 与 [VALIDATION.md](VALIDATION.md)。局部规则只细化 POC 范围和开发方式，不能覆盖项目产品不变量或把未决问题标为已确认。

- POC 源码、依赖、构建脚本、测试和实验记录放在本目录内；工程初始化时将本目录作为 POC 工程根目录，具体模块按实际方案建立。
- Android 原生、首次完全离线、稳定 L 与实际副本分离、原件保护、来源与核验分离等项目约束完整适用。
- 不将所有建议 Must 默认视为已批准；按当前明确任务实现，未决行为继续追踪。
- 与 POC 实验有关的临时技术取舍在本目录记录；影响项目产品规则或长期技术基线的决定同步到 [.agent/DECISIONS.md](../.agent/DECISIONS.md)。
- 当前只建立开发目录和规则，尚无应用代码或构建命令；不得宣称工程、模型或设备验证已经完成。
