## Fontbakery report

Fontbakery version: 0.8.8

<details><summary><b>[6] Calistoga-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:
	- f + f
	- f + i
	- i + f
	- f + l
	- l + f
	- i + l

   [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:
	- NULL
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni01EC	Contours detected: 4	Expected: 3
	- Glyph name: uni01ED	Contours detected: 4	Expected: 3
	- Glyph name: uni01F5	Contours detected: 4	Expected: 3
	- Glyph name: uni0228	Contours detected: 2	Expected: 1
	- Glyph name: uni0229	Contours detected: 3	Expected: 2
	- Glyph name: uni0E3F	Contours detected: 4	Expected: 3
	- Glyph name: uni1E08	Contours detected: 3	Expected: 2
	- Glyph name: uni1E09	Contours detected: 3	Expected: 2
	- Glyph name: uni1E1C	Contours detected: 3	Expected: 2
	- Glyph name: uni1E1D	Contours detected: 4	Expected: 3 
	- And 9 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:
	* uogonek (U+0173): L<<509.0,2.0>--<509.0,2.0>>/B<<509.0,2.0>-<463.0,-9.0>-<440.5,-36.0>> = 13.448615051686527 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/latest/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:
 * Eng (U+014A): L<<494.0,-2.0>--<493.0,506.0>>
 * Eng (U+014A): L<<661.0,518.0>--<662.0,-9.0>>
 * eng (U+014B): L<<380.0,-2.0>--<379.0,379.0>>
 * eng (U+014B): L<<543.0,408.0>--<544.0,-9.0>>
 * franc (U+20A3): L<<503.0,459.0>--<504.0,286.0>>
 * uni00B5 (U+00B5): L<<191.0,-396.0>--<194.0,-4.0>>
 * uni03BC (U+03BC): L<<54.0,-192.0>--<57.0,154.0>>
 * uni1E9E (U+1E9E): L<<236.0,394.0>--<235.0,-13.0>> and uni1E9E (U+1E9E): L<<67.0,100.0>--<68.0,373.0>> [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 6 | 104 | 7 | 108 | 0 |
| 0% | 0% | 3% | 46% | 3% | 48% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
