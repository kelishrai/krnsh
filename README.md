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
                "scope": "krnsh.abbreviations",
                "settings": {
                    "foreground": "#4ec9b0",
                }
            },
            {
                "scope": "krnsh.symbols",
                "settings": {
                    "foreground": "#c87b3c",
                }
            },
            {
                "scope": "krnsh.english",
                "settings": {
                    "foreground": "#9686c5",
                }
            },
            {
                "scope": "krnsh.variables",
                "settings": {
                    "foreground": "#66a1c1",
                }
            },
            {
                "scope": "krnsh.variables.invisible",
                "settings": {
                    "foreground": "#66a1c100",
                }
            },
            {
                "scope": "krnsh.terms",
                "settings": {
                    "foreground": "#c586c0",
                }
            },
            {
                "scope": "krnsh.terms.invisible",
                "settings": {
                    "foreground": "#c586c000",
                }
            },
            {
                "scope": "krnsh.links",
                "settings": {
                    "foreground": "#007bff",
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
                "scope": "krnsh.checklist-done",
                "settings": {
                    "foreground": "#3da753",
                    "fontStyle": "strikethrough",
                }
            },
            {
                "scope": "krnsh.single-line-comments",
                "settings": {
                    "foreground": "#6a9955",
                }
            },
            {
                "scope": "krnsh.horizontal-rule",
                "settings": {
                    "foreground": "#414041",
                }
            },
        ]
    },
4. Additionally, create notes.code-snippets folder in .vscode and add following JSON
{
    "comment": {"prefix": "c", "body": ["⫽ $0",],},
    "heading": {"prefix": "h", "body": ["⟮$1⟯$0",],},
    "variables": {"prefix": "v", "body": ["〈$1〉$0",],},
    "to-do item": {"prefix": "td", "body": ["☑$0",],},
    "horizontal rule": {"prefix": "hr", "body": ["――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――――","$0"],},
}

### Thanks for reading even though you might find no use of this extension XD
