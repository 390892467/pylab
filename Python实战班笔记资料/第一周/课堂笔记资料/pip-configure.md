## pip 配置使用国内镜像

1. 创建目录 `mkdir ~/.pip`
* 编辑 `~/.pip/pip.conf`, 输入一下内容

  ```ini
  [global]
  index-url = http://mirrors.aliyun.com/pypi/simple/
  trusted-host = mirrors.aliyun.com
  ```
