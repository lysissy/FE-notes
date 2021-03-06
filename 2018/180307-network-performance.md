# 网络性能优化

### 资源优化
关键词：关键请求<br>
方案：
* 主动缓存  
* 启用压缩
* 优先关键资源
* 使用CDN

### 图片优化
* 选择正确的格式<br>

格式 | JPEG | PNG-8 | PNG-24 | GIF
-----|------|-------|--------|-------
适用范围 | 色彩丰富的非透明图片（如照片） | 色彩不是很丰富的图片 | 有部分透明度的照片 | 动画图片

    
* 尽可能使用矢量图
* 如果变化不明显，则降低质量
* 尝试新格式（关键词:WebP）
* 使用工具和算法进行优化（关键词: ImageOptim、Guetzli）
* 响应式图片（关键词：picture元素、srcset属性）
* 使用图片CDN

### 网络字体优化
* 选择正确的格式：EOT、TTF、WOFF、WOFF2
* 字体选择评测
* 使用Unicode-range子集
* 建立字体加载策略（关键词：font-display）

### Javascript优化
* 监控Javascript传输
* 移除不必要的依赖
* 实施代码分割
* 考虑框架选择

#### 一些性能指标
* 以用户为中心的性能指标：
    + 白屏时间
    + 首次有效渲染
    + 视觉完整
    + 可交互时间
* 设置性能预算
* 持续监控（Lighthouse、Calibre）
* 建立性能意识和同理心

###### 参考资料
1. [网络现状：性能提升指南](https://github.com/xitu/gold-miner/blob/master/TODO/talk-the-state-of-the-web.md)