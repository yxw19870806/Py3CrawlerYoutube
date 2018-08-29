# Py3CrawlerYoutube
## 如何运行
1. 参照[/common/README.md](https://github.com/yxw19870806/Py3CrawlerLib/blob/master/README.md)安装对应依赖包
2. 根据需求运行对应py文件<br>
/project/youtube/youtube.py 爬取指定账号的所有视频<br>
/project/youtube/download.py 爬取指定播放地址的视频

## 存档格式
1. 账号ID
2. 最后下载视频的ID（下载完成后自动记录，第一次使用不用填写）
3. 最后下载视频的发布时间（精确到天，下载完成后自动记录，第一次使用不用填写）
4. 频道名字（下载过程中自动获取，第一次使用不用填写）

## 账号ID获取步骤
点击视频发布者头像旁的名字，进入频道主页
地址类似为 https://www.youtube.com/channel/[UCa1b2c3d4e5f_6g7h8i9j0k]，其中[]中的字符（实际不包括[]）就是账号的ID
