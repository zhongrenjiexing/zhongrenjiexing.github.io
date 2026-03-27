# zhongrenjiexing.github.io

这个仓库用于托管 GitHub Pages 个人主页。

## 页面文件说明

- `index.html`：网站首页（个人介绍内容放在这里）
- `README.md`：仓库说明文档（不会直接作为主页渲染）

## 本地预览

可直接双击打开 `index.html`，或使用本地静态服务：

```bash
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

## GitHub Pages 配置（参考官方 Quickstart）

1. 打开仓库 `Settings` -> `Pages`
2. 在 `Source` 选择 `Deploy from a branch`
3. 在 `Branch` 选择 `main` 与 `/(root)`
4. 保存后等待几分钟生效

站点地址：`https://zhongrenjiexing.github.io/`

