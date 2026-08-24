# 同学图鉴 · GitHub Pages 用户版

这是一个纯静态、只读的用户版网站，没有后台、没有编辑、没有数据库。

## 发布方法

1. 在 GitHub 新建一个公开仓库。
2. 把当前文件夹里的所有文件推送到仓库。
3. 仓库 Settings -> Pages -> Source 选择 `GitHub Actions`。
4. 保存后会自动发布。

## 文件说明

- `index.html`：用户浏览页面
- `app.js`：筛选、详情、照片放大、视频播放
- `styles.css`：页面样式
- `media/`：优化后的照片和视频
- `robots.txt`：允许搜索引擎抓取
- `sitemap.xml`：网站地图
- `.github/workflows/pages.yml`：自动发布配置
