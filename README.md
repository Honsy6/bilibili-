# bilibili-
这是一个 bilibili 网站视频的爬虫，唯一美中不足就在于它合成视频需要使用到第三方工具 ffmpeg 。
使用说明：
0.使用时请将爬虫文件与 ffmpeg.exe 文件放置于同一目录下。
1.本库没有提供 ffmpeg 工具，需要手动上网搜索下载。（因为文件太大他这不让上传）
2.这些爬虫默认爬取非会员最高清晰度，如需修改移步源码，已经打上了解释。
3.这些爬虫还无法爬取会员视频。
4.如果爬取下来的视频名称跟网上显示的名称不完全一样很正常，因为 ffmpeg 工具无法识别含有特殊符号的视频标题，本爬虫会自动酌情修改视频标题以确保程序能顺利执行。
