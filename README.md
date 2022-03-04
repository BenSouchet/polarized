# Polarized
![cover_polarized](https://user-images.githubusercontent.com/17025808/156747993-fe5a5011-7c81-45d5-a6e3-1b6606cbdd2a.png)

**Polarized** is a color palette (17 colors) for IDEs, editors & code highlighters.  

The palette is based on [Solarized](https://github.com/altercation/solarized) but introduce modifications on the "monotones" colors and a strict guideline on what's the purpose of the colors.

## Light & Dark
**Polarized** exists in two variantes *Light* and *Dark*.

![palettes](https://user-images.githubusercontent.com/17025808/156766126-29925756-2f46-40f0-b1de-c9abefffb740.png)

## Colors Info
| Short Name | Color Name | Light Hex | Dark Hex | Apply on | Description |
|:----------:|:----------:|:---------:|:--------:|:--------:|:-----------:|
| `bgr` | background | #fdf6e3 | #002c37 | background | Code Block Background, Editor Background |
| `hgl` | highlighted | #e1d8c3 | #134a54 | background | Highlighted Line(s), Search Results Highlighed (not user selection) |
| `sel` | selection | #c4bba2 | #396770 | background | User Selection of word(s) or line(s) |
| `com` | *comments* | #a89d82 | #5e858d | text | Code Comments (comments are normally displayed in *italic*) |
| `lin` | line n° | #8b8061 | #80a3aa | text | Line Numbers |
| `def` | default | #6f6241 | #a3c1c7 | text | Default color for text, delimiters & ponctuations (`{`,`}`,`;`,`,`,...) |
| `acc` | Accent | #524520 | #c5dee3 | text | Use when default text are selected to keep text readibility |
| `kwd` | **keywords** | #85754e | #92adb2 | text | Keywords, Keyword Declaration (e.g. `var` in JavaScript), Keyword Type (`int`, `float`, ...), Keyword Namespace (`namespace`) |
| `esc` | escaped | #cb4b16 | #cb4b16 | text | Escaped Characters, Regex, Interpoled Strings, Character Entities |
| `res` | reserved | #b58900 | #b58900 | text | Reserved Keywords, Constant Keywords, Pseudo Keywords |
| `opr` | operators | #859900 | #859900 | text | Operators, Word Operators |
| `str` | strings | #2aa198 | #2aa198 | text | Strings, DocStrings |
| `var` | variables | #268bd2 | #268bd2 | text | Variable Names, Attributes Names |
| `nam` | names | #6c71c4 | #6c71c4 | text | Namespace Names, Class Names, Decorator Names, Exception Names, Function Names |
| `nbr` | numbers | #d33682 | #d33682 | text | All kind of Numbers (integer, float, hex, binary, ...) |
| `err` | errors | #dc322f | #dc322f | text OR wavy underline | Errors (the color can be applied to text or only to a wavy underline), Diff Deleted (apply on text) |
| `ins` | inserted | #83dc2f | #83dc2f | text | Diff Inserted, Success Messages |

## Additionnal Info
Normally comments should be displayed in *italics*.  
**AND**  
Keywords should be in **bold** (to easily identify them).

## Sixteen Color Palette
**Polarized** is a seventeen (17) color palette but if you need (or are restricted) to only sixteen colors, you can ignore the accent (`acc`) color or use the operators (`opr`) color for the Diff Inserted texts.

## Specific colors (Light & Dark)
As you can see the Light and Dark variantes of **Polarized** share 9 colors and have 8 specific colors. These specific colors were obtained by blending two colors:

## Others Ressouces & Useful links
- [Sorbus Auto-Theme for Rouge Highlighter](https://github.com/BenSouchet/sorbus)
- [Solarized Github Project](https://github.com/altercation/solarized)
- [Solarized Website](https://ethanschoonover.com/solarized/)

## Author & maintainer
Polarized has been created and is currently maintained by [Ben Souchet](https://github.com/BenSouchet).

The code present in this repository is under [MIT license](https://github.com/BenSouchet/polarized/blob/main/LICENSE).
