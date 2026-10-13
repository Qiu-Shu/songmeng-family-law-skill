# 宋萌律师·婚姻家事办案助手

已安装插件的完整原始文件备份，供个人保存、迁移和继续维护。打包日期：2026-10-13（Asia/Shanghai）。

## 内容

- `.codex-plugin/plugin.json`：原插件清单。
- `skills/instructions/SKILL.md`：办案助手指令。
- `skills/instructions/agents/openai.yaml`：界面配置。
- `skills/instructions/lookup/knowledge-index.json`：知识文件索引。
- `skills/instructions/references/02_知识库_办案流程与核验规则.txt`。
- `skills/instructions/references/03_知识库_官方来源与历史正文.txt`。
- `skills/instructions/references/04_知识库_工作底表与登记附件.txt`。

上述 7 个源文件保持原始字节，原插件版本为 `0.1.1+bundle.06484e06e81cb24090660e656185662c`。

## 获取与使用

可克隆本仓库，或在 Releases 下载 `songmeng-family-law-skill-0.1.1.zip`。解压后保留隐藏目录 `.codex-plugin` 以及完整的 `skills` 目录。技能入口为 `skills/instructions/SKILL.md`，其余同目录文件应一并保留。

如只需要阅读或迁移知识内容，使用上述三个 TXT 文件即可。迁移到其他宿主时，按目标宿主支持的技能或插件导入方式加载；本次只验证文件完整性，没有进行新机器安装或法律办案行为验收。

`PACKAGE-MANIFEST.json` 记录源版本、文件大小和 SHA-256；`SHA256SUMS.txt` 覆盖本包内其余所有文件。Release 同时提供 ZIP 的 SHA-256 校验文件。

## 资料状态与范围

知识文件整理于 2026-09-22，主要沿用 2026-09-18 的历史获取或核读记录。打包上传不表示重新核验法律效力、更新全部法律正文或补齐源材料提到的历史脚本、日志与原始附件。使用时应保留文件内的来源、日期和待核事项，并按具体案件重新核验。

本仓库范围仅为该已安装插件与打包说明。知识资料包含通用流程、法规历史文本和空白工作表；没有追加本机 Obsidian 笔记或客户卷宗。不要将真实案件数据、访问凭据或机器配置提交到本仓库。

## 来源与许可

原插件身份及版本见 `PACKAGE-MANIFEST.json`，原清单保留 `GPT Creator` 作者标识。知识文件标明其依据 `divorce-practice-stephane-boghossian` 中国大陆适配版整理，原作者标识为 Stephane Boghossian，原许可标识为 AGPL-3.0。相关说明完整保留，见 `THIRD_PARTY_NOTICES.md`。

本次不改写原技能、不更换原作者署名，也不为全部混合资料另行指定统一许可。
