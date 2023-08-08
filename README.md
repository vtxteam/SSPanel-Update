# SSPanel-Update

## 使用方法
1、在网站根目录添加 `version.txt` 文件  
2、将 `<your host>` 改为你站点的地址  
3、将 `<your application>` 改为你应用的命名  

p.s.: macOS不同架构自动更新，将两个不同架构的客户端上传至同一文件夹，命名如需更改请参考官方打包后的命名，即 ”*.pkg" 和 “*-arm64.pkg" 。在 `version.txt` 仅需填写 x64 即 ”*.pkg“ 的下载地址即可，M芯片会自动下载 ”*-arm64.pkg“  版本进行更新
