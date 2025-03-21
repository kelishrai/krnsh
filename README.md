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
                    "foreground": "#9686c5"
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
                    "foreground": "#c586c0"
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

    "𝘢": {"prefix": "$a", "body": ["𝘢",],},
    "𝘣": {"prefix": "$b", "body": ["𝘣",],},
    "𝘤": {"prefix": "$c", "body": ["𝘤",],},
    "𝘥": {"prefix": "$d", "body": ["𝘥",],},
    "𝘦": {"prefix": "$e", "body": ["𝘦",],},
    "𝘧": {"prefix": "$f", "body": ["𝘧",],},
    "𝘨": {"prefix": "$g", "body": ["𝘨",],},
    "𝘩": {"prefix": "$h", "body": ["𝘩",],},
    "𝘪": {"prefix": "$i", "body": ["𝘪",],},
    "𝘫": {"prefix": "$j", "body": ["𝘫",],},
    "𝘬": {"prefix": "$k", "body": ["𝘬",],},
    "𝘭": {"prefix": "$l", "body": ["𝘭",],},
    "𝘮": {"prefix": "$m", "body": ["𝘮",],},
    "𝘯": {"prefix": "$n", "body": ["𝘯",],},
    "𝘰": {"prefix": "$o", "body": ["𝘰",],},
    "𝘱": {"prefix": "$p", "body": ["𝘱",],},
    "𝘲": {"prefix": "$q", "body": ["𝘲",],},
    "𝘳": {"prefix": "$r", "body": ["𝘳",],},
    "𝘴": {"prefix": "$s", "body": ["𝘴",],},
    "𝘵": {"prefix": "$t", "body": ["𝘵",],},
    "𝘶": {"prefix": "$u", "body": ["𝘶",],},
    "𝘷": {"prefix": "$v", "body": ["𝘷",],},
    "𝘸": {"prefix": "$w", "body": ["𝘸",],},
    "𝘹": {"prefix": "$x", "body": ["𝘹",],},
    "𝘺": {"prefix": "$y", "body": ["𝘺",],},
    "𝘻": {"prefix": "$z", "body": ["𝘻",],},
    "𝘈": {"prefix": "$aa", "body": ["𝘈",],},
    "𝘉": {"prefix": "$bb", "body": ["𝘉",],},
    "𝘊": {"prefix": "$cc", "body": ["𝘊",],},
    "𝘋": {"prefix": "$dd", "body": ["𝘋",],},
    "𝘌": {"prefix": "$ee", "body": ["𝘌",],},
    "𝘍": {"prefix": "$ff", "body": ["𝘍",],},
    "𝘎": {"prefix": "$gg", "body": ["𝘎",],},
    "𝘏": {"prefix": "$hh", "body": ["𝘏",],},
    "𝘐": {"prefix": "$ii", "body": ["𝘐",],},
    "𝘑": {"prefix": "$jj", "body": ["𝘑",],},
    "𝘒": {"prefix": "$kk", "body": ["𝘒",],},
    "𝘓": {"prefix": "$ll", "body": ["𝘓",],},
    "𝘔": {"prefix": "$mm", "body": ["𝘔",],},
    "𝘕": {"prefix": "$nn", "body": ["𝘕",],},
    "𝘖": {"prefix": "$oo", "body": ["𝘖",],},
    "𝘗": {"prefix": "$pp", "body": ["𝘗",],},
    "𝘘": {"prefix": "$qq", "body": ["𝘘",],},
    "𝘙": {"prefix": "$rr", "body": ["𝘙",],},
    "𝘚": {"prefix": "$ss", "body": ["𝘚",],},
    "𝘛": {"prefix": "$tt", "body": ["𝘛",],},
    "𝘜": {"prefix": "$uu", "body": ["𝘜",],},
    "𝘝": {"prefix": "$vv", "body": ["𝘝",],},
    "𝘞": {"prefix": "$ww", "body": ["𝘞",],},
    "𝘟": {"prefix": "$xx", "body": ["𝘟",],},
    "𝘠": {"prefix": "$yy", "body": ["𝘠",],},
    "𝘡": {"prefix": "$zz", "body": ["𝘡",],},
    "𝟶": {"prefix": "$0", "body": ["𝟶",],},
    "𝟷": {"prefix": "$1", "body": ["𝟷",],},
    "𝟸": {"prefix": "$2", "body": ["𝟸",],},
    "𝟹": {"prefix": "$3", "body": ["𝟹",],},
    "𝟺": {"prefix": "$4", "body": ["𝟺",],},
    "𝟻": {"prefix": "$5", "body": ["𝟻",],},
    "𝟼": {"prefix": "$6", "body": ["𝟼",],},
    "𝟽": {"prefix": "$7", "body": ["𝟽",],},
    "𝟾": {"prefix": "$8", "body": ["𝟾",],},
    "𝟿": {"prefix": "$9", "body": ["𝟿",],},

    "𝗮": {"prefix": "#a", "body": ["𝗮",],},
    "𝗯": {"prefix": "#b", "body": ["𝗯",],},
    "𝗰": {"prefix": "#c", "body": ["𝗰",],},
    "𝗱": {"prefix": "#d", "body": ["𝗱",],},
    "𝗲": {"prefix": "#e", "body": ["𝗲",],},
    "𝗳": {"prefix": "#f", "body": ["𝗳",],},
    "𝗴": {"prefix": "#g", "body": ["𝗴",],},
    "𝗵": {"prefix": "#h", "body": ["𝗵",],},
    "𝗶": {"prefix": "#i", "body": ["𝗶",],},
    "𝗷": {"prefix": "#j", "body": ["𝗷",],},
    "𝗸": {"prefix": "#k", "body": ["𝗸",],},
    "𝗹": {"prefix": "#l", "body": ["𝗹",],},
    "𝗺": {"prefix": "#m", "body": ["𝗺",],},
    "𝗻": {"prefix": "#n", "body": ["𝗻",],},
    "𝗼": {"prefix": "#o", "body": ["𝗼",],},
    "𝗽": {"prefix": "#p", "body": ["𝗽",],},
    "𝗾": {"prefix": "#q", "body": ["𝗾",],},
    "𝗿": {"prefix": "#r", "body": ["𝗿",],},
    "𝘀": {"prefix": "#s", "body": ["𝘀",],},
    "𝘁": {"prefix": "#t", "body": ["𝘁",],},
    "𝘂": {"prefix": "#u", "body": ["𝘂",],},
    "𝘃": {"prefix": "#v", "body": ["𝘃",],},
    "𝘄": {"prefix": "#w", "body": ["𝘄",],},
    "𝘅": {"prefix": "#x", "body": ["𝘅",],},
    "𝘆": {"prefix": "#y", "body": ["𝘆",],},
    "𝘇": {"prefix": "#z", "body": ["𝘇",],},
    "𝗔": {"prefix": "#aa", "body": ["𝗔",],},
    "𝗕": {"prefix": "#bb", "body": ["𝗕",],},
    "𝗖": {"prefix": "#cc", "body": ["𝗖",],},
    "𝗗": {"prefix": "#dd", "body": ["𝗗",],},
    "𝗘": {"prefix": "#ee", "body": ["𝗘",],},
    "𝗙": {"prefix": "#ff", "body": ["𝗙",],},
    "𝗚": {"prefix": "#gg", "body": ["𝗚",],},
    "𝗛": {"prefix": "#hh", "body": ["𝗛",],},
    "𝗜": {"prefix": "#ii", "body": ["𝗜",],},
    "𝗝": {"prefix": "#jj", "body": ["𝗝",],},
    "𝗞": {"prefix": "#kk", "body": ["𝗞",],},
    "𝗟": {"prefix": "#ll", "body": ["𝗟",],},
    "𝗠": {"prefix": "#mm", "body": ["𝗠",],},
    "𝗡": {"prefix": "#nn", "body": ["𝗡",],},
    "𝗢": {"prefix": "#oo", "body": ["𝗢",],},
    "𝗣": {"prefix": "#pp", "body": ["𝗣",],},
    "𝗤": {"prefix": "#qq", "body": ["𝗤",],},
    "𝗥": {"prefix": "#rr", "body": ["𝗥",],},
    "𝗦": {"prefix": "#ss", "body": ["𝗦",],},
    "𝗧": {"prefix": "#tt", "body": ["𝗧",],},
    "𝗨": {"prefix": "#uu", "body": ["𝗨",],},
    "𝗩": {"prefix": "#vv", "body": ["𝗩",],},
    "𝗪": {"prefix": "#ww", "body": ["𝗪",],},
    "𝗫": {"prefix": "#xx", "body": ["𝗫",],},
    "𝗬": {"prefix": "#yy", "body": ["𝗬",],},
    "𝗭": {"prefix": "#zz", "body": ["𝗭",],},
    "𝟬": {"prefix": "#0", "body": ["𝟬",],},
    "𝟭": {"prefix": "#1", "body": ["𝟭",],},
    "𝟮": {"prefix": "#2", "body": ["𝟮",],},
    "𝟯": {"prefix": "#3", "body": ["𝟯",],},
    "𝟰": {"prefix": "#4", "body": ["𝟰",],},
    "𝟱": {"prefix": "#5", "body": ["𝟱",],},
    "𝟲": {"prefix": "#6", "body": ["𝟲",],},
    "𝟳": {"prefix": "#7", "body": ["𝟳",],},
    "𝟴": {"prefix": "#8", "body": ["𝟴",],},
    "𝟵": {"prefix": "#9", "body": ["𝟵",],},
}

### Thanks for reading even though you might find no use of this extension XD