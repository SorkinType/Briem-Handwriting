## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[13] BriemHandwriting-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (756) and hhea ascent (1300) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 275 font units wide, non-breaking space named (uni00A0) is 0 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.544x (1544) [code: bad-hhea-range]
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

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1 

	- And 80 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0283 (U+0283): L<<124.0,71.0>--<119.0,499.0>> -> L<<119.0,499.0>--<119.0,513.0>>

	* uni0283 (U+0283): L<<232.0,561.0>--<230.0,499.0>> -> L<<230.0,499.0>--<227.0,-1.0>>

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

	* m (U+006D): B<<200.0,217.0>-<198.0,188.0>-<197.0,180.0>>/B<<197.0,180.0>-<211.0,217.0>-<237.5,262.5>> = 13.600542516658704

	* n (U+006E): B<<198.0,217.0>-<196.0,188.0>-<195.0,180.0>>/B<<195.0,180.0>-<209.0,217.0>-<235.5,262.5>> = 13.600542516658704

	* nacute (U+0144): B<<198.0,217.0>-<196.0,188.0>-<195.0,180.0>>/B<<195.0,180.0>-<209.0,217.0>-<235.5,262.5>> = 13.600542516658704

	* ncaron (U+0148): B<<198.0,217.0>-<196.0,188.0>-<195.0,180.0>>/B<<195.0,180.0>-<209.0,217.0>-<235.5,262.5>> = 13.600542516658704

	* ntilde (U+00F1): B<<198.0,217.0>-<196.0,188.0>-<195.0,180.0>>/B<<195.0,180.0>-<209.0,217.0>-<235.5,262.5>> = 13.600542516658704

	* r (U+0072): B<<207.5,302.0>-<205.0,273.0>-<204.0,263.0>>/B<<204.0,263.0>-<235.0,356.0>-<268.0,414.0>> = 12.724355685422335

	* racute (U+0155): B<<207.5,302.0>-<205.0,273.0>-<204.0,263.0>>/B<<204.0,263.0>-<235.0,356.0>-<268.0,414.0>> = 12.724355685422335

	* rcaron (U+0159): B<<207.5,302.0>-<205.0,273.0>-<204.0,263.0>>/B<<204.0,263.0>-<235.0,356.0>-<268.0,414.0>> = 12.724355685422335

	* uni0146 (U+0146): B<<198.0,217.0>-<196.0,188.0>-<195.0,180.0>>/B<<195.0,180.0>-<209.0,217.0>-<235.5,262.5>> = 13.600542516658704

	* uni0157 (U+0157): B<<207.5,302.0>-<205.0,273.0>-<204.0,263.0>>/B<<204.0,263.0>-<235.0,356.0>-<268.0,414.0>> = 12.724355685422335 

	* And 16 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* f (U+0066): L<<230.0,442.0>--<227.0,-1.0>>

	* germandbls (U+00DF): L<<197.0,549.0>--<194.0,0.0>>

	* uni0283 (U+0283): L<<230.0,499.0>--<227.0,-1.0>> 

	* And uni1E1F (U+1E1F): L<<230.0,442.0>--<227.0,-1.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[13] BriemHandwriting-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (756) and hhea ascent (1300) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 275 font units wide, non-breaking space named (uni00A0) is 0 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Briem Handwriting SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.544x (1544) [code: bad-hhea-range]
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

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1 

	- And 78 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Z (U+005A): L<<166.0,336.0>--<180.0,336.0>> -> L<<180.0,336.0>--<180.0,336.0>>

	* Z (U+005A): L<<180.0,336.0>--<180.0,336.0>> -> L<<180.0,336.0>--<182.0,336.0>>

	* Zacute (U+0179): L<<166.0,336.0>--<180.0,336.0>> -> L<<180.0,336.0>--<180.0,336.0>>

	* Zacute (U+0179): L<<180.0,336.0>--<180.0,336.0>> -> L<<180.0,336.0>--<182.0,336.0>>

	* Zcaron (U+017D): L<<166.0,336.0>--<180.0,336.0>> -> L<<180.0,336.0>--<180.0,336.0>>

	* Zcaron (U+017D): L<<180.0,336.0>--<180.0,336.0>> -> L<<180.0,336.0>--<182.0,336.0>>

	* Zdotaccent (U+017B): L<<166.0,336.0>--<180.0,336.0>> -> L<<180.0,336.0>--<180.0,336.0>>

	* Zdotaccent (U+017B): L<<180.0,336.0>--<180.0,336.0>> -> L<<180.0,336.0>--<182.0,336.0>>

	* uni01C4 (U+01C4): L<<934.0,336.0>--<948.0,336.0>> -> L<<948.0,336.0>--<948.0,336.0>>

	* uni01C4 (U+01C4): L<<948.0,336.0>--<948.0,336.0>> -> L<<948.0,336.0>--<950.0,336.0>> 

	* And 76 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* m (U+006D): B<<234.0,273.0>-<231.0,239.0>-<230.0,223.0>>/B<<230.0,223.0>-<238.0,252.0>-<260.5,291.0>> = 11.845826943741303

	* m (U+006D): B<<569.5,265.0>-<567.0,237.0>-<565.0,224.0>>/B<<565.0,224.0>-<574.0,253.0>-<596.5,291.5>> = 8.49529713638477

	* n (U+006E): B<<233.0,273.0>-<230.0,239.0>-<229.0,223.0>>/B<<229.0,223.0>-<237.0,252.0>-<259.5,291.0>> = 11.845826943741303

	* nacute (U+0144): B<<233.0,273.0>-<230.0,239.0>-<229.0,223.0>>/B<<229.0,223.0>-<237.0,252.0>-<259.5,291.0>> = 11.845826943741303

	* ncaron (U+0148): B<<233.0,273.0>-<230.0,239.0>-<229.0,223.0>>/B<<229.0,223.0>-<237.0,252.0>-<259.5,291.0>> = 11.845826943741303

	* ntilde (U+00F1): B<<233.0,273.0>-<230.0,239.0>-<229.0,223.0>>/B<<229.0,223.0>-<237.0,252.0>-<259.5,291.0>> = 11.845826943741303

	* p (U+0070): B<<234.0,292.5>-<231.0,258.0>-<228.0,233.0>>/B<<228.0,233.0>-<237.0,262.0>-<259.0,299.5>> = 10.398685986309037

	* r (U+0072): B<<241.5,320.0>-<239.0,294.0>-<238.0,278.0>>/B<<238.0,278.0>-<278.0,402.0>-<324.5,463.0>> = 14.302362220843962

	* racute (U+0155): B<<241.5,320.0>-<239.0,294.0>-<238.0,278.0>>/B<<238.0,278.0>-<278.0,402.0>-<324.5,463.0>> = 14.302362220843962

	* rcaron (U+0159): B<<241.5,320.0>-<239.0,294.0>-<238.0,278.0>>/B<<238.0,278.0>-<278.0,402.0>-<324.5,463.0>> = 14.302362220843962 

	* And 24 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] BriemHandwriting-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (756) and hhea ascent (1300) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 275 font units wide, non-breaking space named (uni00A0) is 0 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Briem Handwriting Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.544x (1544) [code: bad-hhea-range]
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

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1 

	- And 80 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0283 (U+0283): L<<140.0,40.0>--<135.0,499.0>> -> L<<135.0,499.0>--<135.0,504.0>>

	* uni0283 (U+0283): L<<202.0,571.0>--<199.0,499.0>> -> L<<199.0,499.0>--<199.0,-28.0>>

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

	* uni20B2 (U+20B2): L<<357.0,-13.0>--<361.0,-13.0>>/B<<361.0,-13.0>-<267.0,-8.0>-<200.5,34.0>> = 3.044778444193999 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[13] BriemHandwriting-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (756) and hhea ascent (1300) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 275 font units wide, non-breaking space named (uni00A0) is 0 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Briem Handwriting Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.544x (1544) [code: bad-hhea-range]
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

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1 

	- And 78 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
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

	* aacute (U+00E1): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* abreve (U+0103): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* adieresis (U+00E4): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* agrave (U+00E0): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* amacron (U+0101): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* aring (U+00E5): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* aringacute (U+01FB): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* atilde (U+00E3): B<<384.0,191.5>-<385.0,212.0>-<386.0,224.0>>/B<<386.0,224.0>-<381.0,205.0>-<363.0,175.5>> = 9.979921145744504

	* b (U+0062): B<<283.0,315.0>-<281.0,284.0>-<281.0,275.0>>/B<<281.0,275.0>-<283.0,295.0>-<300.5,325.5>> = 5.710593137499633 

	* And 136 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] BriemHandwriting-UltraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWeightClass. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/usweightclass">com.google.fonts/check/usweightclass</a>)</summary><div>


* 🔥 **FAIL** OS/2 usWeightClass is '200' when it should be '300'. [code: bad-value]
</div></details><details><summary>🔥 <b>FAIL:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 🔥 **FAIL** Font names are incorrect:

| nameID | current | expected |
| :--- | :--- | :--- |
| Family Name | Briem Handwriting UltraLight | Briem Handwriting UltraLight |
| Subfamily Name | Regular | Regular |
| Full Name | Briem Handwriting UltraLight | Briem Handwriting UltraLight Regular |
| Poscript Name | BriemHandwriting-UltraLight | BriemHandwritingUltraLight-Regular |
| Typographic Family Name | Briem Handwriting | N/A |
| Typographic Subfamily Name | UltraLight | N/A | [code: bad-names]
* ⚠ **WARN** Regular missing from full name [code: lacks-regular]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (756) and hhea ascent (1300) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 275 font units wide, non-breaking space named (uni00A0) is 0 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Briem Handwriting UltraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.544x (1544) [code: bad-hhea-range]
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

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1 

	- And 80 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0283 (U+0283): L<<136.0,48.0>--<131.0,499.0>> -> L<<131.0,499.0>--<131.0,506.0>>

	* uni0283 (U+0283): L<<210.0,568.0>--<207.0,499.0>> -> L<<207.0,499.0>--<206.0,-21.0>>

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

	* uni20B2 (U+20B2): L<<357.0,-13.0>--<361.0,-13.0>>/B<<361.0,-13.0>-<267.0,-8.0>-<200.5,34.0>> = 3.044778444193999 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* f (U+0066): L<<207.0,450.0>--<206.0,-21.0>>

	* germandbls (U+00DF): L<<174.0,553.0>--<173.0,-20.0>>

	* uni0283 (U+0283): L<<207.0,499.0>--<206.0,-21.0>> 

	* And uni1E1F (U+1E1F): L<<207.0,450.0>--<206.0,-21.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] BriemHandwriting-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (756) and hhea ascent (1300) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 275 font units wide, non-breaking space named (uni00A0) is 0 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Briem Handwriting Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.544x (1544) [code: bad-hhea-range]
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

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1 

	- And 80 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0283 (U+0283): L<<131.0,58.0>--<126.0,499.0>> -> L<<126.0,499.0>--<126.0,509.0>>

	* uni0283 (U+0283): L<<219.0,565.0>--<216.0,499.0>> -> L<<216.0,499.0>--<215.0,-13.0>>

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

	* n (U+006E): B<<185.0,199.5>-<183.0,169.0>-<182.0,163.0>>/B<<182.0,163.0>-<198.0,203.0>-<226.5,251.0>> = 12.33908727832618

	* nacute (U+0144): B<<185.0,199.5>-<183.0,169.0>-<182.0,163.0>>/B<<182.0,163.0>-<198.0,203.0>-<226.5,251.0>> = 12.33908727832618

	* ncaron (U+0148): B<<185.0,199.5>-<183.0,169.0>-<182.0,163.0>>/B<<182.0,163.0>-<198.0,203.0>-<226.5,251.0>> = 12.33908727832618

	* ntilde (U+00F1): B<<185.0,199.5>-<183.0,169.0>-<182.0,163.0>>/B<<182.0,163.0>-<198.0,203.0>-<226.5,251.0>> = 12.33908727832618

	* r (U+0072): B<<193.5,284.0>-<192.0,263.0>-<191.0,257.0>>/B<<191.0,257.0>-<224.0,355.0>-<258.0,413.5>> = 9.147842519801692

	* racute (U+0155): B<<193.5,284.0>-<192.0,263.0>-<191.0,257.0>>/B<<191.0,257.0>-<224.0,355.0>-<258.0,413.5>> = 9.147842519801692

	* rcaron (U+0159): B<<193.5,284.0>-<192.0,263.0>-<191.0,257.0>>/B<<191.0,257.0>-<224.0,355.0>-<258.0,413.5>> = 9.147842519801692

	* uni0146 (U+0146): B<<185.0,199.5>-<183.0,169.0>-<182.0,163.0>>/B<<182.0,163.0>-<198.0,203.0>-<226.5,251.0>> = 12.33908727832618

	* uni0157 (U+0157): B<<193.5,284.0>-<192.0,263.0>-<191.0,257.0>>/B<<191.0,257.0>-<224.0,355.0>-<258.0,413.5>> = 9.147842519801692

	* uni01CC (U+01CC): B<<185.0,199.5>-<183.0,169.0>-<182.0,163.0>>/B<<182.0,163.0>-<198.0,203.0>-<226.5,251.0>> = 12.33908727832618 

	* And 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* f (U+0066): L<<217.0,447.0>--<215.0,-13.0>>

	* germandbls (U+00DF): L<<184.0,551.0>--<182.0,-12.0>>

	* uni0283 (U+0283): L<<216.0,499.0>--<215.0,-13.0>> 

	* And uni1E1F (U+1E1F): L<<217.0,447.0>--<215.0,-13.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] BriemHandwriting-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (756) and hhea ascent (1300) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 275 font units wide, non-breaking space named (uni00A0) is 0 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Briem Handwriting Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.544x (1544) [code: bad-hhea-range]
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

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1 

	- And 80 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0283 (U+0283): L<<118.0,84.0>--<113.0,499.0>> -> L<<113.0,499.0>--<113.0,516.0>>

	* uni0283 (U+0283): L<<244.0,556.0>--<243.0,499.0>> -> L<<243.0,499.0>--<239.0,11.0>>

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

	* m (U+006D): B<<213.0,233.5>-<211.0,206.0>-<210.0,197.0>>/B<<210.0,197.0>-<222.0,230.0>-<247.0,273.0>> = 13.642914775990052

	* m (U+006D): B<<548.0,228.5>-<546.0,205.0>-<545.0,197.0>>/B<<545.0,197.0>-<557.0,231.0>-<582.0,274.0>> = 12.315018479274388

	* n (U+006E): B<<211.5,233.5>-<209.0,206.0>-<208.0,197.0>>/B<<208.0,197.0>-<220.0,230.0>-<245.0,273.0>> = 13.642914775990052

	* nacute (U+0144): B<<211.5,233.5>-<209.0,206.0>-<208.0,197.0>>/B<<208.0,197.0>-<220.0,230.0>-<245.0,273.0>> = 13.642914775990052

	* ncaron (U+0148): B<<211.5,233.5>-<209.0,206.0>-<208.0,197.0>>/B<<208.0,197.0>-<220.0,230.0>-<245.0,273.0>> = 13.642914775990052

	* ntilde (U+00F1): B<<211.5,233.5>-<209.0,206.0>-<208.0,197.0>>/B<<208.0,197.0>-<220.0,230.0>-<245.0,273.0>> = 13.642914775990052

	* r (U+0072): B<<220.5,309.0>-<218.0,281.0>-<217.0,269.0>>/B<<217.0,269.0>-<261.0,403.0>-<310.0,463.5>> = 13.41437710769231

	* racute (U+0155): B<<220.5,309.0>-<218.0,281.0>-<217.0,269.0>>/B<<217.0,269.0>-<261.0,403.0>-<310.0,463.5>> = 13.41437710769231

	* rcaron (U+0159): B<<220.5,309.0>-<218.0,281.0>-<217.0,269.0>>/B<<217.0,269.0>-<261.0,403.0>-<310.0,463.5>> = 13.41437710769231

	* uni0146 (U+0146): B<<211.5,233.5>-<209.0,206.0>-<208.0,197.0>>/B<<208.0,197.0>-<220.0,230.0>-<245.0,273.0>> = 13.642914775990052 

	* And 20 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0283 (U+0283): L<<243.0,499.0>--<239.0,11.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[12] BriemHandwriting-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking OS/2 Metrics match hhea Metrics. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/os2_metrics_match_hhea">com.google.fonts/check/os2_metrics_match_hhea</a>)</summary><div>


* 🔥 **FAIL** OS/2 sTypoAscender (756) and hhea ascent (1300) must be equal. [code: ascender]
</div></details><details><summary>🔥 <b>FAIL:</b> Space and non-breaking space have the same width? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_widths">com.google.fonts/check/whitespace_widths</a>)</summary><div>


* 🔥 **FAIL** Space and non-breaking space have differing width: The space glyph named space is 275 font units wide, non-breaking space named (uni00A0) is 0 font units wide, and both should be positive and the same. GlyphsApp has "Sidebearing arithmetic" (https://glyphsapp.com/tutorials/spacing) which allows you to set the non-breaking space width to always equal the space width. [code: different-widths]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Check font follows the Google Fonts vertical metric schema (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vertical_metrics">com.google.fonts/check/vertical_metrics</a>)</summary><div>


* ⚠ **WARN** We recommend the absolute sum of the hhea metrics should be between 1.2-1.5x of the font's upm. This font has 1.544x (1544) [code: bad-hhea-range]
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

	- Glyph name: dcroat	Contours detected: 3	Expected: 2

	- Glyph name: hbar	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni0180	Contours detected: 3	Expected: 2

	- Glyph name: ohorn	Contours detected: 3	Expected: 2

	- Glyph name: Uhorn	Contours detected: 2	Expected: 1

	- Glyph name: uhorn	Contours detected: 2	Expected: 1 

	- And 78 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Does GPOS table have kerning information? This check skips monospaced fonts as defined by post.isFixedPitch value (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gpos.html#com.google.fonts/check/gpos_kerning_info">com.google.fonts/check/gpos_kerning_info</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0283 (U+0283): L<<285.0,543.0>--<284.0,499.0>> -> L<<284.0,499.0>--<276.0,47.0>>

	* uni0283 (U+0283): L<<96.0,126.0>--<91.0,499.0>> -> L<<91.0,499.0>--<91.0,528.0>>

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

	* b (U+0062): B<<262.5,301.5>-<260.0,267.0>-<260.0,254.0>>/B<<260.0,254.0>-<265.0,278.0>-<284.5,312.5>> = 11.768288932020628

	* d (U+0064): B<<390.5,203.0>-<392.0,230.0>-<394.0,249.0>>/B<<394.0,249.0>-<386.0,225.0>-<365.0,191.5>> = 12.425942865427455

	* dcaron (U+010F): B<<390.5,203.0>-<392.0,230.0>-<394.0,249.0>>/B<<394.0,249.0>-<386.0,225.0>-<365.0,191.5>> = 12.425942865427455

	* dcroat (U+0111): B<<390.5,203.0>-<392.0,230.0>-<394.0,249.0>>/B<<394.0,249.0>-<386.0,225.0>-<365.0,191.5>> = 12.425942865427455

	* dong (U+20AB): B<<390.5,203.0>-<392.0,230.0>-<394.0,249.0>>/B<<394.0,249.0>-<386.0,225.0>-<365.0,191.5>> = 12.425942865427455

	* g (U+0067): B<<396.5,197.0>-<396.0,233.0>-<396.0,260.0>>/B<<396.0,260.0>-<390.0,235.0>-<370.0,200.5>> = 13.495733280795811

	* gbreve (U+011F): B<<396.5,197.0>-<396.0,233.0>-<396.0,260.0>>/B<<396.0,260.0>-<390.0,235.0>-<370.0,200.5>> = 13.495733280795811

	* gcaron (U+01E7): B<<396.5,197.0>-<396.0,233.0>-<396.0,260.0>>/B<<396.0,260.0>-<390.0,235.0>-<370.0,200.5>> = 13.495733280795811

	* gcircumflex (U+011D): B<<396.5,197.0>-<396.0,233.0>-<396.0,260.0>>/B<<396.0,260.0>-<390.0,235.0>-<370.0,200.5>> = 13.495733280795811

	* gdotaccent (U+0121): B<<396.5,197.0>-<396.0,233.0>-<396.0,260.0>>/B<<396.0,260.0>-<390.0,235.0>-<370.0,200.5>> = 13.495733280795811 

	* And 102 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 18 | 90 | 886 | 49 | 668 | 0 |
| 0% | 1% | 5% | 52% | 3% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
