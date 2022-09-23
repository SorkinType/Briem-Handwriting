## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[22] BriemHandwriting-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 fsType does not impose restrictions. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fstype">com.google.fonts/check/fstype</a>)</summary><div>


* 🔥 **FAIL** In this font fsType is set to 4 meaning that:
The font may be embedded, and temporarily loaded on the remote system, but documents that use it must not be editable.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWeightClass. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** OS/2 usWeightClass is '400' when it should be '900'. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** Font lacks NameID 13 (LICENSE DESCRIPTION). A proper licensing entry must be set. [code: missing]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking post.italicAngle value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/italic_angle">com.google.fonts/check/italic_angle</a>)</summary><div>


* 🔥 **FAIL** Font is not italic, so post.italicAngle should be equal to zero. [code: non-zero-normal]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.sTypoLineGap is "75" it should be 0 [code: bad-OS/2.sTypoLineGap]
* 🔥 **FAIL** The sum of hhea.ascender+abs(hhea.descender)+hhea.lineGap is 1000 when it should be at least 1200 [code: bad-hhea-range]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/ttf/BriemHandwriting-Black.ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoLineGap (75) and hhea lineGap (0) must be equal. [code: lineGap]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 275 font units wide, non-breaking space named (uni00A0) is 0 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>🔥 <b>FAIL:</b> Description strings in the name table must not contain copyright info. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/name.html#com.google.fonts/check/name/no_copyright_on_description">com.google.fonts/check/name/no_copyright_on_description</a>)</summary><div>


* 🔥 **FAIL** Some namerecords with ID=10 (NameID.DESCRIPTION) containing copyright info should be removed (perhaps these were added by a longstanding FontLab Studio 5.x bug that copied copyright notices to them.) [code: copyright-on-description]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_TransLatin_Pinyin is almost fulfilled. Missing codepoints:

	- 0x01D7 (LATIN CAPITAL LETTER U WITH DIAERESIS AND ACUTE)


	- 0x01D9 (LATIN CAPITAL LETTER U WITH DIAERESIS AND CARON)


	- 0x01DB (LATIN CAPITAL LETTER U WITH DIAERESIS AND GRAVE)


	- 0x01D5 (LATIN CAPITAL LETTER U WITH DIAERESIS AND MACRON)


	- 0x01D6 (LATIN SMALL LETTER U WITH DIAERESIS AND MACRON)


	- 0x207F (SUPERSCRIPT LATIN SMALL LETTER N)


	- 0x030D (COMBINING VERTICAL LINE ABOVE)


	- 0x0358 (COMBINING DOT ABOVE RIGHT)
 

	- And 0x1D3A (MODIFIER LETTER CAPITAL N)
 [code: missing-codepoints]
* ⚠ **WARN** GF_TransLatin_Arabic is almost fulfilled. Missing codepoints:

	- 0x1E21 (LATIN SMALL LETTER G WITH MACRON)


	- 0x1E35 (LATIN SMALL LETTER K WITH LINE BELOW)


	- 0x02BF (MODIFIER LETTER LEFT HALF RING)


	- 0x02BE (MODIFIER LETTER RIGHT HALF RING)


	- 0x1E96 (LATIN SMALL LETTER H WITH LINE BELOW)
 

	- And 0x02BD (MODIFIER LETTER REVERSED COMMA)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Briem Handwriting Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Font contains '.notdef' as its first glyph? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/mandatory_glyphs">com.google.fonts/check/mandatory_glyphs</a>)</summary><div>


* ⚠ **WARN** Glyph '.notdef' should contain a drawing, but it is empty. [code: empty]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- IJ_acutecomb

	- ibar 

	- And uni0328.alt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: onehalf	Contours detected: 2	Expected: 3

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni018E	Contours detected: 1	Expected: 2

	- Glyph name: uni01EA	Contours detected: 3	Expected: 2

	- Glyph name: uni0228	Contours detected: 2	Expected: 1

	- Glyph name: uni0229	Contours detected: 3	Expected: 2

	- Glyph name: uni0244	Contours detected: 0	Expected: 2

	- Glyph name: uni024C	Contours detected: 0	Expected: 2 

	- And 48 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Checking Vertical Metric Linegaps. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/hhea.html#com.google.fonts/check/linegaps">com.google.fonts/check/linegaps</a>)</summary><div>


* ⚠ **WARN** OS/2 sTypoLineGap is not equal to 0. [code: OS/2]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0283 (U+0283): L<<304.0,536.0>--<304.0,499.0>> -> L<<304.0,499.0>--<294.0,65.0>>

	* uni0283 (U+0283): L<<86.0,146.0>--<81.0,499.0>> -> L<<81.0,499.0>--<81.0,534.0>>

	* uni0324 (U+0324): L<<200.0,-120.0>--<200.0,-126.0>> -> L<<200.0,-126.0>--<200.0,-131.0>>

	* uni0324 (U+0324): L<<204.0,-145.0>--<205.0,-147.0>> -> L<<205.0,-147.0>--<206.0,-149.0>>

	* uni0324 (U+0324): L<<216.0,-83.0>--<214.0,-85.0>> -> L<<214.0,-85.0>--<212.0,-87.0>>

	* uni0324 (U+0324): L<<218.0,-81.0>--<216.0,-83.0>> -> L<<216.0,-83.0>--<214.0,-85.0>>

	* uni0324 (U+0324): L<<219.0,-80.0>--<218.0,-81.0>> -> L<<218.0,-81.0>--<216.0,-83.0>>

	* uni0324 (U+0324): L<<221.0,-78.0>--<219.0,-80.0>> -> L<<219.0,-80.0>--<218.0,-81.0>>

	* uni0324 (U+0324): L<<223.0,-76.0>--<221.0,-78.0>> -> L<<221.0,-78.0>--<219.0,-80.0>>

	* uni0324 (U+0324): L<<227.0,-74.0>--<225.0,-75.0>> -> L<<225.0,-75.0>--<223.0,-76.0>> 

	* And 58 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* a (U+0061): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* abreve (U+0103): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* agrave (U+00E0): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* amacron (U+0101): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* aring (U+00E5): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* aringacute (U+01FB): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* d (U+0064): B<<378.0,191.5>-<379.0,212.0>-<380.0,224.0>>/B<<380.0,224.0>-<375.0,205.0>-<357.0,175.5>> = 9.979921145744504

	* dcaron (U+010F): B<<378.0,191.5>-<379.0,212.0>-<380.0,224.0>>/B<<380.0,224.0>-<375.0,205.0>-<357.0,175.5>> = 9.979921145744504

	* h (U+0068): B<<270.0,315.0>-<268.0,284.0>-<268.0,275.0>>/B<<268.0,275.0>-<270.0,295.0>-<287.5,325.5>> = 5.710593137499633

	* hcircumflex (U+0125): B<<270.0,315.0>-<268.0,284.0>-<268.0,275.0>>/B<<268.0,275.0>-<270.0,295.0>-<287.5,325.5>> = 5.710593137499633 

	* And 57 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 9 | 13 | 116 | 7 | 82 | 0 |
| 0% | 4% | 6% | 51% | 3% | 36% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
