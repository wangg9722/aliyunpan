# 小白羊云盘Open API版本

基于 https://github.com/liupan1890/aliyunpan 仓库。
原作者 @liupan1890已停止维护，开源的项目，而且没有LICENSE问题，每个人都可以基于此来做2次开发，没有任何法律和道德的问题，不要来我的地盘撒野。
使用新版API，支持阿里云盘的所有功能。

# 使用方法
见 源码开发打包帮助.md

# 入群
https://t.me/+wjdFeQ7ZNNE1NmM1

# 功能说明
1. 登录: 阿里云Open API相比之前的版本功能受限，只开放了很少量的功能，如果完全弃用旧版API,小白羊的功能会大打折扣。
因此，项目基于两套阿里云API。
2. 最近放映室：新增了最近播放列表菜单，可以查询最近播放视频，并支持保存观看进度。
3. 修改了app的图标，更加简洁。
4. 替换了APP中所有的图标，我觉得以前的图标不够亮色，大气。
5. 优化了布局，包括搜索按钮提升到主页，新建按钮缩减为一个大大的加号。
6. 去掉了一些未完成的功能模块。显得多余。
7. 修复了下载上传完成提示音在某些平台上上无法生效问题。
8. 其他影响程序使用的若干bug修复。
9. 修复文件夹上传层次不正确问题。
10. 最近播放升级为放映室，支持列出网盘全部专辑以及正在观看视频。
11. 修复版本升级重新安装小白羊登录失败问题。
12. 修复单个文件链接分享问题。
13. 修复因为旧API 访问失败 导致的用户信息加载时间过长问题。
14. 修复上传下载音效无音效提示问题
15. 修复视频观看，下载，上传问题以及优化，
16. 新增最近播放视频列表，支持进度记忆。
17. 新增开机自启选项
18. 扫描重复文件，新增全选按钮
19. 视频播放支持外挂网盘同目录下的字幕文件，目前支持srt|vtt|ass格式
20. web播放器支持一键截图按钮
21. 针对aria2连接失败问题，设置中新增本地aria2c，可以指定本地的aria2c路径和配置文件来启动aria2c了。
22. 针对每次点击上传资源都会要求设置冲突文件处理逻辑，将上传遇到重复文件处理移到设置中。
23. 修复上传文件夹，文件夹层次不对的问题
24. 修复不能重复下载同一文件bug。
25. 优化app icon图标。
26. 修复mac下不能自定义播放器播放bug。


# 注意事项
如果在使用过程中遇到问题，欢迎大家提出issue，我会长期维护该项目。

# License
[LICENSE](./LICENSE)


# Star History
[![Star History Chart](https://api.star-history.com/svg?repos=gaozhangmin/aliyunpan&type=Date)](https://star-history.com/#gaozhangmin/aliyunpan&Date)

# 免责声明

1.本程序为免费开源项目，旨在分享网盘文件，方便下载以及学习electron，使用时请遵守相关法律法规，请勿滥用；

2.本程序通过调用官方sdk/接口实现，无破坏官方接口行为；

3.本程序仅做302重定向/流量转发，不拦截、存储、篡改任何用户数据；

4.在使用本程序之前，你应了解并承担相应的风险，包括但不限于账号被ban，下载限速等，与本程序无关；

5.如有侵权，请通过邮件与我联系，会及时处理。
