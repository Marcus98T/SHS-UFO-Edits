# Source Han Sans/Serif UFO Edits

## About
This is a quick-and-dirty repository to store my edits to [Source Han Sans](https://github.com/adobe-fonts/source-han-sans) and [Serif](https://github.com/adobe-fonts/source-han-serif) (思源黑體/思源宋體). For now, they are only provided in UFO and glyphspackage formats, the former for which can be read by most font editors and the latter specifically for [Glyphs for Mac](https://glyphsapp.com/). The sources are overlapped, which is suitable for variable fonts, and available in two masters, ExtraLight and Heavy.

It is divided into folder categories of orthography formats, followed by typeface style. For now, there is only the traditional orthography format (Simplified Chinese: 旧字形/传承字形; Traditional Chinese: 舊字形/傳承字形), the JP glyphs missing from the main font and some Japanese kana edits available. More orthography formats will follow in the near future.

**Please note:** This repository does not contain any final font files in OTF/TTF format as I currently lack the technical knowledge to re-compile Source Han Sans/Serif into a usable font with my own glyph edits, especially when it comes to dealing with the complexity of multi-region fonts and working around Unicode limitations. So for now, the best I can contribute is by releasing my edits as overlapping source-only formats. Anyone can use them in their own Source Han forks as they please. Also, the sources do not contain the entire font, only my glyph edits.

Regarding the versions, my edits are based on Source Han Sans v2.004 and Source Han Serif v2.001. If a new version is released, any glyphs added from that version will be noted down as such.

The sources will be updated with new glyphs and adjustments periodically. They will be noted in their respective changelogs.

## Regarding the ridiculous names

The naming of the source files will temporarily be called "WIPSHDC" (an unoriginal acronym I have to make up), followed by the category (like "Kana" or "Old-Traditional" as mentioned above), and then either "Sans" or "Serif" as the suffix. A better name will be decided in the near future.

## Quick weight setup

These tables are provided as reference to recreate the intermediate weights in the font editor of your choosing.

### Sans

Weight Name | Weight Value
-- | --
ExtraLight | 0
Light | 160
Normal | 320
Regular | 390
Medium | 560
Bold | 780
Heavy | 1000

### Serif

Weight Name | Weight Value
-- | --
ExtraLight | 0
Light | 95
Regular | 210
Medium | 360
SemiBold | 510
Bold | 730
Heavy | 1000

## Licence

As always, the sources are licensed under the SIL Open Font License.

## Special Thanks to:
* ChiuMing-Neko for the [ChiuKong Gothic project (秋空黑體)](https://github.com/ChiuMing-Neko/ChiuKongGothic).
* NightFurySL2001 for providing some support.
* ButTaiwan for [GenYoGothic (源樣黑體)](https://github.com/ButTaiwan/genyog-font), for which I recreated the き and さ kana designs to work with variable format.
* Tamcy for providing the sources to the [Chiron HK](https://github.com/chiron-fonts/chiron-hei-hk-gf) [font series](https://github.com/chiron-fonts/chiron-sung-hk-gf) for Google Fonts.
* Ichitenfont for the [Inherited Glyph reference](https://github.com/ichitenfont/inheritedglyphs).
