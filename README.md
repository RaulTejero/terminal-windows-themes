# terminal-windows
## Json 
- Tema: Andromeda.
- Integaciones añadidas:
    - Ubuntu
    - Git bash
- Comandos:
    - ctrl+f: busqueda;
    - ctrl+c: copy;
    - ctrl+v: paste;
    - alt+shift+d: nueva pestaña;

<pre>
// This file was initially generated by Windows Terminal 1.3.2651.0
// It should still be usable in newer versions, but newer versions might have additional
// settings, help text, or changes that you will not see unless you clear this file
// and let us generate a new one for you.
// To view the default settings, hold "alt" while clicking on the "Settings" button.
// For documentation on these settings, see: https://aka.ms/terminal-documentation
{
    "$schema": "https://aka.ms/terminal-profiles-schema",
    "defaultProfile": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
    // You can add more global application settings here.
    // To learn more about global settings, visit https://aka.ms/terminal-global-settings
    // If enabled, selections are automatically copied to your clipboard.
    "copyOnSelect": false,
    // If enabled, formatted data is also copied to your clipboard
    "copyFormatting": false,
    // A profile specifies a command to execute paired with information about how it should look and feel.
    // Each one of them will appear in the 'New Tab' dropdown,
    //   and can be invoked from the commandline with `wt.exe -p xxx`
    // To learn more about profiles, visit https://aka.ms/terminal-profile-settings
    "profiles": {
        "defaults": {
            // Put settings here that you want to apply to all profiles.
        },
        "list": [
            {
                // Make changes here to the cmd.exe profile.
                "commandline": "cmd.exe",
                "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
                "name": "cmd",
                "colorScheme": "raul tejero noche",
                "hidden": false,
                "fontFace": "Ubuntu Mono derivative Powerline",
                "fontSize": 10,
                "experimental.retroTerminalEffect": false,
                "cursorShape": "emptyBox",
                "cursorColor": "#438ff9",
                "padding": "30,30,30,30",
                "antialiasingMode": "aliased"
            },
            {
                "name": "GitBash",
                "guid": "{00000000-0000-0000-0000-000000000001}",
                "commandline": "\"%PROGRAMFILES%\\Git\\usr\\bin\\bash.exe\" --login -i -l",
                "suppressApplicationTitle": true,
                "colorScheme": "Andromeda",
                "acrylicOpacity": 0.9,
                "closeOnExit": true,
                "cursorColor": "#438ff9",
                "fontFace": "Ubuntu Mono derivative Powerline",
                "fontSize": 10,
                "historySize": 9001,
                "icon": "%PROGRAMFILES%\\Git\\mingw64\\share\\git\\git-for-windows.ico",
                "snapOnInput": true,
                "startingDirectory": "%USERPROFILE%",
                "useAcrylic": true,
                "padding": "30,30,30,30",
                "antialiasingMode": "aliased",
                "cursorShape": "emptyBox"
            },
            {
                "source": "Windows.Terminal.Wsl",
                "colorScheme": "Andromeda",
                "guid": "{2c4de342-38b7-51cf-b940-2309a097f518}",
                "name": "Ubuntu",
                "suppressApplicationTitle": true,
                "hidden": false,
                "cursorShape": "emptyBox",
                "cursorColor": "#438ff9",
                "acrylicOpacity": 0.9,
                "fontSize": 10,
                "useAcrylic": true,
                "padding": "30,30,30,30",
                "fontFace": "Ubuntu Mono derivative Powerline",
                "antialiasingMode": "aliased"
            },
            {
                // Make changes here to the powershell.exe profile.
                "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
                "name": "Windows PowerShell",
                "commandline": "powershell.exe",
                "hidden": false
            },
            {
                "source": "Windows.Terminal.Azure",
                "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
                "name": "Azure Cloud Shell",
                "hidden": false
            }
        ]
    },
    // Add custom color schemes to this array.
    // To learn more about color schemes, visit https://aka.ms/terminal-color-schemes
    "schemes": [
        {
            "name": "GitBash",
            "black": "#002831",
            "red": "#f40a0a",
            "green": "#6cbe6c",
            "yellow": "#d2ea12",
            "blue": "#5a5dff",
            "purple": "#c61c6f",
            "cyan": "#259286",
            "white": "#ea9412",
            "brightBlack": "#006488",
            "brightRed": "#f5163b",
            "brightGreen": "#24d21e",
            "brightYellow": "#a8b53c",
            "brightBlue": "#345ef6",
            "brightPurple": "#e24d8e",
            "brightCyan": "#00b39e",
            "brightWhite": "#5fc5f6",
            "background": "#000000",
            "foreground": "#b3b3b3"
        },
        {
            "name": "raul tejero noche",
            "black": "#002831",
            "red": "#f40a0a",
            "green": "#6cbe6c",
            "yellow": "#d2ea12",
            "blue": "#5a5dff",
            "purple": "#c61c6f",
            "cyan": "#259286",
            "white": "#ea9412",
            "brightBlack": "#006488",
            "brightRed": "#f5163b",
            "brightGreen": "#24d21e",
            "brightYellow": "#e1d922",
            "brightBlue": "#345ef6",
            "brightPurple": "#e24d8e",
            "brightCyan": "#00b39e",
            "brightWhite": "#5fc5f6",
            "background": "#262a33",
            "foreground": "#adadad"
        },
        {
            "name": "Andromeda",
            "black": "#000000",
            "red": "#cd3131",
            "green": "#05bc79",
            "yellow": "#e5e512",
            "blue": "#2472c8",
            "purple": "#bc3fbc",
            "cyan": "#0fa8cd",
            "white": "#e5e5e5",
            "brightBlack": "#666666",
            "brightRed": "#cd3131",
            "brightGreen": "#05bc79",
            "brightYellow": "#e5e512",
            "brightBlue": "#2472c8",
            "brightPurple": "#bc3fbc",
            "brightCyan": "#0fa8cd",
            "brightWhite": "#e5e5e5",
            "background": "#262a33",
            "foreground": "#aaaaaa"
        },
        {
            "name": "Harper",
            "black": "#010101",
            "red": "#f8b63f",
            "green": "#7fb5e1",
            "yellow": "#d6da25",
            "blue": "#489e48",
            "purple": "#b296c6",
            "cyan": "#f5bfd7",
            "white": "#a8a49d",
            "brightBlack": "#726e6a",
            "brightRed": "#f8b63f",
            "brightGreen": "#7fb5e1",
            "brightYellow": "#d6da25",
            "brightBlue": "#489e48",
            "brightPurple": "#b296c6",
            "brightCyan": "#f5bfd7",
            "brightWhite": "#fefbea",
            "background": "#010101",
            "foreground": "#a8a49d"
        }
    ],
    // Add custom actions and keybindings to this array.
    // To unbind a key combination from your defaults.json, set the command to "unbound".
    // To learn more about actions and keybindings, visit https://aka.ms/terminal-keybindings
    "actions": [
        // Copy and paste are bound to Ctrl+Shift+C and Ctrl+Shift+V in your defaults.json.
        // These two lines additionally bind them to Ctrl+C and Ctrl+V.
        // To learn more about selection, visit https://aka.ms/terminal-selection
        {
            "command": {
                "action": "copy",
                "singleLine": false
            },
            "keys": "ctrl+c"
        },
        {
            "command": "paste",
            "keys": "ctrl+v"
        },
        // Press Ctrl+Shift+F to open the search box
        {
            "command": "find",
            "keys": "ctrl+f"
        },
        // Press Alt+Shift+D to open a new pane.
        // - "split": "auto" makes this pane open in the direction that provides the most surface area.
        // - "splitMode": "duplicate" makes the new pane use the focused pane's profile.
        // To learn more about panes, visit https://aka.ms/terminal-panes
        {
            "command": {
                "action": "splitPane",
                "split": "auto",
                "splitMode": "duplicate"
            },
            "keys": "alt+shift+d"
        }
    ]
}
</pre>
