# Polarized
![cover_polarized](https://user-images.githubusercontent.com/17025808/156747993-fe5a5011-7c81-45d5-a6e3-1b6606cbdd2a.png)

**Polarized** is a color palette (17 colors) for IDEs, editors & code highlighters.  

The palette is based on [Solarized](https://github.com/altercation/solarized) but introduce modifications on the "monotones" colors and a <ins>strict guideline</ins> on what's the purpose of the colors.

## Light & Dark
**Polarized** exists in two variants *Light* and *Dark*.

![palettes](https://user-images.githubusercontent.com/17025808/156766126-29925756-2f46-40f0-b1de-c9abefffb740.png)


As you can see the *Light* and *Dark* variants of **Polarized** share 9 colors and have 8 specific colors. These specific colors were obtained by blending two colors as you can see here:
![gradients](https://user-images.githubusercontent.com/17025808/157433104-a9e27335-adeb-421a-bfa7-ecb91398a4ad.png)

The last color of each row (image below) aren't used in the final palette, these colors were simply used in the blending process to generate the other colors.

## Colors Info / Guidelines
| Short Name | Color Name | Light | Dark | Apply on | Description |
|:----------:|:----------:|:---------:|:--------:|:--------:|:-----------:|
| `bgr` | background | ![bgr_light](https://user-images.githubusercontent.com/17025808/157435460-bdf1df00-b898-412d-849c-cc60e90ab7b9.png) | ![bgr_dark](https://user-images.githubusercontent.com/17025808/157435643-abdbc5dd-bbe9-4318-9a18-36fbae6cc946.png) | background | Code Block Background, Editor Background |
| `hgl` | highlighted | ![hgl_light](https://user-images.githubusercontent.com/17025808/157435484-9eed3590-b746-49fa-aac3-917c4f59ba6f.png) | ![hgl_dark](https://user-images.githubusercontent.com/17025808/157435684-0e04d721-57f0-44cb-a8fc-ca921a7e3626.png) | background | Highlighted Line(s), Search Results Highlighed (not user selection) |
| `sel` | selection | ![sel_light](https://user-images.githubusercontent.com/17025808/157435507-16839184-c041-41fe-b10c-2cac7c0bc1b3.png) | ![sel_dark](https://user-images.githubusercontent.com/17025808/157435706-b1782db8-f4e5-4854-a9fc-4f4f486e7116.png) | background | User Selection of word(s) or line(s) |
| `com` | *comments* | ![com_light](https://user-images.githubusercontent.com/17025808/157435531-a88f9254-91ae-430a-8b39-8acb21d1a0cf.png) | ![com_dark](https://user-images.githubusercontent.com/17025808/157435734-46e58344-56b2-4ee1-9581-166a03038818.png) | text | Code Comments (comments are normally displayed in *italic*) |
| `lin` | line n° | ![lin_light](https://user-images.githubusercontent.com/17025808/157435562-0568c867-1c22-4400-963f-9ef78d7e7c00.png) | ![lin_dark](https://user-images.githubusercontent.com/17025808/157435773-079becd4-450b-40e9-af19-a71644487193.png) | text | Line Numbers |
| `def` | default | ![def_light](https://user-images.githubusercontent.com/17025808/157435586-66054cd5-5503-4974-a5c2-9f092d159469.png) | ![def_dark](https://user-images.githubusercontent.com/17025808/157435796-725b1438-f8a0-4185-b9d0-190807c7a87e.png) | text | Default color for text, delimiters & ponctuations (`{`,`}`,`;`,`,`,...) |
| `acc` | Accent | ![acc_light](https://user-images.githubusercontent.com/17025808/157435615-5f7098df-7333-4df1-9fe1-4a3cf3f3b4a0.png) | ![acc_dark](https://user-images.githubusercontent.com/17025808/157435849-b2f39dee-367d-4ee6-94bb-01b136e3ef81.png) | text | Use when default text are selected to keep text readibility |
| `kwd` | **keywords** | ![kwd_light](https://user-images.githubusercontent.com/17025808/157437330-38849a15-578b-4bc5-a1a9-b04fcb22ff50.png) | ![kwd_dark](https://user-images.githubusercontent.com/17025808/157437362-a3d7da14-b24b-4985-ba75-6fe0d1d7dffe.png) | text | Keywords, Keyword Declaration (e.g. `var` in JavaScript), Keyword Type (`int`, `float`, ...), Keyword Namespace (`namespace`) |
| `esc` | escaped | ![esc](https://user-images.githubusercontent.com/17025808/157437402-d691fd7d-c4c0-4fbd-be31-71c437331095.png) | ![esc](https://user-images.githubusercontent.com/17025808/157437402-d691fd7d-c4c0-4fbd-be31-71c437331095.png) | text | Escaped Characters, Regex, Interpoled Strings, Character Entities |
| `res` | reserved | ![res](https://user-images.githubusercontent.com/17025808/157437461-2abf575e-777e-4e7b-83fa-6baa66682e99.png) | ![res](https://user-images.githubusercontent.com/17025808/157437461-2abf575e-777e-4e7b-83fa-6baa66682e99.png) | text | Reserved Keywords, Constant Keywords, Pseudo Keywords |
| `opr` | operators | ![opr](https://user-images.githubusercontent.com/17025808/157437520-84542c82-ea2d-46ac-a7f9-50555b3ee885.png) | ![opr](https://user-images.githubusercontent.com/17025808/157437520-84542c82-ea2d-46ac-a7f9-50555b3ee885.png) | text | Operators, Word Operators |
| `str` | strings | ![str](https://user-images.githubusercontent.com/17025808/157437573-51c7a5f9-618e-4980-8746-525d03e4f92b.png) | ![str](https://user-images.githubusercontent.com/17025808/157437573-51c7a5f9-618e-4980-8746-525d03e4f92b.png) | text | Strings, DocStrings |
| `var` | variables | ![var](https://user-images.githubusercontent.com/17025808/157437611-51c9242e-9086-420e-a7f3-e07370021236.png) | ![var](https://user-images.githubusercontent.com/17025808/157437611-51c9242e-9086-420e-a7f3-e07370021236.png) | text | Variable Names, Attributes Names |
| `nam` | names | ![nam](https://user-images.githubusercontent.com/17025808/157437655-b29bcc05-a007-4b28-8003-6d7dcc5a8b5f.png) | ![nam](https://user-images.githubusercontent.com/17025808/157437655-b29bcc05-a007-4b28-8003-6d7dcc5a8b5f.png) | text | Namespace Names, Class Names, Decorator Names, Exception Names, Function Names |
| `nbr` | numbers | ![nbr](https://user-images.githubusercontent.com/17025808/157437726-7598721d-7ef6-4903-807a-4cfe8129e902.png) | ![nbr](https://user-images.githubusercontent.com/17025808/157437726-7598721d-7ef6-4903-807a-4cfe8129e902.png) | text | All kind of Numbers (integer, float, hex, binary, ...) |
| `err` | errors | ![err](https://user-images.githubusercontent.com/17025808/157437772-ef2e2fd6-8b8a-442d-9863-a1cf2fe9d8fa.png) | ![err](https://user-images.githubusercontent.com/17025808/157437772-ef2e2fd6-8b8a-442d-9863-a1cf2fe9d8fa.png) | text OR wavy underline | Errors (the color can be applied to text or only to a wavy underline), Diff Deleted (apply on text) |
| `ins` | inserted | ![ins](https://user-images.githubusercontent.com/17025808/157437809-fa25de21-e150-45a2-b809-27c011c6893a.png) | ![ins](https://user-images.githubusercontent.com/17025808/157437809-fa25de21-e150-45a2-b809-27c011c6893a.png) | text | Diff Inserted, Success Messages |

As you can see every colors are meant to be used for a specific purpose. Of course if in your case you can't use all the colors do your best to stay as close as possible to the original palette. 

## Palette Colors Values
Find in [this page](https://github.com/BenSouchet/polarized/blob/main/VALUES.md) a table with the exact colors codes in multiple color models (HEX, RGB, HSV, HSL, Lab).  

There is also files in the [`palette` folder](https://github.com/BenSouchet/polarized/tree/main/palette) defining the colors in HEX in multiple formats: [YAML](https://github.com/BenSouchet/polarized/tree/main/palette/yaml), [CSS](), [SCSS]().

**Important**: if you implement the color palette in an editor, a website, a service, ... please do not modify the color codes (use the exact ones listed in [this page](https://github.com/BenSouchet/polarized/blob/main/VALUES.md)).

## Additionnal Info
If you implement this palette as a color theme somewhere, code comments should be displayed in *italics*, and keywords should be in **bold** (to easily identify them).

## Sixteen Color Palette
**Polarized** is a seventeen (17) color palette but if you need (or are restricted) to only sixteen colors, you can ignore the accent (`acc`) color or use the operators (`opr`) color for the Diff Inserted texts.

## Others Ressouces & Useful links
- [Sorbus Auto-Theme for Rouge Highlighter](https://github.com/BenSouchet/sorbus), in this project **Polarized** is one of the default color palettes available.
- [Solarized Github Project](https://github.com/altercation/solarized) & [Website](https://ethanschoonover.com/solarized/), the original palette **Polarized** is based on.
- [Color Blend](https://bensouchet.github.io/color-blend/), website to blend two colors and generate intermediates colors.
- [Colorizer.org](http://colorizer.org/), super tool to convert and play with colors into multiples color models (HSV, HSL, Lab, ...).

## Author & maintainer
Polarized has been created and is currently maintained by [Ben Souchet](https://github.com/BenSouchet).

All the files present in this repository are under [MIT license](https://github.com/BenSouchet/polarized/blob/main/LICENSE).
