# WeChat-Elegant Themes

一套专为微信公众号排版优化的跨平台编辑器主题。追求极致的人文感排版，核心采用 **Optima** 与 **PingFang SC Light** 字体组合。

## 🌟 特性
- **人文感字体栈**：西文 Optima 搭配中文极细平方，视觉清透、具有呼吸感。
- **公众号适配**：针对微信后台过滤器优化，解决 H2 边线丢失、图片同步等痛点。
- **多平台统一**：同时支持 Typora (.css), Ulysses (.ulstyle) 和 iA Writer (.iatemplate)。
- **精排细节**：黄色荧光笔高亮样式、左对齐断词优化、1.8x 黄金行高。

## 📸 预览å
> [此处建议放置一张你在 Mac Studio 上截取的 Typora 渲染图]

## 🛠 安装方法

### Typora
1. 打开 Typora 偏好设置 -> 外观 -> 打开主题文件夹（通常在 `~/Library/Application Support/abnerworks.Typora/themes`）。
2. 将 `Typora/wechat-elegant.css` 放入该文件夹。
3. 重启 Typora，在菜单栏“主题”中选择 `WeChat-Elegant`。

[Write Custom Typora Theme](https://theme.typora.io/doc/zh/Write-Custom-Theme/)

### iA Writer
1. 在 Finder 中进入 `iA-Writer/` 文件夹。
2. 双击 `WeChat-Elegant.iatemplate` 即可自动安装。

iA Writer 主题默认安装位置通常在 `~/Library/Containers/pro.writer.mac/Data/Library/Application Support/iA Writer/Templates`

### Ulysses
1. 双击 `Ulysses/wechat-elegant.ulstyle` 进行安装。

## 📝 写作建议 (针对微信公众号)
由于微信后台的限制，建议配合以下流程以获得最佳效果：
1. 在 Typora 中编写完成。
2. 使用 `导出为 HTML` 功能。
3. 在浏览器打开 HTML，全选并粘贴至微信后台。

## 在图片下方增加一行「图注（Caption）」

当给图片加 alt，也就是 markdown 的 `![猫](cat.jpg)` 语法中`[]`里的描述内容，iA Writer 和 Ulysses 会解析成 figcaption，但 Typora 不予处理，所以 Typora 可以手动在紧跟图片后用 `<small>` 标签，例如：

```markdown
![](cat.jpg)
<small>猫咪</small>
```

## 📄 License
[MIT](LICENSE) © Huang Yang
