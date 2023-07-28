# Source Han Sans/Serif UFO Edits

## About
This is a quick-and-dirty repository to store my edits to [Source Han Sans](https://github.com/adobe-fonts/source-han-sans) and [Serif](https://github.com/adobe-fonts/source-han-serif). For now, they are only provided in UFO and/or glyphspackage format, the former for which can be read by most font editors and the latter specifically for [Glyphs for Mac](https://glyphsapp.com/). The sources are overlapped, which is suitable for variable fonts, and available in two masters, ExtraLight and Heavy.

It is divided into folder categories of orthography formats, followed by typeface style. For now, there is only the traditional orthography format (Simplified Chinese: 旧字形/传承字形; Traditional Chinese: 舊字形/傳承字形) and some Japanese kana edits available. More orthography formats may follow in the near future.

**Please note:** This repository does not contain any final font files in OTF/TTF format as I currently lack the technical knowledge to re-compile Source Han Sans/Serif into a usable font with my own glyph edits. So for now, the best I can contribute is by releasing my edits as overlapping source-only formats. Anyone can use them in their own Source Han forks as they please.

Regarding the versions, my edits are based on Source Han Sans v2.004 and Source Han Serif v2.001.

## Quick setup

### Source Han Sans

_Detailed instructions coming soon..._

For Glyphs, click on File, and then Open.

Go to Font Info.

At the _Font_ tab, Units per Em should be set to 1000. In the _Axes_ subsection, create a new Weight value.

At the _Masters_ tab, set up a ExtraLight master and a Heavy master. The Heavy master can be added by clicking on the + button, then selecting Add Other Font.

The ExtraLight master should be set up as follows:

_[insert image here]_

The Heavy master should be set up as follows:

_[insert image here]_

At the _Exports_ tab, create the intermediate weights with the following values:

Weight Name | Weight Value
-- | --
ExtraLight | 0
Light | 160
Normal | 320
Regular | 390
Medium | 560
Bold | 780
Heavy | 1000

### Source Han Serif

_Detailed instructions coming soon..._

For Glyphs, click on File, and then Open.

Go to Font Info.

At the _Font_ tab, Units per Em should be set to 1000. In the _Axes_ subsection, create a new Weight value.

At the _Masters_ tab, set up a ExtraLight master and a Heavy master. The Heavy master can be added by clicking on the + button, then selecting Add Other Font.

The ExtraLight master should be set up as follows:

_[insert image here]_

The Heavy master should be set up as follows:

_[insert image here]_

At the _Exports_ tab, create the intermediate weights with the following values:

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
* Ichitenfont for the [Inherited Glyph reference](https://github.com/ichitenfont/inheritedglyphs).
