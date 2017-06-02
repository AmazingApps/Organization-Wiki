## Contribution Guidelines for Windows｜Windows 贡献指引

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
 
** 如果您不了解 Markdown 语法格式，请勿创建 pull request，请新建一个 issue**

* 当您创建一个添加新应用的 pull request 时：
    1. 请确认该应用符合 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 当中的条件
    2. 请标注相关信息：
        * 请用第三级标题写应用名并在应用名处附带官网链接，随后请根据具体信息添加标识 logo
            * 如果位于官网主页的下载按钮指向一个二级站点，且安装包 URL 位于该站点，请使用第六级标题在第二行分开标注官网与下载页面（此时请勿在第一行的应用名处附带官网链接）
            * 标识 logo 位于 `assets` 目录下，使用相对路径表示，并且要求带文件后缀名
                * 如果因应用特定界面语言而需要新 logo 的请 [联系 owner](https://t.me/EMLVIRUS)
                * 标识 logo 请按照顺序排列：免费→开源→支持的语种→便携→跨平台→命令行操作
                * 若该应用开源，请使用图片的 titile 属性注明开源协议、托管站点与开源地址，title 格式为：开源协议 @托管站点: 开源地址
       * 使用概括性语言描述应用功能：对于一个 awesome list 而言，** 完整简洁的概括 ** 至关重要
    3. 如果该应用创建人具有中国国籍（包含港澳台地区），除非创建人另有要求，请复制到 [国产应用目录](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/china-apps.md) 中
    4. 如果该应用存在以下情况，请在应用描述后另转一行添加额外描述：
        1. 联网下载或捆绑其它软件安装包，但目标软件具有完善卸载功能且无害、无明显恶意行为的
        2. （仍在维护但）长期未更新且无明显 bug 的；若不清楚该应用是否仍被维护，请使用删除线表示。
        3. 除 C++、.Net framework 等之外需要其它额外运行库的，如 Java
    5. 在 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 的计数 badge 处 + 1，并在 [acknowledgement](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/acknowledgement.md) 处添加您的信息
        * ** 如果您不清楚具体实现方式，请到此为止 **

* 当您创建一个移除应用的 pull request 时：
    1. 如果该应用符合 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 当中的争议条件，请添加删除线并移除官网链接
    2. 如果该应用符合 [黑名单](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/blacklist.md) 的条件，请将其在分类中删除，添加到黑名单，并添加符合的拉黑标准
    3. 在 [README](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/README.md) 的计数 badge 处 - 1，并在 [acknowledgement](https://github.com/EMLVIRUS/Amazing-Windows-Apps/blob/master/acknowledgement.md) 处添加您的信息
        * ** 如果您不清楚具体实现方式，请到此为止 **

如果您有其它疑问，请 [联系 owner](https://t.me/EMLVIRUS)
---

Any contribution to the repository is always welcome and grateful. If you expect better experience, please go through contents below:

(Remember these are always **SUGGESTIONS**)

* Create an issue for new app request:
    1. Please confirm that the app meets requirements from [README](https://github.com/AmazingApps/Amazing-Windows-Apps/blob/master/README.md)
    2. Provide suggested category & link to official site
    3. A piece of brief and conclusive description is recommended
    4. More information is also recommended: whether the app is free, open sourced, portable, localized or not, operated by GUI or CLI.

* Create an issue to remove an existing app:
    1. Please point out which condition in [README](https://github.com/AmazingApps/Amazing-Windows-Apps/blob/master/README.md) is satisfied.
        * standards in [blacklist](https://github.com/AmazingApps/Amazing-Windows-Apps/blob/master/blacklist.md) will be equivalently considered. In that case, it will be also blacklisted.
    2. Other behaviors such as severe violation of industry principle will be also considered

>**If you are not familiar with Markdown, please create an issue instead of a pull request**

* Create a pull request for adding new app:
    1. Please confirm that the app meets requirement from [README](https://github.com/AmazingApps/Amazing-Windows-Apps/blob/master/README.md)
    2. Commit with following information:
        * Please use h3 to write the app name with link to official site, with icons followed
            * If download page is different from homepage, write down official home & download page separately with h6 in another line (in which case, do not attach official link in the same line with the app name).
            * Icons are under `assets` folder. Use with relevant path with extension names.
                * Please [contact owner](https://t.me/EMLVIRUS) if a new logo is required for UI language in a specific app
                * Arrange the logos in such order: free→open source→supported languages→portable→multi-platform→CLI
                * If this app is open source, set the title property of the image to: `license@host site: open source address`
        * Descibe the app in short: **complete & brief conclusion** is really critical to an awesome list
    3. if the app creator's nationality is Chinese (including Hong Kong, Macow & Taiwan), please copy it to [china's app.md](https://github.com/AmazingApps/Amazing-Windows-Apps/blob/master/china-apps.md) unless the creator asked you not to
    4. Please add extra desciption in another line if the app: 
        1. downloads or bundles other harmless apps
        2. (is still maintained but) do not receive update for a long time and there are no known bugs; strike it through if it is unclear whether it is still being maintained.
        3. requires other libraries than C++ Runtime, .Net framework, such as Java
    5. Add 1 to the badge in [README](https://github.com/AmazingApps/Amazing-Windows-Apps/blob/master/README.md) and add your information to [acknowledgement](https://github.com/AmazingApps/Amazing-Windows-Apps/blob/master/acknowledgement.md)
        * **stop by this step if you don't know how to implement this**

* Create a pull request to remove an existing app:
    1. if it is controversial as described in [README](https://github.com/AmazingApps/Amazing-Windows-Apps/blob/master/README.md), remove official link and strike it through
    2. if it should be included in the [blacklist](https://github.com/AmazingApps/Amazing-Windows-Apps/blob/master/blacklist.md), delete it category, add it to black list with the condition number
    3. Substract 1 from the badge in [README](https://github.com/AmazingApps/Amazing-Windows-Apps/blob/master/README.md) and add your info to [acknowledgement](https://github.com/AmazingApps/Amazing-Windows-Apps/blob/master/acknowledgement.md)
        * **stop by this step if you don't know how detailedly**

If any other questions, please [contact owner](https://t.me/EMLVIRUS)
