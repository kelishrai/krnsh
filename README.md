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
                "scope": "krnsh.highlight",
                "settings": {
                    "fontStyle": "bold"
                }
            },
            {
                "scope": "krnsh.highlight.invisible",
                "settings": {
                    "foreground": "#ffffff00",
                }
            },
            {
                "scope": "krnsh.english",
                "settings": {
                    "foreground": "#9686c5",
                }
            },
            {
                "scope": "krnsh.explanation",
                "settings": {
                    "foreground": "#6a9955",
                }
            },
            {
                "scope": "krnsh.file-name",
                "settings": {
                    "foreground": "#dfbe5b",
                    "fontStyle": "underline",
                }
            },
            {
                "scope": "krnsh.heading",
                "settings": {
                    "foreground": "#c586c0",
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
                "scope": "krnsh.representation",
                "settings": {
                    "foreground": "#4ec9b0",
                }
            },
            {
                "scope": "krnsh.section-heading",
                "settings": {
                    "foreground": "#cf7094",
                }
            },
            {
                "scope": "krnsh.symbol",
                "settings": {
                    "foreground": "#c87b3c",
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
    "╱": {"prefix": "c", "body": ["╱ $0",],},
    "│": {"prefix": "h", "body": ["│ $0",],},
    "❘": {"prefix": "s", "body": ["❘ $0",],},
    "〈〉": {"prefix": "v", "body": ["〈$1〉$0",]},
    "⟮⟯": {"prefix": "b", "body": ["⟮$1⟯$0",],},
    "⸻": {"prefix": "hr", "body": ["⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻","$0"],},
    "→": {"prefix": "arrow", "body": ["→ $0",],},

    "ⓘ": {"prefix": "nt", "body": ["ⓘ$0",]},
    "☀": {"prefix": "ti", "body": ["☀$0",]},
    "✓": {"prefix": "rt", "body": ["✓$0",]},
    "✗": {"prefix": "wg", "body": ["✗$0",]},
    "⚙": {"prefix": "se", "body": ["⚙$0",]},
    "⥣": {"prefix": "ad", "body": ["⥣$0",]},
    "⥥": {"prefix": "di", "body": ["⥥$0",]},
    "⧉": {"prefix": "me", "body": ["⧉$0",]},
    "ƒ": {"prefix": "fo", "body": ["ƒ$0",]},
    "⇄": {"prefix": "pr", "body": ["⇄$0",]},
    "⚛": {"prefix": "st", "body": ["⚛$0",]},
    "≫": {"prefix": "cl", "body": ["≫$0",]},
    "⋙": {"prefix": "acl", "body": ["⋙$0",]},
    "◉": {"prefix": "eg", "body": ["◉$0",]},
    "≣": {"prefix": "li", "body": ["≣$0",]},
    "⚒": {"prefix": "ps", "body": ["⚒$0",]},
    "☑": {"prefix": "td", "body": ["☑$0",]},
    "‴": {"prefix": "sn", "body": ["‴$0",]},
    "◨": {"prefix": "vs", "body": ["◨$0",]},
    "⍦": {"prefix": "ty", "body": ["⍦$0",]},
    "↳": {"prefix": "ou", "body": ["↳$0",]},
    "⚠": {"prefix": "er", "body": ["⚠$0",]},
    "⌘": {"prefix": "sh", "body": ["⌘$0",]},
    "⛶": {"prefix": "fg", "body": ["⛶$0",]},
}

### Thanks for reading even though you might find no use of this extension XD
