## 版本依赖

| 依赖     | 版本     |
| -------- | -------- |
| node.js  | v10.16.1 |
| npm      | 6.9.0    |
| @vue/cli | 3.10.0   |

## 说明

> **在执行任务前，请确保机器人正确初始化了**

Demo 项目实现了以下功能：

1. 地图的查询及展示
2. 手画路径的查询及展示
3. 手画路径的绘制
4. 手画路径的删除
5. 手画路径的任务执行
6. 手画路径的任务停止

## Demo 示例

### 地图查询及展示


![size:800,1000](http://39.98.34.145/storage/2021/01-27/tTJbJQl19qdWLGA1pa3usLYo8YP28MtPQ2DzI30V.jpeg "地图查询及展示")

### 手画路径查询及展示
![size:800,1000](http://39.98.34.145/storage/2021/01-27/WBbMhlDDnqFB3IorhJmIOHFCkwHBJYayxt3N3x6b.jpeg)
### 手画路径的绘制


![size:800,1000](http://39.98.34.145/storage/2021/01-27/VjOVJWuWYOVpmc1BGTzcvrCksRakuZMOHIbjqIJC.jpeg)

![size:800,1000](http://39.98.34.145/storage/2021/01-27/1627cBWifQKV5ktRK8ilbM9goKuwrOMs12SETr2V.jpeg)
### 手画路径的删除
![size:800,1000](http://39.98.34.145/storage/2021/01-27/A67I1bKihjXiKRiHCw6msXcA4gfm4WJW7WKFzFmO.jpeg)


### 手画路径的任务执行
![size:800,1000](http://39.98.34.145/storage/2021/01-27/rEZIQi5GGNOcQiiyKKrE2sF8qbDxzv14yjyAYBe6.jpeg)


### 手画路径的任务停止
![size:800,1000](http://39.98.34.145/storage/2021/01-27/k5FG3FFMqOXtKShAEcbS9JOGY9mpuqg8zGhLTI9w.jpeg)

### 操作演示视频下载

[模块demo 操作演示视频](http://39.98.34.145/storage/2021/01-27/RTxfOTYKyLakxDl9RMNZMMs9105P3iwnVxCyljXU.zip)



### demo代码

[demo](http://support.agilex.ai/storage/2021/02-05/amMm1tcxcKYiqrJAr6ov2oEEJVxseXN7FZth2q4w.zip)

## 项目代码说明

* gsApi.js  该类封装了对导航的http请求
* CanvasManager.js 该类主要负责对canvas 的渲染管理操作
* DataManager.js 该类主要负责对http请求返回的数据进行一个解析和管理