## 一个小型的数据爬取+数据提取+数据报告
**运行顺序：**

1.先运行`server.py`服务器，

2.再运行`fetch_data.py`抓取内容，生成一个`devicde_logs.csv`，

3.之后再运行`generate_report.py`，把抓取到的内容转到生成的专家报告里`系统诊断报告.html`

4.在`系统诊断报告`的html页面里，上面有个`下载.pdf`类似的按钮
