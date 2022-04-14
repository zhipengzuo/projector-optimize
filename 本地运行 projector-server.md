### projector-server 本地运行

* clone 项目

  * clone [projector-server](https://github.com/JetBrains/projector-server) 项目
  * clone [projector-demo](https://github.com/JetBrains/projector-demo) 项目

* 修改 projector-demo

  重命名 projector-demo 目录下 local.properties 文件
  ```
  mv local.properties.example local.properties
  ```
  local.properties 指定运行本地 projector-server
  ```
  projectorServerSource=local
  ```

* 运行 projector-demo

  可以通过 Select Run/Debug Configuration 选择运行：

  * (Headless) HeadlessSupportingMain
  * (UI) HeadlessSupportingMain

