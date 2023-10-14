# ✨本文件补充一下README中没有说清楚的内容

## 安装
1. 使用Pycharm打开后, 按照提示建立一个`venv`文件夹. 很有必要, 因原项目使用python3.8相关的环境
2. 之后为了能够利用环境, 需要使用Pycharm自带的terimnal运行README中的安装命令。请勿自行打开其它的
3. 按照README中的安装依赖即可. 其中playwright是python中做自动化的, 自然需要安装浏览器内核
4. 如果按照提示安装了pyinstaller, 就可以按照命令打包了. Windows和Mac均可

## 使用
1. 环境配置好后，运行test.py, spider.py等里面的测试代码均可以进行测试和试验
2. 按照README提示`编译主程序`, 即可在./dist/目录下看到可执行文件，使用命令行，如`./dist/douyin -t like`
3. 需要登陆自己的抖音账号, 账号信息存储在`auth.json`当中. 开始不知道自己的`toutiao_sso_user`等信息, 可以先把auth.json删掉后运行, 程序检测不到就会启动浏览器登陆(见`login.py`代码), 登陆后自己账号的信息就会存储在`新生成的auth.json`当中.
4. 如果没有任何 `like`(喜欢视频) 等, 程序是会报Error的, 正常现象.

