# medialpha
a personal local web video media-player (golang+vue3)


部署流程：
1. build前端，npm build，得到dist文件夹
2. 将dist文件夹放入后端根目录
3. build后端，go build，得到可执行文件（build前，请启动一次main.go以生成configs/controllers.json）
4. 将可执行文件 + configs + dist 复制出来即可运行
