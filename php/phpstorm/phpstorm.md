# PhpStorm常用配置

- .editorconfig 
    - 配置文件: 规范不同项目的缩进
    
- php-conding-style.xml 
    - PhpStorm导入该文件,导入方式：Code Style里Manage-import文件
    
- 文件目录颜色标注
    - Test (颜色为绿色) > 测试主目录，如 `Laravel` 的 `tests` 目录
    - Sources (颜色为蓝色) > 项目主代码目录，如 `Laravel` 的 `app` 目录
    - Excluded (颜色为红色) > 第三方扩展依赖(不会修改代码)，不建立索引，不由`phpstorm`管理，如 `Laravel` 的 `vendor` 目录
    - Resource Root (颜色为紫色) > 前端资源，如 `Laravel` 的 `public` 目录

- 配置项目debug
