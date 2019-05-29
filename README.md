# 启动
npm run dev
打开chrome扩展 -> 加载已解压的扩展程序-> 选择生成的dev文件夹

# 功能
webpack-dev-server启动后将文件输出到硬盘中而不是存在内存中，因为扩展插件需要实际的文件。
通过message通信在webpack热更新时执行chrome.reload()，不需要每次热更新都去手动刷新扩展程序的文件。


