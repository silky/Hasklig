_N.B. This is a fork of the_ [Source Code Pro repository](https://github.com/adobe/source-code-pro)

## Hasklig - Ligatures for Haskell code

Programming languages are limited to relatively few characters. As a result of a limited character set, combined character operators surfaced quite early, such as the widely used arrow (`->`), comprised of a hyphen and greater sign. It looks like an arrow if you know the analogy and squint a bit.

Composite glyphs become especially  problematic in languages such as Haskell which utilize these complicated operators (`<-`, `::`, `=>`, `-<`, `>>=` etc.) extensively (over 100 in `lens` alone!). Prettified code improves readability considerably - some Haskell programmers have even resorted to unicode symbols (ie. `⇒`, `←` etc.). This opens a whole new can of worms. In addition to encoding/compatibility problems and all the reasons it never worked out in APL, these symbols are one-character-wide and therefore eye-strainingly small.

Hasklig solves this problem the way typographers have always solved ill-fitting characters which co-occur often: ligatures. The underlying code stays the same — only the representation changes.

[**Download**](https://github.com/i-tu/Hasklig/releases/download/v0.2/Hasklig_0.2.zip)

#### Hasklig
![Hasklig Sample](hasklig_example.png?raw=true)

#### Source Code Pro
![Source Code Pro Sample](SourceCodeProSample.png?raw=true)


## Support
Let me know how your editor is supported.

### Editors with known ligature support
+ Leksah
+ TextEdit
+ Atom _(add `text-rendering: optimizeLegibility;` to your `.editor` css.)_
+ Chocolat
+ Kate
+ KWrite
+ gEdit

### No ligature support
- Any terminal editor
- Sublime Text _(Vote for the enhancement [here](http://sublimetext.userecho.com/topic/433445-/))_
- MacVim


## To Do
1. Glyph substitution for `\` → `λ` and `.` → `∘`
2. Terminal support (for example iTerm2)
