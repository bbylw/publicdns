# 🌐 公共 DNS 导航 (Public DNS Guide)

> **精选全球高速、安全的免费公共 DNS 服务**  
> *Premium UI • Glassmorphism • Interactive Spotlight*

这是一个设计精美、交互流畅的静态网页，旨在为用户提供全球知名公共 DNS 服务的快速索引。项目采用现代化的 **Glassmorphism (毛玻璃)** 设计风格，结合 **深色模式** 和 **动态光效**，提供极致的视觉体验。

## ✨ 核心亮点 (Key Features)

*   **🎨 极致视觉体验**
    *   **动态背景**：沉浸式流体网格渐变背景，搭配细腻的噪点纹理 (Noise Texture)。
    *   **毛玻璃特效**：全站采用 Glassmorphism 设计，半透明磨砂质感，层次分明。
    *   **聚光灯特效 (Spotlight)**：卡片支持鼠标跟随光效，悬停时自动照亮边框与背景。

*   **⚡ 高效交互**
    *   **一键复制**：悬停显示复制按钮，点击即刻复制 IP 地址，并伴有触感反馈。
    *   **快捷搜索**：支持实时过滤，按下键盘 **`/`** 键即可快速聚焦搜索框。
    *   **响应式布局**：完美适配桌面端、平板及移动端设备，IP 地址在桌面端采用双列网格布局。

*   **🛡️ 全面专业**
    *   **数据完整**：收录 IPv4/IPv6 双栈地址。
    *   **加密支持**：详细列出 **DoH (DNS over HTTPS)** 和 **DoT (DNS over TLS)** 接口。
    *   **分类清晰**：支持按“国内首选”、“国际推荐”、“安全防护”、“IPv6”等维度筛选。

## 🚀 收录服务商

本项目精选收录了全球最值得信赖的 DNS 服务商：

### 🌏 国际/海外
*   **Cloudflare** (1.1.1.1) - 全球最快，隐私优先
*   **Google Public DNS** (8.8.8.8) - 基础设施强大，稳定可靠
*   **OpenDNS** - Cisco 旗下，家庭网络安全首选
*   **Quad9** - 非营利组织，专注恶意域名拦截
*   **AdGuard DNS** - 原生广告拦截与隐私保护

### 🇨🇳 国内/中国
*   **阿里 AliDNS** (223.5.5.5) - 稳定高速，电商优化
*   **腾讯 DNSPod** (119.29.29.29) - 防劫持，针对国内网络优化
*   **114 DNS** (114.114.114.114) - 国内老牌服务，覆盖广
*   **百度公共 DNS** (180.76.76.76) - 百度云防护技术
*   **字节跳动 TrafficRoute** (180.184.1.1) - 企业级解析能力

## 🛠️ 技术栈 (Tech Stack)

本项目坚持 **"Zero Dependency"** (零依赖) 原则，仅使用原生技术构建：

*   **HTML5**: 语义化标签结构。
*   **CSS3**: 
    *   CSS Variables (主题配置)
    *   Backdrop Filter (毛玻璃)
    *   CSS Grid & Flexbox (布局)
    *   Keyframe Animations (动画)
    *   Masking & Gradients (光效)
*   **JavaScript (Vanilla)**: 原生 DOM 操作，无任何类库依赖。

## 📦 使用方法 (Usage)

由于是纯静态网页，无需复杂的构建流程。

### 方式一：直接预览
1.  下载本项目代码。
2.  直接双击打开 `index.html` 文件即可体验。

### 方式二：本地服务 (推荐)
为了获得完整的 HTTP 协议体验 (如复制功能的权限控制)，建议使用本地服务器运行：

**Python:**
```bash
python -m http.server
```

**Node.js:**
```bash
npx http-server
```

## 📂 目录结构

```text
.
├── index.html      # 核心页面 (结构与逻辑)
├── style.css       # 样式表 (视觉设计与动画)
└── README.md       # 项目文档
```

## 📝 贡献与自定义

如果你想添加新的 DNS 服务商，只需编辑 `index.html` 中的 `<section class="dns-grid">` 区域，复制现有的 `.dns-card` 结构并修改数据即可。

---
*© 2024 Public DNS Guide. Designed with ❤️.*
