## 场景一（静态资源加速）

### 静态资源较多的站点/应用加速

站点或者应用中大量静态资源的加速分发，建议将站点内容进行动静分离，动态文件可以结合云服务器ECS，静态资源如图片，HTML，css，js文件等，建议结合，对象存储OSS存储海量静态资源，可以有效加速内容加载速度，轻松搞定网站图片，端视频等内容分发。

#### 对象：新闻门户，企政网站，访问量比较大的其他网站。

## 场景二（音视频点播）

### 音视频点播/大文件下载分发加速

支持各类文件的下载，分发，支持在线点播加速业务，如MP4，flv视频文件或者平均单个文件大小在20M以上，主要的业务场景是音视频点播，大文件下载（如安装包下载）等，建议搭配对象存储OSS使用，可提升回源速度，节约约2/3回源宽带成本。

#### 对象：在线广播，视频网站，下载站点。

## 场景三（移动APP）

### 移动英勇加速

移动app更新文件（apk文件）分发，移动app内图片，页面，短视频，UGC等内容的优化加速分发。提供httpDNS服务，避免DNS劫持并获得实时精确的DNS解析结果，有效缩短用户访问时间，提升用户体验。

#### 对象：小图片，短视频，文件下载。

## 场景四（视频直播）

### 视频直播加速

视频流媒体直播服务，支持媒资存储，切片转码，访问鉴权，内容分发加速一体化解决方案，结合弹性伸缩服务，及时调整服务器带宽，应对突发流量访问；结合媒体转码服务，享受高速稳定的并行转码，且任务规模无缝扩展。

#### 对象：网络电视，俱乐部，企业培训。

## 计费模式

- 按带宽计费
- 按流量计费

带宽利用率 = 实际使用流量GB/（带宽峰值Mbps x 10.54），**1Mbps**带宽每日100%利用率产生的流量约为**10.54GB**

