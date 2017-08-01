#### Windows 贡献指引

首先，对于任何贡献表示欢迎和感谢。阅读以下内容将进一步帮助本项目变得更好：

（当然，如果您无法理解下列内容，您也不必在贡献时有所顾忌，这毕竟只是建议）

* 当您创建一个关于添加新应用的 issue 时：
    1. 请确认该应用符合 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 当中的条件
    2. 表明建议添加的分类并附注官网链接
    3. 建议给出简洁的、概括性的描述
    4. 建议给出尽可能多的额外信息，如是否免费、是否开源、是否便携、多语种支持（如果仅支持少数语种则建议表明具体语种）、是否使用命令行操作等

* 当您创建一个移除应用的 issue 时：
    1. 请给出针对于 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 中的条件的矛盾点
        * 如果给出符合 [黑名单](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/blacklist.md) 的条件，作用是等效的，此时还会考虑拉黑
     2. 其它违反行业基本守则的行为同样会被考虑
 
###### **如果您不了解 Markdown 语法格式，请勿创建 pull request，请新建一个 issue**

* 当您创建一个添加新应用的 pull request 时：
    1. 请确认该应用符合 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 当中的条件
    2. 请标注相关信息：
        * 请用第三级标题写应用名并在应用名处附带官网链接，随后请根据具体信息添加标识 logo
            * 如果位于官网主页的下载按钮指向一个二级站点，且安装包 URL 位于该站点，请使用第六级标题在第二行分开标注官网与下载页面（此时请勿在第一行的应用名处附带官网链接）
            * 标识 logo 位于 `assets` 目录下，使用相对路径表示，并且要求带文件后缀名
                * 如果因应用特定界面语言而需要新 logo 的请 [联系 owner](https://t.me/EMLVIRUS)
                * 标识 logo 请按照顺序排列：免费→开源→支持的语种→便携→跨平台→命令行操作
                * 若该应用开源，请使用图片的 title 属性注明开源协议、托管站点与开源地址，title 格式为：开源协议 @托管站点: 开源地址
       * 使用概括性语言描述应用功能：对于一个 awesome list 而言，** 完整简洁的概括 ** 至关重要
    3. 如果该应用创建人具有中国国籍（包含港澳台地区），除非创建人另有要求，请复制到 [国产应用目录](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/china-apps.md) 中
    4. 如果该应用存在以下情况，请在应用描述后另转一行添加额外描述：
        1. 联网下载或捆绑其它软件安装包，但目标软件具有完善卸载功能且无害、无明显恶意行为的
        2. （仍在维护但）长期未更新且无明显 bug 的；若不清楚该应用是否仍被维护，请使用删除线表示。
        3. 除 C++、.Net framework 等之外需要其它额外运行库的，如 Java
    5. 在 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 的计数 badge 处 + 1，并在 [acknowledgement](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/acknowledgement.md) 处添加您的信息
        * **如果您不清楚具体实现方式，请到此为止**

* 当您创建一个移除应用的 pull request 时：
    1. 如果该应用符合 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 当中的争议条件，请添加删除线并移除官网链接
    2. 如果该应用符合 [黑名单](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/blacklist.md) 的条件，请将其在分类中删除，添加到黑名单，并添加符合的拉黑标准
    3. 在 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 的计数 badge 处 - 1，并在 [acknowledgement](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/acknowledgement.md) 处添加您的信息
        * **如果您不清楚具体实现方式，请到此为止**
