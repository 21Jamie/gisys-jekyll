# Obsidian Site with Quartz

基于 Quartz 4 的静态网站，用于发布 Obsidian 笔记。

## 快速开始

### 在本地预览

```bash
cd "/Volumes/X10 Pro/ObsidianVault"
npm run dev
```

访问 http://localhost:8080

### 添加笔记

1. 在 Obsidian 中打开 vault：`/Volumes/X10 Pro/ObsidianVault`
2. 在 `content` 文件夹中添加 `.md` 文件
3. 提交并推送：

```bash
git add content/
git commit -m "Add new note"
git push origin v4
```

GitHub Actions 会自动构建并发布到 GitHub Pages。

## 访问网站

https://gisys.netlify.app

## 配置

- 修改 `quartz.config.ts` 自定义主题和配置
- 修改 `content` 文件夹中的笔记内容

## 文件结构

```
ObsidianVault/
├── content/          # Obsidian 笔记存放位置
├── docs/             # 构建输出（自动生成）
├── quartz.config.ts  # Quartz 配置
└── .github/workflows/deploy.yml  # 自动部署配置
```
