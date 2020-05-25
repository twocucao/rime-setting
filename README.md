# Rime 输入法配置指南
  ## 用法
  1. 安装[Rime输入法](https://rime.im/),并注销或重启
  2. 下载仓库所有配置文件到本地
        3. 将下载的除字体外的所有文件覆盖到用户设定文件夹
       - Windows
         - Weasel: %APPDATA%\Rime
       - Mac OS X
         - Squirrel: ~/Library/Rime
       - Linux
         - iBus: ~/.config/ibus/rime
         - Fcitx: ~/.config/fcitx/rime
        4. 安装字体 ( font 目录)
        5. 也可以在“用户文件夹”中查看
        6. 右上角菜单栏点击鼠须管图标，点击重新部署，部署完毕即可用


  ## 配置文件说明
  - `default.custom.yaml` 设置输入法、如何切换输入法、翻页等
  - `double_pinyin_flypy.custom.yaml` 双拼方案，
  - `squirrel.custom.yaml` 鼠须管( Mac 版本 )设置哪些软件默认英文输入，输入法皮肤等
  - `custom_phrase.txt` 设置快捷输入，修改完成后要重新部署才能生效
    配置文件中大部分都有注释。

------

  ## 参考/致谢
  1. [Mac 下调校 Rime](https://mritd.me/2019/03/23/oh-my-rime/)
  2. [鼠须管 0.11 Mac 升级重装配置 2019](https://github.com/cnfeat/Rime)
  3. [鼠须管配置 2019](https://placeless.net/blog/rime-squirrel-customization-2019#article)

  
