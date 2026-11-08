# Personal Skills

我的个人 AI Agent Skills 集合，用于积累和维护可复用的工作流、脚本与参考资料。

## 目录

- [skills/](./skills/)：每个 skill 使用一个独立目录。
- [.gitignore](./.gitignore)：忽略本地配置、依赖和临时文件。

## 添加一个 skill

1. 在 `skills/` 下创建目录，名称使用小写字母和连字符，例如 `my-skill`。
2. 添加 `SKILL.md`，说明 skill 的用途、适用场景和执行步骤。
3. 按需加入脚本、参考文档和素材，文档中的路径使用相对路径。
4. 验证 skill 可用后提交到仓库。

推荐的单个 skill 目录结构：

```text
skills/
└── my-skill/
    ├── SKILL.md
    ├── scripts/       # 可选：辅助脚本
    ├── references/    # 可选：参考文档
    └── assets/        # 可选：模板与素材
```

## 使用

选择所需的 skill，将其完整目录安装或复制到所用 AI 工具支持的 skills 目录中。具体依赖和使用方式见各 skill 的 `SKILL.md`。

## 已收录 Skills

| Skill | 用途 |
| --- | --- |
| [Bikini Bottom Gross-Up](./skills/bikini-bottom-gross-up/SKILL.md) | 比奇堡特写：将人物、动物、食物、物件与场景转成二维手绘怪诞特写，也可生成对应提示词。 |

安装后可使用 `$bikini-bottom-gross-up` 调用。
