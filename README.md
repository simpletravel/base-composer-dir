# php composer 包 封装的基本目录结构
```
/base-composer-dir
├── .editorconfig      编辑器配置文件，比如缩进大小、换行模式等,用于统一代码格式 [EditorConfig](https://editorconfig.org/)
├── .gitattributes     git 配置文件，可以设计导出时忽略文件等  Git 的属性配置文件
├── .gitignore         git 忽略文件配置列表
├── .php_cs            PHP-CS-Fixer 配置文件
├── README.md          项目说明文档，一份项目介绍与使用指引，维护状态授权方式等。
├── composer.json      composer配置文件
├── phpunit.xml.dist   PHPUnit 单元测试 配置文件
├── src                源代码存放到此目录
│   └── .gitkeep       空目录无法纳入到版本控制中,添加.gitkeep隐藏文件来保证目录不为空
└── tests              用于存放单元测试或者功能测试的测试用例代码
    └── .gitkeep
