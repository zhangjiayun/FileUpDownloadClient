# FileUpDownloadClient

本项目是一个用C++开发的文件上传和下载客户端，暂仅支持window端运行。

是以flamingo-server端的文件服务器（fileserver）为服务端，github地址:  https://github.com/balloonwj/flamingo

暂支持简单传参

上传功能：一个入参，为想要上传文件的绝对路径。上传成功后会在fileserver中的filecache文件夹里以其文件md5码命名的文件保存；

下载功能：两个入参，一个是自定义想要在本地保存文件的绝对路径，如"D:/abc.mp4"；另一个入参为fileserver的filecache文件夹里有的md5文件名。