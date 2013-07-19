Cloud Foundry 所需Maven依赖库
======

因为Cloud Foundry在部署过程中需要解决大量的依赖库问题，但是从国外网址获取速度很慢，所以将这些依赖项全部打包发送上来
提供快速下载。这些依赖库默认放在用户目录的.m2/repository 目录下，所以下载时，请用如下命令：

    $ mkdir ~/.m2/repository
    $ git clone https://github.com/ChenMingHe/cfrepo ~/.m2/repository

