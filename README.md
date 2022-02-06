# 这里是`Request Counter`的文档
虽然说项目很小根本不需要文档

## 部署到本地服务器
 ```shell
 $ git clone https://git@github.com:MarkusJoe/RequestCounter.git
 $ cd RequestCounter
 $ pip3 install -r requirements.txt
 $ python3 app.py 
 ```

> 程序还支持自定义图片的大小需要在`./bin/core/length.py` 中修改 `make_html`函数的参数

### 基本信息
- Python版本: `3.9.9`
- 请求方法: `GET` `POST`
- 请求地址: `/API`
- 请求参数: `name` : `str`
  - 可选参数: `length` : `int`


### 注意事项
- Python版能最新版就最新版
- 项目使用了标准库`Sqlite3`进行了数据库操作某些免费部署的服务器可能不支持


### 开源
- 本项目以Apache-2.0许可开源, 即:
  - 你可以直接使用该项目提供的功能, 无需任何授权
  - 你可以在**注明来源版权信息**的情况下对源代码进行任意分发和修改以及衍生