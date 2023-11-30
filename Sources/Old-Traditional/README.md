# Old Traditional

This category consists of Chinese characters as they appeared in the 1970s and 1980s during the phototypesetting era, particularly in Taiwan and Hong Kong.

They are called by several names including **traditional orthography**, **old forms**, **old character shape** (Simplified Chinese: 旧字形; Traditional Chinese: 舊字形), **inherited glyphs** (Simplified Chinese: 传承字形; Traditional Chinese: 傳承字形), **kyūjitai** (Japanese: 旧字体/舊字體) and so on.

As everybody knows, the glyph shapes are derived from the Japanese and Korean versions of Source Han Sans and Serif, unlike the official Chinese versions which follow their respective handwritten government orthography (Chinese: 楷化, 新字形).

Right now, they mostly contain glyphs that I'm 100% sure will never make it into the main Adobe fonts due to their glyph policy.

As for restoring v1 JP glyphs, because Adobe is not giving the project some love recently with the exception of a few external requirements deemed bare minimum, I will release the manually recreated sources first.

Regarding Inherited Glyphs, I believe it was created to standardise on the many different old forms throughout Chinese history. This will not be the main scope here as the plan is to recreate the forms seen in 1970s and 1980s newspapers and other media, which may not be deemed correct in the Inherited Glyphs standard. Regardless, many glyphs can be useful for the project.

Regarding a potential major update to Source Han Sans in the future, it is possible that some JP forms as seen in v2 (e.g. 立, 豆, 子, 戶, 人, 夕, etc.) might be unified to the CN forms. If such a scenario happens, the sources will retain the JP-style aesthetics as of v2 rather than adopt the new unified forms.

Some glyphs are taken from [Chiukong Gothic](https://github.com/ChiuMing-Neko/ChiuKongGothic), and some of those imported glyphs are improved on to make them more JP-like. They will be noted in the glyph lists below.

## Glyph naming

To avoid confusion, the production names of the glyphs do not follow what is in the [AI0-SourceHanSans](https://github.com/adobe-fonts/source-han-sans/blob/release/Resources/AI0-SourceHanSans) or [AI0-SourceHanSerif](https://github.com/adobe-fonts/source-han-serif/blob/release/Resources/AI0-SourceHanSerif) files.

Here are a list of glyph suffixes. Taiwan will be the default glyph shape, so generally there is no suffix. The suffixes are also prepended by a period rather than dashes.

- uniXXXX<span>.</span>JP - Japanese glyph shape (according to their interpretation of the so-called Kangxi Dictionary forms)
- uniXXXX<span>.</span>HK - Hong Kong glyph shape
- uniXXXX<span>.</span>HK2 - Alternate Hong Kong glyph shape
- uniXXXX<span>.</span>inherited - Glyph shapes that follow the [Inherited Glyph standard](https://github.com/ichitenfont/inheritedglyphs) and may not appear in old prints.
- uniXXXX<span>.</span>altpr - Alternate print form (Unicode example, 卽 as an alternate print form for 即) which is also commonplace in some old typefaces.
- uniXXXX<span>.</span>noaxe - (Serif only) An alternate form which does not include the decorative axe in strokes like 乀. Inherited Glyphs adopts this standard by default, but in old media, this is less commonly seen.

## List of glyphs available

- [Sans](glyphlist-old-traditional-sans.md)
- [Serif](glyphlist-old-traditional-serif.md)
