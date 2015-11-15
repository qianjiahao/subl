# subl
Fix Sublime Text 3 quickly open files command for Mac


👿打开.bash_profile文件 (如果安装了zsh，就打开.zshrc)
    
    nano ~/.bash_profile  (~/.zshrc)
    
😠添加如下内容

    # For Sublime Text
    alias subl=\"/Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl\"
    
☺️编译文件

    source ~/.bash_profile  (~/.zshrc)
    
😃打完收工！


备注: Sublime Text版本根据自己的版本配置(2/3) , 或者可以直接获取subl文件的路径替换上面的内容
