# Codex Public Skills

这是 Jiayi-Mo 用于公开分享 Codex skills 的合集仓库。每个 skill 都是独立目录，可以单独查看、下载和安装。

## Skills

| Skill | 功能 |
| --- | --- |
| [reverse-image-prompt](skills/reverse-image-prompt/) | 精细拆解参考图片，并生成高还原、可直接使用的中文 AI 生图提示词。 |

## 仓库结构

\`\`\`text
skills/
└── skill-name/
    ├── SKILL.md
    ├── agents/
    └── references/
\`\`\`

## 安装单个 skill

克隆仓库：

\`\`\`bash
git clone https://github.com/Jiayi-Mo/codex-public-skills.git
\`\`\`

将需要的 skill 复制到 Codex skills 目录：

\`\`\`bash
cp -R codex-public-skills/skills/reverse-image-prompt ~/.codex/skills/
\`\`\`

安装完成后，在新任务中使用：

\`\`\`text
$reverse-image-prompt
\`\`\`

## 添加新的公开 skill

将完整 skill 文件夹放入 \`skills/<skill-name>/\`，并在本页的 Skills 表格中增加一条记录。

## License

当前仓库暂未声明开源许可证。公开可见不等于自动授予复制、修改或再分发许可；如需开放复用，请后续添加合适的许可证。
