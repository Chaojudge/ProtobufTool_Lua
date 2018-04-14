# ProtobufTool_Lua

注意部分操作系统安装后也无法生成.proto文件，需要重启

1.运行：python_2.7.13150.msi,安装，注意要保存好python的安装目录

我的：C:\Python27\

2.环境配置.bat中的路径修改，该批处理文件只修改当前命令窗体的环境变量，关闭后回复:

set %path%="%path%;C:\Python27" 设置成 set %path%="%path%;Python的路径"

只要有涉及到...\protobuf-lua\...路径的，均修改成自身所在目录下的\protobuf-lua\...

3.运行环境配置.bat，若看到Finished...表示成功

4.在Unity3d目录下查找：Packager.cs，打开后查找[MenuItem("LuaFramework/Build Protobuf-lua-gen File")]

修改dir 、protoc 、protoc_gen_dir 路径
