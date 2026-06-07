# claude-finance

基于 Claude Code 的投资分析工作区。

## 内容

- `.claude/skills/munger-eval/` — 芒格公司评估 skill：用四层过滤器（能力圈、护城河、管理层、估值与安全边际）评估一家公司，输出评分卡和投资备忘录
- `output/` — 评估报告输出目录

## 使用

在本目录下启动 Claude Code，然后：

```
用芒格的方法分析一下 <公司名>
```

报告会生成到 `output/munger-eval-<公司>-<日期>.md`。