🌀 Lain

一个简洁轻量的软件项目。

📁 项目结构
Lain/
├── lain.exe                # 主程序（可执行文件）
├── data/
│   └── project.dp          # 数据存储文件
├── static/                 # 静态资源（图标、CSS样式等）
├── templates/              # 前端页面与 JavaScript 逻辑
└── config.json             # 配置文件，记录数据路径等信息

⚙️ 配置说明

config.json 用于存储程序运行所需的基础配置，例如：

{
    "data_path": "data/project.dp"
}

🚀 使用方法

下载并解压本项目。

确保 config.json 中的数据路径正确。

运行主程序：

lain.exe


打开后即可使用界面进行操作。

💡 文件说明
文件 / 目录	说明
lain.exe	主程序入口
data/project.dp	软件运行数据存储文件
static/	存放图标、样式等静态资源
templates/	存放前端页面与逻辑脚本
config.json	配置文件（包含数据路径等）
🧩 备注

所有前端资源应放置在 templates 与 static 中；

若需迁移或备份，只需同时保存 data/ 与 config.json 即可恢复数据。
