#### Contribution Guidelines for Windows

Any contribution to the repository is always welcome and grateful. If you expect better experience, please go through contents below:

(Remember these are always **SUGGESTIONS**)

* Create an issue for new app request:
    1. Please confirm that the app meets requirements from [README](https://github.com/AmazingApps/Amazing-Windows-Apps/blob/master/README.md)
    2. Provide suggested category & link to official site
    3. A piece of brief and conclusive description is recommended
    4. More information is also recommended: whether the app is free, open sourced, portable, localized or not, operated by GUI or CLI, available from Windows store,etc.

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
                * Please [contact owner](https://t.me/Engorgio) if a new logo is required for UI language in a specific app
                * Arrange the logos in such order: free→open source→supported languages→portable→multi-platform→CLI→Windows store
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
        * **stop by this step if you don't know how to implement this**
