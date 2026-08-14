# Oil-Price-Comparison
实现两个主要的功能： 
1 .能够迅速在陌生城市算出周边价格最低的加油站。 2.快速计算去哪里要花多少油价。

使用条件

电脑需要联网，地图、油站搜索和图标资源依赖网络。
建议使用最新版 Chrome、Edge 或 Safari。
当前数据保存在浏览器本机，不会自动同步到其他电脑。
请先完整解压压缩包，不要直接在压缩包预览窗口中运行。
macOS

双击 start-mac.command。
浏览器打开 http://127.0.0.1:4190/index.html
终端窗口需保持开启；结束使用时可关闭终端窗口。
如果系统阻止首次运行，可右键 start-mac.command，选择“打开”。
Windows

电脑需安装 Python 3，并在安装时启用 Python Launcher。
双击 start-windows.bat。
浏览器会自动打开应用；命令窗口需保持开启。
高德地图说明

本发布包不包含任何 API Key 或安全密钥。
首次使用地图、路线或油站搜索前，请在网页左下角“设置”中填写你自己的高德 Web 端 Key
与 securityJsCode，并确认该 Key 允许 localhost / 127.0.0.1 来源访问。
凭证仅保存在当前浏览器的本机存储中，不会写入源码、导出数据或便携包。
v1.11.1 变化

移除源码与发布包中的全部默认高德 API 凭证。
设置页提供用户自有 Web Key 与 securityJsCode 的保存、显示和清除入口。
未配置时地图功能会明确提示，不影响油价计算、方案和加油记录。
v1.11.0 变化

新增 macOS 风格侧边工具坞、沉浸式中央画布与 GLSL 动态环境光。
桌面和手机均采用专门布局；手机端可单列滚动完成计算与查看结果。
统一高德地图加载与地点搜索缓存，减少重复 SDK、插件和检索请求。
行程候选先在本机估算距离，选定终点后才请求一次真实驾车路线。
“最省钱路线”仍暂时关闭，不会初始化该功能或占用其地点搜索额度。
<img width="1678" height="1081" alt="截屏2026-08-12 23 27 33" src="https://github.com/user-attachments/assets/07612760-b7b2-48af-93ac-195f967ac1d5" />
<img width="1678" height="1051" alt="截屏2026-08-12 23 53 02" src="https://github.com/user-attachments/assets/e057cd1f-4dac-4886-bbce-91b7455b4f2e" />
<img width="1678" height="1081" alt="截屏2026-08-12 23 27 41" src="https://github.com/user-attachments/assets/bd384e25-1895-436c-8ca8-91e2024d68ba" />
<img width="1678" height="1081" alt="截屏2026-08-12 23 28 04" src="https://github.com/user-attachments/assets/d4875e5b-a3e4-41f7-9679-d4389d089350" />
