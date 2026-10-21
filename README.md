# AI 秋招面试平台

面向 AI 全栈开发 / AI 创造者学生的秋招求职工作台：选一个岗位族，生成这条路的五步路线——投哪些公司、刷哪些面试题、刷哪些算法题、四周怎么排、看哪些资料。

- 3823 家企业开发研发岗（12 个岗位族，可筛选可搜索）
- 171 道面试题（含考点 / 答法 / 追问三层）
- 50 道 LeetCode + 18 道手撕题

## 部署到 GitHub Pages

1. 新建一个 **public** 仓库（例如 `aiqiuzhao`）
2. 把本目录下的 `index.html`、`jobs.js`、`.nojekyll` 三个文件上传到仓库根目录
3. 仓库 → Settings → Pages → Source 选 `Deploy from a branch`，Branch 选 `main` / `root`，保存
4. 等 1-2 分钟，访问 `https://<你的用户名>.github.io/aiqiuzhao/`

## 注意

- `jobs.js` 必须和 `index.html` 一起上传，否则岗位库为空（题库和路线不受影响）。
- `.nojekyll` 用来关掉 GitHub 的 Jekyll 处理，别删。
- 页面所有数据都是静态的，不需要后端；勾选进度存在浏览器本地。
- 岗位数据来自本地校招内推表，投递前请以企业官网实时状态为准。
