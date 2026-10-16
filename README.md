# AI Governance Portfolio — GitHub Pages

这是一个纯静态网页，不依赖构建工具，适合直接部署到 GitHub Pages。

## 文件结构

```text
ai_governance_portfolio_github/
├── index.html
├── styles.css
├── script.js
├── assets/
│   ├── dashboard.png
│   └── workflow.png
└── data/
    └── metrics.json
```

## 本地预览

最简单的方式：

```bash
cd ai_governance_portfolio_github
python -m http.server 8000
```

浏览器打开：

```text
http://localhost:8000
```

## 部署到 GitHub Pages

1. 在 GitHub 新建仓库，例如：
   `ai-governance-portfolio`

2. 将本目录下所有文件上传到仓库根目录。

3. 在仓库进入：
   `Settings → Pages`

4. 在 **Build and deployment** 中选择：
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`

5. 保存，等待 GitHub Pages 完成部署。

页面地址通常是：

```text
https://<你的GitHub用户名>.github.io/ai-governance-portfolio/
```

## 建议修改

在 `index.html` 中搜索以下内容并按需要调整：

- `童宇轩`
- `AI Governance Portfolio`
- Footer 里的个人信息
- 项目指标（如果后续 V2.1 / Holdout 结果更新）

## 数据声明

页面中的 Case 与指标均来自基于公开规则构造的模拟治理项目，
不代表任何平台真实内部数据、真实生产模型表现或实际风险分布。
