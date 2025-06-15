# KRNSH

### I doubt anyone will find this extension useful besides me. Still, here's the install process:

1. Download KRNSH and rename it to "krnsh"
2. Add krnsh in "C:\Users\‹user›\.vscode\extensions"
3. Finally, in VS Code, open settings.json and add following JSON
    "files.associations": {
        "*.txt": "krnsh"
    },
    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "krnsh.abbreviation",
                "settings": {
                    "foreground": "#4ec9b0",
                }
            },
            {
                "scope": "krnsh.bold",
                "settings": {
                    "fontStyle": "bold"
                }
            },
            {
                "scope": "krnsh.bold.invisible",
                "settings": {
                    "foreground": "#ffffff00",
                }
            },
            {
                "scope": "krnsh.comment",
                "settings": {
                    "foreground": "#6a9955",
                }
            },
            {
                "scope": "krnsh.english",
                "settings": {
                    "foreground": "#9686c5",
                }
            },
            {
                "scope": "krnsh.file-name",
                "settings": {
                    "foreground": "#007bff",
                    "fontStyle": "underline",
                }
            },
            {
                "scope": "krnsh.horizontal-rule",
                "settings": {
                    "foreground": "#414041",
                }
            },
            {
                "scope": "krnsh.link",
                "settings": {
                    "foreground": "#007bff",
                    "fontStyle": "underline",
                }
            },
            {
                "scope": "krnsh.list",
                "settings": {
                    "foreground": "#ff6e6e"
                }
            },
            {
                "scope": "krnsh.section-divider",
                "settings": {
                    "foreground": "#75cc9e",
                }
            },
            {
                "scope": "krnsh.symbol",
                "settings": {
                    "foreground": "#c87b3c",
                }
            },
            {
                "scope": "krnsh.term",
                "settings": {
                    "foreground": "#c586c0",
                }
            },
            {
                "scope": "krnsh.term.invisible",
                "settings": {
                    "foreground": "#c586c000",
                }
            },
            {
                "scope": "krnsh.to-do",
                "settings": {
                    "foreground": "#3da753",
                    "fontStyle": "strikethrough",
                }
            },
            {
                "scope": "krnsh.variable",
                "settings": {
                    "foreground": "#66a1c1",
                }
            },
            {
                "scope": "krnsh.variable.invisible",
                "settings": {
                    "foreground": "#66a1c100",
                }
            },
        ]
    },
4. Additionally, create notes.code-snippets folder in .vscode and add following JSON
{
    "╎": {"prefix": "comment", "body": ["╎ $0",],},
    "〈": {"prefix": "variable", "body": ["〈$1〉$0",],},
    "⟮": {"prefix": "term", "body": ["⟮$1⟯$0",],},
    "⫽": {"prefix": "section divider", "body": ["⫽ $0",],},
    "⸻": {"prefix": "horizontal rule", "body": ["⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻","$0"],},
    "☑": {"prefix": "to-do", "body": ["☑$0",],},
    "→": {"prefix": "arrow", "body": ["→",],},
}

### Thanks for reading even though you might find no use of this extension XD
