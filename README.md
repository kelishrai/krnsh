# KRNSH

### I doubt anyone will find this extension useful besides me. Still, here's the install process:

1. Download KRNSH and rename it to "krnsh"
2. Add krnsh in "C:\Users\userX\.vscode\extensions"
3. Finally, in VS Code, open settings.json and add following JSON
    "files.associations": {
        "*.txt": "krnsh",
    },
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "krnsh.headings",
                "settings": {
                    "foreground": "#aaaa00",
                }
            },
            {
                "scope": "krnsh.comments",
                "settings": {
                    "foreground": "#6a9955",
                }
            },
            {
                "scope": "krnsh.abbreviations",
                "settings": {
                    "foreground": "#4ec9b0",
                }
            },
            {
                "scope": "krnsh.conjunctions",
                "settings": {
                    "foreground": "#c586c0",
                }
            },
            {
                "scope": "krnsh.links",
                "settings": {
                    "foreground": "#007bff",
                }
            },
            {
                "scope": "krnsh.symbols-1",
                "settings": {
                    "foreground": "#c87b3c",
                }
            },
            {
                "scope": "krnsh.symbols-2",
                "settings": {
                    "foreground": "#569cd6",
                }
            },
            {
                "scope": "krnsh.file-name",
                "settings": {
                    "foreground": "#b5cea8",
                    "fontStyle": "underline",
                }
            },
            {
                "scope": "krnsh.new-line-continuation",
                "settings": {
                    "foreground": "#f9f26c",
                }
            },
            {
                "scope": "krnsh.checklist-done",
                "settings": {
                    "foreground": "#3da753",
                    "fontStyle": "strikethrough",
                }
            }
        ]
    },

### Thanks for reading even though you might find no use of this extension XD