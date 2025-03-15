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
    "comment": {"prefix": "c", "body": ["⫽ ",],},
    "𝗮": {"prefix": "aa", "body": ["𝗮",],},
    "𝗯": {"prefix": "bb", "body": ["𝗯",],},
    "𝗰": {"prefix": "cc", "body": ["𝗰",],},
    "𝗱": {"prefix": "dd", "body": ["𝗱",],},
    "𝗲": {"prefix": "ee", "body": ["𝗲",],},
    "𝗳": {"prefix": "ff", "body": ["𝗳",],},
    "𝗴": {"prefix": "gg", "body": ["𝗴",],},
    "𝗵": {"prefix": "hh", "body": ["𝗵",],},
    "𝗶": {"prefix": "ii", "body": ["𝗶",],},
    "𝗷": {"prefix": "jj", "body": ["𝗷",],},
    "𝗸": {"prefix": "kk", "body": ["𝗸",],},
    "𝗹": {"prefix": "ll", "body": ["𝗹",],},
    "𝗺": {"prefix": "mm", "body": ["𝗺",],},
    "𝗻": {"prefix": "nn", "body": ["𝗻",],},
    "𝗼": {"prefix": "oo", "body": ["𝗼",],},
    "𝗽": {"prefix": "pp", "body": ["𝗽",],},
    "𝗾": {"prefix": "qq", "body": ["𝗾",],},
    "𝗿": {"prefix": "rr", "body": ["𝗿",],},
    "𝘀": {"prefix": "ss", "body": ["𝘀",],},
    "𝘁": {"prefix": "tt", "body": ["𝘁",],},
    "𝘂": {"prefix": "uu", "body": ["𝘂",],},
    "𝘃": {"prefix": "vv", "body": ["𝘃",],},
    "𝘄": {"prefix": "ww", "body": ["𝘄",],},
    "𝘅": {"prefix": "xx", "body": ["𝘅",],},
    "𝘆": {"prefix": "yy", "body": ["𝘆",],},
    "𝘇": {"prefix": "zz", "body": ["𝘇",],},
    "𝗔": {"prefix": "aaa", "body": ["𝗔",],},
    "𝗕": {"prefix": "bbb", "body": ["𝗕",],},
    "𝗖": {"prefix": "ccc", "body": ["𝗖",],},
    "𝗗": {"prefix": "ddd", "body": ["𝗗",],},
    "𝗘": {"prefix": "eee", "body": ["𝗘",],},
    "𝗙": {"prefix": "fff", "body": ["𝗙",],},
    "𝗚": {"prefix": "ggg", "body": ["𝗚",],},
    "𝗛": {"prefix": "hhh", "body": ["𝗛",],},
    "𝗜": {"prefix": "iii", "body": ["𝗜",],},
    "𝗝": {"prefix": "jjj", "body": ["𝗝",],},
    "𝗞": {"prefix": "kkk", "body": ["𝗞",],},
    "𝗟": {"prefix": "lll", "body": ["𝗟",],},
    "𝗠": {"prefix": "mmm", "body": ["𝗠",],},
    "𝗡": {"prefix": "nnn", "body": ["𝗡",],},
    "𝗢": {"prefix": "ooo", "body": ["𝗢",],},
    "𝗣": {"prefix": "ppp", "body": ["𝗣",],},
    "𝗤": {"prefix": "qqq", "body": ["𝗤",],},
    "𝗥": {"prefix": "rrr", "body": ["𝗥",],},
    "𝗦": {"prefix": "sss", "body": ["𝗦",],},
    "𝗧": {"prefix": "ttt", "body": ["𝗧",],},
    "𝗨": {"prefix": "uuu", "body": ["𝗨",],},
    "𝗩": {"prefix": "vvv", "body": ["𝗩",],},
    "𝗪": {"prefix": "www", "body": ["𝗪",],},
    "𝗫": {"prefix": "xxx", "body": ["𝗫",],},
    "𝗬": {"prefix": "yyy", "body": ["𝗬",],},
    "𝗭": {"prefix": "zzz", "body": ["𝗭",],},
    "to-do item": {"prefix": "td", "body": ["☑",],}
}

### Thanks for reading even though you might find no use of this extension XD