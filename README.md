# 短剧剧本与台词工作室

一套可复用的 Codex Skill，用于短剧剧本创作、续写、扩写、压缩、剧情诊断和人物台词精修。它会根据任务选择剧本写作或台词精修规则，并尽量保持人物关系、剧情事实与场次连续性。

这个 Skill 聚焦文字剧本，不负责分镜提示词、图片资产、视频生成或成片检查。仓库不包含任何用户剧本原稿或项目素材。

## 文件结构

```text
SKILL.md
agents/openai.yaml
references/script-writing.md
references/dialogue-revision.md
```

## 安装

将本仓库克隆或复制到个人 Skill 目录 `$HOME/.agents/skills/short-drama-script-studio`。Codex 会读取其中的 `SKILL.md`。如未立即出现，可重启 Codex。

## 使用示例

```text
$short-drama-script-studio 根据以下梗概写短剧第 1 集，每场标明地点、人物、冲突与场末结果：……
```

```text
$short-drama-script-studio 只精修下面的台词，让它更自然，不改变剧情事实与人物立场：……
```

也可以直接描述短剧写作或台词修改任务，让 Codex 按需选用此 Skill。

## 贡献

欢迎通过 Issue 提出使用场景和改进建议，或通过 Pull Request 改进通用规则。请不要在公开 Issue 中粘贴未授权公开的剧本或私人素材。

## 许可证

MIT
