# Install-SmartGit-for-Ubuntu
This is a document about  how to install SmartGit for Ubuntu

* 准备过程
    * 官方下载SmartGit
        * 地址：https://www.syntevo.com/smartgit/download
    * 下载最新JRE包
        * 地址：http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html（可选）
* 安装过程
    * 解压SmartGit安装包
    * 解压JRE包
        * 新建在home下建立一个文件夹，把JRE压缩包解压到该文件中，记住把该路径拷贝下来
    * 修改SmartGit中的smartgit.vmoptions
        * 这个文件为空，主要是为了记录JRE的路径。把路径粘贴在文件内容中，格式：jre=/home/XX/jre/jre1.8.0_144
    
    * 打开终端：执行/home/XXX/SmartGit/smartgit/bin/smartgit.sh文件即可
    
    
