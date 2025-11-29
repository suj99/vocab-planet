# 词汇星球 (Vocab Planet)

每日英语学习应用 - 帮助初学者掌握3000个日常英语单词

## 功能特点

- 📖 **每日学习** - 可调节每天学习单词数量（5-30个）
- 🎭 **情景练习** - 10个生活场景分类学习
- ✍️ **巩固练习** - 填空选择题强化记忆
- 📰 **趣味阅读** - 分级小短文，点击生词查释义
- 🔊 **发音功能** - 支持美式/英式发音
- 📊 **进度追踪** - 连续学习天数、掌握数量统计

## 部署到 Vercel

### 方法一：通过 GitHub（推荐）

1. 在 GitHub 创建新仓库
2. 上传项目文件
3. 访问 [vercel.com](https://vercel.com)
4. 点击 "New Project"
5. 导入你的 GitHub 仓库
6. 点击 "Deploy"

### 方法二：通过 Vercel CLI

```bash
# 安装 Vercel CLI
npm install -g vercel

# 在项目目录下运行
vercel

# 按提示操作即可
```

## 项目结构

```
vocab-planet/
├── public/
│   └── index.html    # 主应用页面
├── package.json      # 项目配置
├── vercel.json       # Vercel 部署配置
└── README.md         # 说明文档
```

## 本地预览

```bash
# 安装依赖
npm install -g serve

# 启动服务
npx serve public

# 访问 http://localhost:3000
```

## 后续开发计划

- [ ] 扩充词库到完整3000词
- [ ] 添加用户账号系统
- [ ] 增加听写练习模式
- [ ] 开发微信小程序版本
- [ ] 开发 iOS/Android App

## License

MIT
