在store安装Windows Terminal

命令：

`Install-Module posh-git -Scope CurrentUser`
`Install-Module oh-my-posh -Scope CurrentUser`



字体颜色：#f57c00



<img src="https://gitee.com/la-vono/Markdown/raw/master/img/202202271752149.png" alt="image-20220227175242047" style="zoom: 67%;" />



```
{
    "$schema": "https://aka.ms/terminal-profiles-schema",
    "defaultProfile": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
    "copyOnSelect": false,
    "copyFormatting": false,
    "profiles":
    {
        "defaults":
        {
          "fontFace": "Consolas", // oh-my-posh 
          "backgroundImage": "C:\\Users\\T-04\\pics\\qlz.jpg", 
          "backgroundImageOpacity": 0.5, 
          "colorScheme" : "Campbell", 
          "acrylicOpacity": 0.7,
          "useAcrylic":true
        },
        "list":
        [
            {
                // Make changes here to the powershell.exe profile.
                "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
                "name": "powershell",
                "commandline": "powershell.exe",
                "hidden": false
            },
            {
                // Make changes here to the cmd.exe profile.
                "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
                "name": "cmd",
                "commandline": "cmd.exe",
                "hidden": false
            },
            {
                "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
                "name": "Azure Cloud Shell",
                "source": "Windows.Terminal.Azure"
            }
        ]
    },
 "schemes": [
        {
    "name" : "Campbell",
    "cursorColor": "#FFFFFF",
    "selectionBackground": "#FFFFFF",
    "background" : "#0C0C0C",
    "foreground" : "#CCCCCC",
    "black" : "#0C0C0C",
    "blue" : "#0037DA",
    "cyan" : "#3A96DD",
    "green" : "#13A10E",
    "purple" : "#881798",
    "red" : "#C50F1F",
    "white" : "#CCCCCC",
    "yellow" : "#C19C00",
    "brightBlack" : "#767676",
    "brightBlue" : "#3B78FF",
    "brightCyan" : "#61D6D6",
    "brightGreen" : "#16C60C",
    "brightPurple" : "#B4009E",
    "brightRed" : "#E74856",
    "brightWhite" : "#F2F2F2",
    "brightYellow" : "#F9F1A5"
      	}
    ],
    "actions":
    [
        { "command": {"action": "copy", "singleLine": false }, "keys": "ctrl+c" },
        { "command": "paste", "keys": "ctrl+v" },
        { "command": "find", "keys": "ctrl+shift+f" },
        { "command": { "action": "splitPane", "split": "auto", "splitMode": "duplicate" }, "keys": "alt+shift+d" }
    ]
}


```



