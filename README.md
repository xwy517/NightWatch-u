# 守夜 NIGHTWATCH

一个伪装成智能安防产品官网的互动恐怖网页。单文件静态站点，无后端、无外部请求。

> 内容提示：包含突然音效、闪烁画面和惊吓镜头。页面不会访问摄像头或麦克风；页面中显示的时间、设备、屏幕与滚动距离均由浏览器本地计算。

## 在线访问

部署到 GitHub Pages 后：

```
https://<你的用户名>.github.io/nightwatch/
```

## 部署

1. 仓库根目录保持 `index.html` 与 `.nojekyll`。
2. 仓库 **Settings → Pages**。
3. Source 选择 **Deploy from a branch**，分支 `main`，目录 `/ (root)`，保存。
4. 等待 1–3 分钟，页面顶部会出现站点地址。

## 更新

重新上传 `index.html` 并提交，GitHub Pages 会自动重新发布。

## 本地预览

直接双击 `index.html` 即可；声音需要点击右上角“声音”按钮后才会播放。
