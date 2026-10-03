# 粒子玫瑰 · 独立发布版

这是完全自包含的静态网页，保留三维花瓣、九万级粒子、慢速聚拢与散开、无屏幕文字，以及手机长按交互。

- 所有 CSS 和 JavaScript 已内嵌到 index.html。
- 不请求 chatgpt.site、GPT API、CDN、外部图片或字体。
- 访客不需要登录 GPT。

## GitHub Pages

把本目录文件提交至公开仓库 main 分支。在仓库 Settings → Pages 中选择 Deploy from a branch，选择 main 和 /(root)，保存。以 GitHub 返回的实际成功发布地址为准。

## Render Static Site

使用此仓库创建 Static Site，构建命令设为 true，发布目录设为 .。

托管平台成功发布不等于所有移动网络都能访问。需在目标手机的 Wi-Fi 和蜂窝网络上分别验证。

数学来源：https://nylander.wordpress.com/2006/06/21/rose-shaped-parametric-surface/
渲染参考：https://github.com/mrdoob/three.js/blob/dev/examples/webgl_buffergeometry_custom_attributes_particles.html
