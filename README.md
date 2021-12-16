# Panda看书

一款 Flutter 写的小说 App

小说界面效果[掘金](https://juejin.cn/post/6844903907110420488)
---


## Show

### gif
<image src="https://file-1301408689.cos.ap-guangzhou.myqcloud.com/image/g1.gif?raw=true" width="300px"/>  <image src="https://file-1301408689.cos.ap-guangzhou.myqcloud.com/image/g2.gif?raw=true" width="300px"/>

### image

<image src="https://file-1301408689.cos.ap-guangzhou.myqcloud.com/githubImage/image1.png?raw=true" width="250px"/>  <image src="https://file-1301408689.cos.ap-guangzhou.myqcloud.com/githubImage/image2.png?raw=true" width="250px"/>  <image src="https://file-1301408689.cos.ap-guangzhou.myqcloud.com/githubImage/image3.png?raw=true" width="250px"/>

<image src="https://file-1301408689.cos.ap-guangzhou.myqcloud.com/githubImage/image4.png?raw=true" width="250px"/>  <image src="https://file-1301408689.cos.ap-guangzhou.myqcloud.com/githubImage/image5.png?raw=true" width="250px"/>  <image src="https://file-1301408689.cos.ap-guangzhou.myqcloud.com/githubImage/image6.png?raw=true" width="250px"/>

<image src="https://file-1301408689.cos.ap-guangzhou.myqcloud.com/githubImage/image7.png?raw=true" width="250px"/>  <image src="https://file-1301408689.cos.ap-guangzhou.myqcloud.com/githubImage/image8.png?raw=true" width="250px"/>  <image src="https://file-1301408689.cos.ap-guangzhou.myqcloud.com/githubImage/image9.png?raw=true" width="250px"/>

---

## Usage

### git

```groovy
https://github.com/q805699513/flutter_books.git

```
### 项目结构

<image src="https://file-1301408689.cos.ap-guangzhou.myqcloud.com/githubImage/lib.png?raw=true" width="350px"/>

| 目录        |                    描述                                | 
| -----------| --------------------------------- | 
| data       |  网络请求封装 [Dio](https://github.com/flutterchina/dio)   | 
| db         | 书架数据库封装 [sqflite](https://github.com/tekartik/sqflite)   |
| event      | 事件总线 [dart-event-bus](https://github.com/marcojakob/dart-event-bus)   |
| res        | 将 colors、dimens、style 等写在该目录下   |
| ui          | ui 界面   |
| ui.bookshelf | 书架页面   |
| ui.details   | 小说详情、章节、内容页   |
| ui.home      | 首页 tab 书城页面   |
| ui.me        | 首页 tab 我的页面  |
| ui.search    | 小说搜索页面   |
| ui.splash    | 小说启动引导页   |
| util   | 工具类   |
| widget   | 自定义 view   |

### 下载

[点击下载](https://file-1301408689.cos.ap-guangzhou.myqcloud.com/apk/books.apk)

#### 二维码下载（Android）

<image src="https://file-1301408689.cos.ap-guangzhou.myqcloud.com/githubImage/download.png?raw=true" width="210px"/>

### 版本更新记录

#### v1.0.0：2020-05-05
*  使用最新的 flutter 版本

#### v1.0.0：2019-08-06
*  小说 app 初始版

### TODO

  更换另一个爬虫小说源，目前暂时使用的[追书api](https://juejin.im/entry/593a3fdf61ff4b006c737ca4)。（进行中）
  
  
## License
```text

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```



