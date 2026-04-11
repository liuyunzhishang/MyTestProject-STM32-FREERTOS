# MyTestProject-STM32-FREERTOS

个人实验库，用于学习STM32的基础HAL库编程和FreeRTOS. 同时，巩固基础的寄存器知识。工程利用AI辅助编程，并在除编码环节外的部分也利用AI进行分析。

## 项目目录结构

本项目采用立芯嵌入式 C 语言编码规范组织代码结构：

### 自研代码目录（遵循立芯规范）
- **[01_App/](01_App/)**        - 应用层代码
- **[01_Service/](01_Service/)** - 服务层代码  
- **[02_Platform/](02_Platform/)** - 平台层代码
- **[03_Bsp/](03_Bsp/)**       - BSP 驱动代码
- **[99_Utils/](99_Utils/)**    - 工具函数代码

### STM32 FreeRTOS 相关目录
- **[03_Os/](03_Os/)**         - FreeRTOS 操作系统相关
- **[Core/](Core/)**           - STM32CubeMX 生成文件
- **[Drivers/](Drivers/)**     - STM32 HAL 驱动库
- **[Middlewares/](Middlewares/)** - 中间件组件
- **[Docs/](Docs/)**           - 项目文档

## 编码规范
- 遵循立芯嵌入式 C 语言编码规范
- 使用 Allman 大括号风格
- 4空格缩进，禁用 TAB
- 文件名：`snake_case`
- 函数名：`PascalCase`
- 所有函数必须包含规范注释
