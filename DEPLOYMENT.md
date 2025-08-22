# OTTO 专注陪伴玩具 - 部署指南

## 🚀 快速部署

### 1. 本地预览
```bash
# 方法1：直接打开文件
双击 start.html 或 index.html

# 方法2：使用Python本地服务器
python -m http.server 8000
# 然后访问 http://localhost:8000

# 方法3：使用Node.js
npx serve .
# 然后访问显示的本地地址
```

### 2. 部署到Web服务器

#### 使用GitHub Pages（免费）
1. 创建GitHub仓库
2. 上传所有文件
3. 在仓库设置中启用GitHub Pages
4. 选择主分支作为源
5. 访问生成的网址

#### 使用Netlify（免费）
1. 注册Netlify账号
2. 拖拽整个文件夹到Netlify部署区域
3. 自动生成网站链接

#### 使用Vercel（免费）
1. 注册Vercel账号
2. 导入GitHub仓库或直接上传文件
3. 自动部署并生成链接

### 3. 自定义域名（可选）
- 购买域名（如：otto-ai.com）
- 在DNS设置中指向您的服务器
- 在部署平台中配置自定义域名

## 📁 文件结构
```
octopod-ai-website/
├── index.html          # 主网站
├── otto-ai.html        # OTTO产品专门页面
├── styles.css          # 主站样式
├── otto-ai.css         # OTTO产品页样式
├── script.js           # 交互功能
├── start.html          # 启动页面
├── logo.png            # 公司logo
├── favicon.ico         # 网站图标
├── README.md           # 项目说明
└── DEPLOYMENT.md       # 部署指南
```

## 🌐 访问链接

### 主要页面
- **启动页面**: `start.html`
- **主网站**: `index.html`
- **OTTO产品页**: `otto-ai.html`

### 功能特性
- ✅ 完整的中英文双语切换
- ✅ 响应式设计（手机/平板/桌面）
- ✅ 现代化UI/UX设计
- ✅ 平滑动画效果
- ✅ 表单验证和提交
- ✅ SEO友好的HTML结构

## 🔧 技术栈
- **前端**: HTML5, CSS3, JavaScript (ES6+)
- **图标**: Font Awesome 6.0
- **字体**: Google Fonts (Inter)
- **动画**: CSS3 Animations & Transitions
- **布局**: CSS Grid & Flexbox

## 📱 浏览器兼容性
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+
- 移动端浏览器

## 🎯 产品特色
OTTO专注陪伴玩具是一个融合科学训练、效率优化与情感陪伴的AI伙伴：

### 核心功能
1. **专注模式** - 番茄钟工作法 + 视觉监督
2. **冥想模式** - 姿态识别 + 引导训练
3. **奖励系统** - 积分兑换现金奖励
4. **AI陪伴交互** - 个性化对话 + 情感支持

### 价值主张
- 🧠 **注意力训练** - 系统性提升专注力
- 📈 **效率提升** - 高质量学习工作产出
- ❤️ **心理陪伴** - 温暖的情感支持

## 📞 联系信息
- 邮箱：contact@octopod-ai.com
- 电话：+86 400-888-8888
- 地址：中国·深圳

---

*让AI成为人类值得信赖的生活伙伴*
