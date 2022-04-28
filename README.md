c#调用c++多开微信并注入微信源码api接口：
需要两个源码文件，其中 dllmain文件是用 Visual Studio2019 新建的c++ 动态链接库，用来注入和多开微信的代码
wechatmore 文件是Visual Studio2019 新建 c# winfrom程序，用来调用上面dllmain生成的dll的
