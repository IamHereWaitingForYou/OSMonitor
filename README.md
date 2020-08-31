# OSMonitor
实时监控CPU使用情况和磁盘空间统计
OS Monitor 项目结构分为两部分：UI 部分和逻辑部分
UI 部分包括：主程序、磁盘空间扫描 Tab 页、CPU占有率 Tab 页、Controller。UI部分是通过 javafx来实现
逻辑部分主要包括：系统资源获取、文件目录扫描。系统资源是通过OperatingSystemMXBean 来获取。
