# KRNSH

## install process

1. download KRNSH and add it in "C:\Users\user-x\.vscode\extensions"
2. in VS Code, "File" > "Preferences" > "Settings" > "Edit in settings.json", add following syntax:
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "krnsh.comments",
                "settings": {
                    "foreground": "#6A9955",
                }
            },
            {
                "scope": "krnsh.abbreviations",
                "settings": {
                    "foreground": "#4EC9B0",
                }
            },
            {
                "scope": "krnsh.links",
                "settings": {
                    "foreground": "#007bff",
                }
            },
            {
                "scope": "krnsh.comma",
                "settings": {
                    "foreground": "#C586C0",
                }
            },
            {
                "scope": "krnsh.period",
                "settings": {
                    "foreground": "#CE9178",
                }
            },
            {
                "scope": "krnsh.symbols",
                "settings": {
                    "foreground": "#569CD6",
                }
            }
        ]
    },
    "files.associations": {
        "*.txt": "krnsh",
    },
3. rename KRNSH to krnsh

That's all!
