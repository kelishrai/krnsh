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
                    "foreground": "#4ec9b0"
                }
            },
            {
                "scope": "krnsh.symbols",
                "settings": {
                    "foreground": "#c87b3c"
                }
            },
            {
                "scope": "krnsh.english",
                "settings": {
                    "foreground": "#c586c0"
                }
            },
            {
                "scope": "krnsh.variables",
                "settings": {
                    "foreground": "#66a1c1"
                }
            },
            {
                "scope": "krnsh.terms",
                "settings": {
                    "foreground": "#c87b3c"
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
    "to-do item": {"prefix": "td", "body": ["☑",],},

    "𝗮": {"prefix": "$a", "body": ["𝗮",],},
    "𝗯": {"prefix": "$b", "body": ["𝗯",],},
    "𝗰": {"prefix": "$c", "body": ["𝗰",],},
    "𝗱": {"prefix": "$d", "body": ["𝗱",],},
    "𝗲": {"prefix": "$e", "body": ["𝗲",],},
    "𝗳": {"prefix": "$f", "body": ["𝗳",],},
    "𝗴": {"prefix": "$g", "body": ["𝗴",],},
    "𝗵": {"prefix": "$h", "body": ["𝗵",],},
    "𝗶": {"prefix": "$i", "body": ["𝗶",],},
    "𝗷": {"prefix": "$j", "body": ["𝗷",],},
    "𝗸": {"prefix": "$k", "body": ["𝗸",],},
    "𝗹": {"prefix": "$l", "body": ["𝗹",],},
    "𝗺": {"prefix": "$m", "body": ["𝗺",],},
    "𝗻": {"prefix": "$n", "body": ["𝗻",],},
    "𝗼": {"prefix": "$o", "body": ["𝗼",],},
    "𝗽": {"prefix": "$p", "body": ["𝗽",],},
    "𝗾": {"prefix": "$q", "body": ["𝗾",],},
    "𝗿": {"prefix": "$r", "body": ["𝗿",],},
    "𝘀": {"prefix": "$s", "body": ["𝘀",],},
    "𝘁": {"prefix": "$t", "body": ["𝘁",],},
    "𝘂": {"prefix": "$u", "body": ["𝘂",],},
    "𝘃": {"prefix": "$v", "body": ["𝘃",],},
    "𝘄": {"prefix": "$w", "body": ["𝘄",],},
    "𝘅": {"prefix": "$x", "body": ["𝘅",],},
    "𝘆": {"prefix": "$y", "body": ["𝘆",],},
    "𝘇": {"prefix": "$z", "body": ["𝘇",],},
    "𝗔": {"prefix": "$aa", "body": ["𝗔",],},
    "𝗕": {"prefix": "$bb", "body": ["𝗕",],},
    "𝗖": {"prefix": "$cc", "body": ["𝗖",],},
    "𝗗": {"prefix": "$dd", "body": ["𝗗",],},
    "𝗘": {"prefix": "$ee", "body": ["𝗘",],},
    "𝗙": {"prefix": "$ff", "body": ["𝗙",],},
    "𝗚": {"prefix": "$gg", "body": ["𝗚",],},
    "𝗛": {"prefix": "$hh", "body": ["𝗛",],},
    "𝗜": {"prefix": "$ii", "body": ["𝗜",],},
    "𝗝": {"prefix": "$jj", "body": ["𝗝",],},
    "𝗞": {"prefix": "$kk", "body": ["𝗞",],},
    "𝗟": {"prefix": "$ll", "body": ["𝗟",],},
    "𝗠": {"prefix": "$mm", "body": ["𝗠",],},
    "𝗡": {"prefix": "$nn", "body": ["𝗡",],},
    "𝗢": {"prefix": "$oo", "body": ["𝗢",],},
    "𝗣": {"prefix": "$pp", "body": ["𝗣",],},
    "𝗤": {"prefix": "$qq", "body": ["𝗤",],},
    "𝗥": {"prefix": "$rr", "body": ["𝗥",],},
    "𝗦": {"prefix": "$ss", "body": ["𝗦",],},
    "𝗧": {"prefix": "$tt", "body": ["𝗧",],},
    "𝗨": {"prefix": "$uu", "body": ["𝗨",],},
    "𝗩": {"prefix": "$vv", "body": ["𝗩",],},
    "𝗪": {"prefix": "$ww", "body": ["𝗪",],},
    "𝗫": {"prefix": "$xx", "body": ["𝗫",],},
    "𝗬": {"prefix": "$yy", "body": ["𝗬",],},
    "𝗭": {"prefix": "$zz", "body": ["𝗭",],},

    "𝚊": {"prefix": "#a", "body": ["𝚊",],},
    "𝚋": {"prefix": "#b", "body": ["𝚋",],},
    "𝚌": {"prefix": "#c", "body": ["𝚌",],},
    "𝚍": {"prefix": "#d", "body": ["𝚍",],},
    "𝚎": {"prefix": "#e", "body": ["𝚎",],},
    "𝚏": {"prefix": "#f", "body": ["𝚏",],},
    "𝚐": {"prefix": "#g", "body": ["𝚐",],},
    "𝚑": {"prefix": "#h", "body": ["𝚑",],},
    "𝚒": {"prefix": "#i", "body": ["𝚒",],},
    "𝚓": {"prefix": "#j", "body": ["𝚓",],},
    "𝚔": {"prefix": "#k", "body": ["𝚔",],},
    "𝚕": {"prefix": "#l", "body": ["𝚕",],},
    "𝚖": {"prefix": "#m", "body": ["𝚖",],},
    "𝚗": {"prefix": "#n", "body": ["𝚗",],},
    "𝚘": {"prefix": "#o", "body": ["𝚘",],},
    "𝚙": {"prefix": "#p", "body": ["𝚙",],},
    "𝚚": {"prefix": "#q", "body": ["𝚚",],},
    "𝚛": {"prefix": "#r", "body": ["𝚛",],},
    "𝚜": {"prefix": "#s", "body": ["𝚜",],},
    "𝚝": {"prefix": "#t", "body": ["𝚝",],},
    "𝚞": {"prefix": "#u", "body": ["𝚞",],},
    "𝚟": {"prefix": "#v", "body": ["𝚟",],},
    "𝚠": {"prefix": "#w", "body": ["𝚠",],},
    "𝚡": {"prefix": "#x", "body": ["𝚡",],},
    "𝚢": {"prefix": "#y", "body": ["𝚢",],},
    "𝚣": {"prefix": "#z", "body": ["𝚣",],},
    "𝙰": {"prefix": "#aa", "body": ["𝙰",],},
    "𝙱": {"prefix": "#bb", "body": ["𝙱",],},
    "𝙲": {"prefix": "#cc", "body": ["𝙲",],},
    "𝙳": {"prefix": "#dd", "body": ["𝙳",],},
    "𝙴": {"prefix": "#ee", "body": ["𝙴",],},
    "𝙵": {"prefix": "#ff", "body": ["𝙵",],},
    "𝙶": {"prefix": "#gg", "body": ["𝙶",],},
    "𝙷": {"prefix": "#hh", "body": ["𝙷",],},
    "𝙸": {"prefix": "#ii", "body": ["𝙸",],},
    "𝙹": {"prefix": "#jj", "body": ["𝙹",],},
    "𝙺": {"prefix": "#kk", "body": ["𝙺",],},
    "𝙻": {"prefix": "#ll", "body": ["𝙻",],},
    "𝙼": {"prefix": "#mm", "body": ["𝙼",],},
    "𝙽": {"prefix": "#nn", "body": ["𝙽",],},
    "𝙾": {"prefix": "#oo", "body": ["𝙾",],},
    "𝙿": {"prefix": "#pp", "body": ["𝙿",],},
    "𝚀": {"prefix": "#qq", "body": ["𝚀",],},
    "𝚁": {"prefix": "#rr", "body": ["𝚁",],},
    "𝚂": {"prefix": "#ss", "body": ["𝚂",],},
    "𝚃": {"prefix": "#tt", "body": ["𝚃",],},
    "𝚄": {"prefix": "#uu", "body": ["𝚄",],},
    "𝚅": {"prefix": "#vv", "body": ["𝚅",],},
    "𝚆": {"prefix": "#ww", "body": ["𝚆",],},
    "𝚇": {"prefix": "#xx", "body": ["𝚇",],},
    "𝚈": {"prefix": "#yy", "body": ["𝚈",],},
    "𝚉": {"prefix": "#zz", "body": ["𝚉",],},
}

### Thanks for reading even though you might find no use of this extension XD