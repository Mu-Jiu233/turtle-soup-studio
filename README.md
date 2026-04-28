# 🐢 海龟汤创作工坊

AI 海龟汤（横向思维谜题）自动生成工具，完整自包含单文件，无任何外部依赖。

---

## 快速部署

### 方式一：Cloudflare Pages（推荐，免费永久）

1. 访问 [https://pages.cloudflare.com](https://pages.cloudflare.com)
2. 注册/登录后，点击 **Create a project**
3. 选择 **Direct Upload** → 直接拖入本目录的 `index.html`
4. 点击 **Save and Deploy**，获得类似 `xxx.pages.dev` 的免费地址
5. 可选：绑定自定义域名

### 方式二：Vercel

1. 访问 [https://vercel.com](https://vercel.com)
2. 注册后，点击 **Add New Project** → **Import**
3. 将本目录文件上传或连接 GitHub 仓库
4. 点击 **Deploy**，获得免费地址

### 方式三：Netlify

1. 访问 [https://netlify.com](https://netlify.com)
2. 注册后，点击 **Add new site** → **Deploy manually**
3. 拖入 `index.html` 所在文件夹
4. 完成，获得免费子域名

### 方式四：GitHub Pages

1. 创建 GitHub 仓库，上传 `index.html`
2. 进入 Settings → Pages → Source 选择 `main` 分支
3. 等待部署，访问 `https://你的用户名.github.io/仓库名`

### 方式五：本地使用

直接双击 `index.html` 用浏览器打开即可，配置 API 后离线可用。

---

## 使用前准备

首次使用需要配置一个 AI API（一次性操作）：

1. 点击右上角 **⚙️ API 配置**
2. 选择平台预设（推荐 **DeepSeek**，便宜且国内可用）
3. 到对应平台申请 API Key 并填入
4. 点击 **测试连接** → 成功后保存

推荐平台：
- **DeepSeek**：[https://platform.deepseek.com](https://platform.deepseek.com)（性价比最高）
- **通义千问**：[https://dashscope.console.aliyun.com](https://dashscope.console.aliyun.com)
- **智谱 GLM**：[https://open.bigmodel.cn](https://open.bigmodel.cn)
- **OpenAI**：[https://platform.openai.com](https://platform.openai.com)

---

## 功能说明

| 模块 | 说明 |
|------|------|
| 复杂程度 | Lv.1~Lv.5 + 随机 |
| 主题风格 | 12种风格多选 |
| 陷阱机制 | 5级陷阱自由组合 |
| 汤面字数 | 7档（30字~300字） |
| 反转层数 | 7种（无反转~四层深渊） |
| 主角设定 | 自定义角色名字 |
| 特殊要求 | 任意补充描述 |
| 流式输出 | 实时看到生成过程 |
| 历史记录 | 本地自动保存 |

---

## 文件说明

```
deploy-turtle-soup/
├── index.html   ← 部署时上传此文件
└── README.md    ← 部署说明（可选删除）
```

**注意**：`index.html` 为完全自包含文件，不依赖任何外部资源，可直接部署。
