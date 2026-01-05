# NowFocus GitHub Pages Setup - 使用说明

## 📁 文件结构

```
hackergin.github.io/
├── index.html                      # 主页（项目列表）
└── NowFocus/
    ├── index.html                  # NowFocus 首页
    ├── support.html                # 支持页面（App Store Support URL）
    └── privacy-policy.html         # 隐私政策页面
```

## 🌐 访问 URL

假设你的 GitHub 用户名是 `hackergin`：

- **主页:** https://hackergin.github.io/
- **NowFocus 首页:** https://hackergin.github.io/NowFocus/
- **支持页面:** https://hackergin.github.io/NowFocus/support.html ⭐
- **隐私政策:** https://hackergin.github.io/NowFocus/privacy-policy.html ⭐

## 📝 App Store Connect 填写

### 1. Support URL（必填）
```
https://hackergin.github.io/NowFocus/support.html
```

### 2. Privacy Policy URL（必填）
```
https://hackergin.github.io/NowFocus/privacy-policy.html
```

### 3. Marketing URL（可选）
```
https://hackergin.github.io/NowFocus/
```

## ⚠️ 提交前必须修改的内容

### 在 support.html 中修改：

1. **邮箱地址**（第 451 行附近）：
```html
<a href="mailto:support@yourdomain.com">support@yourdomain.com</a>
```
改为你的真实邮箱：
```html
<a href="mailto:your-email@example.com">your-email@example.com</a>
```

2. **GitHub 链接**（第 460 行附近）：
```html
<a href="https://github.com/yourusername/nowfocus">GitHub</a>
```
改为你的 GitHub 仓库：
```html
<a href="https://github.com/hackergin/work_manager_for_ADHD">GitHub</a>
```

### 在 index.html 中修改：

同样修改 GitHub 链接（第 99 行附近）

## 🚀 部署步骤

1. **提交更改到 Git**
```bash
cd /Users/feng/projects/hackergin.github.io
git add .
git commit -m "Add NowFocus support and privacy pages"
git push origin main
```

2. **等待 GitHub Pages 部署**
- 通常需要 1-5 分钟
- 访问 https://github.com/hackergin/hackergin.github.io/settings/pages 查看状态

3. **验证页面**
- 访问 https://hackergin.github.io/NowFocus/support.html
- 检查所有链接是否正常工作
- 确认邮箱和 GitHub 链接已更新

## ✅ 提交前检查清单

- [ ] 修改 support.html 中的邮箱地址
- [ ] 修改 support.html 中的 GitHub 链接
- [ ] 修改 index.html 中的 GitHub 链接
- [ ] 提交并推送到 GitHub
- [ ] 等待 GitHub Pages 部署完成
- [ ] 访问 URL 验证页面正常显示
- [ ] 测试所有链接（支持、隐私政策、GitHub）
- [ ] 确认页面在手机和桌面浏览器都能正常显示

## 📱 页面内容概览

### support.html 包含：
- ✅ 应用介绍和功能特性
- ✅ Mac 和 iOS 设置指南
- ✅ 备忘录格式详细说明
- ✅ 常见问题解答（10+ 个问题）
- ✅ 故障排除指南
- ✅ ADHD 用户使用技巧
- ✅ 联系方式
- ✅ 响应式设计（手机友好）

### privacy-policy.html 包含：
- ✅ 数据收集说明
- ✅ 备忘录访问说明
- ✅ iCloud 同步说明
- ✅ 用户权利
- ✅ 联系方式

## 🎨 设计特点

- 现代化渐变配色（紫色系）
- 完全响应式设计
- 清晰的排版和层次结构
- 适合 ADHD 用户的简洁界面
- 专业的视觉效果

## 🔄 后续维护

当应用更新时，记得更新：
- 功能列表
- 使用说明
- FAQ 内容
- 版本号（在隐私政策中）

## 💡 提示

1. **测试邮箱链接**：点击邮箱链接确保能正常打开邮件客户端
2. **检查移动端**：在手机浏览器测试页面显示效果
3. **SEO 优化**：页面已包含 meta 描述，有利于搜索引擎收录
4. **备份**：提交到 Git 前先备份原有内容

---

## 🎯 App Store 审核时的优势

这些页面会给审核员留下专业印象：

- ✅ 详细的功能说明和使用指南
- ✅ 全面的 FAQ 覆盖常见问题
- ✅ 清晰的隐私政策
- ✅ 专业的设计和用户体验
- ✅ 明确的联系方式

审核员能快速找到他们需要的所有信息，提高审核通过率。

---

创建时间：2026-01-06
