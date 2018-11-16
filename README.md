# PyCTP
CTP for Python

这是程序化期货交易上期ctp接口版本.将其包装为python版本. 支持python3
编译需求:根据自己python对就的MSC版本号下载对应的VS
编译方法 python setup.py build

> 编译指南请关注公众号：PyCTP6,并回复“编译”

#目录说明
PyCTP_test  我用python3.7编译好的接口，如果不想自己编译的，可以拿去直接用。
里面有测试文件，修改test_PyCTP.py文件中main方法的期货账号，密码，然后运行即可开始开发测试。

src 为接口转换工程原文件，不能修改
v6.3.6 打头的3个文件为CTP官方版本接口文件