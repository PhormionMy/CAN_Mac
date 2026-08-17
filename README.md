# CAN Mac Analyzer

CAN协议分析工具，采用Mac风格的CANoe界面设计。

## 功能特性

- **DBC文件导入** - 完整解析DBC文件中的报文定义、信号定义、注释、属性和值表
- **ASC文件解析** - 解析Vector ASC格式的CAN日志文件
- **BLF文件解析** - 解析Vector BLF二进制日志格式（使用pako解压zlib压缩数据块）
- **信号解码** - 支持Intel/Motorola字节序、有符号/无符号信号、因子偏移计算
- **波形显示** - Canvas绘制时间-信号值波形图
- **数据视图** - 原始数据表格和信号值展示
- **协议视图** - DBC定义详情浏览
- **Mac风格UI** - 深色主题、macOS窗口控件、SF Pro字体、圆角设计

## 使用方法

1. 点击工具栏的 **DBC** 按钮导入DBC文件
2. 点击 **ASC/BLF** 按钮导入ASC或BLF日志文件
3. 点击 **解析** 按钮开始解析
4. 在左侧报文列表中选择报文查看详情
5. 在波形视图中查看信号波形

## 技术栈

- 纯前端单HTML文件架构
- 内联pako库用于BLF解压
- Canvas绘制波形
- 响应式设计

## 在线访问

[https://phormionmy.github.io/CAN_Mac/](https://phormionmy.github.io/CAN_Mac/)

## License

MIT
