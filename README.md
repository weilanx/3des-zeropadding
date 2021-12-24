# 3des-zeropadding
* 这是3des加密的简单实现，采用了0填充
* 3des加密的填充问题，一直没有最佳解决方案。即使是复杂的位数填充，也可能有凑巧填充的就是加密后的字符。
* 用法：
* 1. 点击文件夹空白处按住shift右键打开powershell窗口
* 2. 输入命令举例
	./3des en 11224477 a.jpg d://en.txt
* en对应加密，de对应解密，11224477为8位密钥，下面两个文件是源文件和目标文件
* 执行该命令后将该文件目录下的a.jpg加密后放到d://en.txt中
