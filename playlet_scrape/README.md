<center><img src="https://raw.githubusercontent.com/htnanako/MovieBot_plugins/main/playlet_scrape/amd64/playlet_scrape/logo.jpg"  alt=""/></center>


## 短剧刮削

> 基于MovieBot插件系统实现的短剧刮削工具。

### 使用

#### 一、下载本插件

- 目前仅支持amd64的设备使用，拷贝amd64文件夹下的playlet_scrape文件夹到插件目录。
- 重启MovieBot

#### 二、注册数据库认证key

- 在插件管理-快捷功能中，点击注册短剧数据库认证key。
- 输入邮箱提交，从弹窗或者日志获取key，为64位的字符串。
- 复制得到的key，填写到插件配置里

#### 三、配置其他信息

- 监控路径，可填写多个监控的下载路径，用英文逗号(,)隔开。每个下载路径后用英文冒号(:)接上一个目标整理路径。例如"/movie/downloads/短剧1:/movie/link/短剧1,/movie/downloads/短剧2:/movie/link/短剧2"
- 监控路径需要在MovieBot的媒体文件夹设置中添加，类型选择XX即可。
- 默认的整理路径，用于手动执行刮削任务时的默认整理路径。
- 是否生成单集的信息文件。关闭则不会刮削单集的nfo文件。

### 关于ARM。

- 目前仅支持amd64设备安装的MovieBot使用。如果有arm设备需求，请提交issues，并附上设备信息，可能会考虑增加支持。