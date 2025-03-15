# KRNSH

### I doubt anyone will find this extension useful besides me. Still, here's the install process:

1. Download KRNSH and rename it to "krnsh"
2. Add krnsh in "C:\Users\userX\.vscode\extensions"
3. Finally, in VS Code, open settings.json and add following JSON
    "files.associations": {
        "*.txt": "krnsh"
    },
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "krnsh.abbreviations",
                "settings": {
                    "foreground": "#4ec9b0",
                    "fontStyle": "bold"
                }
            },
            {
                "scope": "krnsh.symbols",
                "settings": {
                    "foreground": "#c87b3c"
                }
            },
            {
                "scope": "krnsh.digits",
                "settings": {
                    "fontStyle": "italic"
                }
            },
            {
                "scope": "krnsh.variables",
                "settings": {
                    "foreground": "#7db7d7"
                }
            },
            {
                "scope": "krnsh.new-variables",
                "settings": {
                    "foreground": "#7db7d7"
                }
            },
            {
                "scope": "krnsh.links",
                "settings": {
                    "foreground": "#007bff"
                }
            },
            {
                "scope": "krnsh.file-name",
                "settings": {
                    "foreground": "#b5cea8",
                    "fontStyle": "underline"
                }
            },
            {
                "scope": "krnsh.checklist-done",
                "settings": {
                    "foreground": "#3da753",
                    "fontStyle": "strikethrough"
                }
            },
            {
                "scope": "krnsh.single-line-comments",
                "settings": {
                    "foreground": "#6a9955"
                }
            }
        ]
    },
4. Additionally, create notes.code-snippets folder in .vscode and add following JSON
{
    "comment": {
        "prefix": "c",
        "body": [
            "⫽ $1",
        ],
    },
    "variable": {
        "prefix": "v",
        "body": [
            "⟨$1⟩",
        ],
    },
    "to-do item": {
        "prefix": "td",
        "body": [
            "☑$1",
        ],
    }
}

### Thanks for reading even though you might find no use of this extension XD