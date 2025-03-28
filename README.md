# 🚀 起始页项目

## 📖 项目简介
起始页项目是一个集多种实用功能于一体的网页，为用户提供了便捷高效的网页起始体验。它拥有时间显示、天气查询、书签管理、快捷方式设置以及搜索功能等，用户能够根据自己的需求进行个性化设置，快速访问常用网站。😃

---

## ✨ 项目亮点
1. **炫酷加载动画**：页面加载时会呈现由三个旋转立方体组成的炫酷动画，通过 CSS 动画实现流畅旋转效果，带来良好等待体验。🎞️
2. **贴心问候提示**：根据不同时间段，为用户显示相应问候语，如早上显示“早上好”，晚上显示“晚上好”，增加亲切感。😊
3. **实时时间显示**：实时展示当前时间、日期和星期，每秒更新一次，确保信息及时性。⏰
4. **天气信息查询**：通过接口获取当前天气状况和温度范围，不过每日限量 100 次，需前往 [天气 API 网站](https://www.tianqiapi.com/index/doc?version=v6) 免费申请。🌤️
5. **丰富书签管理**：提供多个书签页，涵盖常用、工具、开发、娱乐、学习、设计等类型，方便用户切换和访问不同网站。📑
6. **便捷快捷方式**：用户可自行设置快捷方式列表，以图标和文字形式显示，快速访问常用网站。🚀
7. **智能搜索功能**：支持输入关键词搜索，并提供搜索建议提示，用户可点击建议直接搜索。🔍
8. **个性化设置功能**：用户能打开设置页面，对快捷方式、搜索引擎等进行个性化设置，界面简洁，操作方便。⚙️

---

## 🛠️ 安装步骤
### 1. 🔧 克隆项目
将项目克隆到本地：
```bash
git clone https://github.com/ChinaLysss/Home_Page.git
```

### 2. 🌐 打开页面
在浏览器中打开 `index.html` 文件。

---

## 📂 项目结构
### 1. HTML 文件
- `index.html`：包含页面基本结构，如加载动画、背景图片、主体内容、书签页、设置页等，同时引入必要的 CSS 和 JavaScript 文件。📄

### 2. CSS 文件
- `style.css`：定义页面整体样式，包括布局、颜色、字体等。🎨
- `loading.css`：定义加载动画样式。💫
- `animation.css`：定义页面中使用的动画效果，如渐入动画、文字闪烁动画等。🎉
- `mobile.css`：针对移动端进行样式调整。📱

### 3. JavaScript 文件
- `main.js`：负责页面加载完成后的初始化操作，如载入动画、用户欢迎提示、时间显示、天气查询、书签页和设置页的切换等。💻
- `set.js`：包含快捷方式管理、搜索引擎管理、搜索建议提示、设置页面的打开和关闭等功能的实现。⚙️
- `js.cookie.js`：用于处理 Cookie 相关操作。🍪

### 4. 其他文件
- `vercel.json`：Vercel 部署配置文件。📄
- `favicon.ico`：网站图标。🖼️
- `font` 文件夹：存放字体文件。🅰️
- `img` 文件夹：存放图片文件，如背景图片等。🖼️

---

## ⚠️ 注意事项
1. **天气接口限制**：天气查询接口每日限量 100 次，请前往 [天气 API 网站](https://www.tianqiapi.com/index/doc?version=v6) 免费申请。🌐
2. **中文字体加载**：中文字体缓加载时，由于压缩过后的中文字体仍旧过大，可转移至对象存储或 CDN 加载。📦
3. **图片 API 问题**：若使用的图片 API 失效，可能会影响背景图片显示，需更换其他可用 API。🖼️

---

## 👥 贡献
欢迎提交✨Pull Request或创建💬Issue讨论改进方案！大家一起让这个项目变得更加完美。👏

---

## 📜 许可证
详见项目中的 `LICENSE` 文件。📄

---

## 😊 Have A Good Day ~
🌈 愿代码永远没有 BUG！在使用起始页的过程中，希望能为你带来便捷和愉悦的体验。😘
