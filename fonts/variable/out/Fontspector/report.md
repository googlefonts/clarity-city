## FontSpector report

fontspector version: 1.7.1






## Check results




<details><summary>[6] </summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 usWinAscent & usWinDescent (family/win_ascent_and_descent)</summary>
    <div>








- 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 965, but got 795 instead. [code: ascent]
  
  


- 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 277, but got 205 instead. [code: descent]
  
  


- 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 965, but got 795 instead. [code: ascent]
  
  


- 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 277, but got 205 instead. [code: descent]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Copyright notices match canonical pattern in fonts (googlefonts/font_copyright)</summary>
    <div>








- 🔥 **FAIL** ClarityCity-Italic[wght].ttf: Name Table entry: Copyright notices should match a pattern similar to:

"Copyright 2020 The Familyname Project Authors (git url)"

But instead we have got:

"copyright (c) 2019 vmware, inc.	" [code: bad-notice-format]
  
  


- 🔥 **FAIL** ClarityCity[wght].ttf: Name Table entry: Copyright notices should match a pattern similar to:

"Copyright 2020 The Familyname Project Authors (git url)"

But instead we have got:

"copyright (c) 2019 vmware, inc.	" [code: bad-notice-format]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check Google Fonts glyph coverage. (googlefonts/glyph_coverage)</summary>
    <div>








- 🔥 **FAIL** ClarityCity-Italic[wght].ttf missing required codepoints:

* 0x00A0: NO-BREAK SPACE
* 0x00A7: SECTION SIGN
* 0x00AA: FEMININE ORDINAL INDICATOR
* 0x00B0: DEGREE SIGN
* 0x00BA: MASCULINE ORDINAL INDICATOR
* 0x010A: LATIN CAPITAL LETTER C WITH DOT ABOVE
* 0x010B: LATIN SMALL LETTER C WITH DOT ABOVE
* 0x0120: LATIN CAPITAL LETTER G WITH DOT ABOVE
* 0x0121: LATIN SMALL LETTER G WITH DOT ABOVE
... and 22 others [code: missing-codepoints]
  
  


- 🔥 **FAIL** ClarityCity[wght].ttf missing required codepoints:

* 0x00A0: NO-BREAK SPACE
* 0x00A7: SECTION SIGN
* 0x00AA: FEMININE ORDINAL INDICATOR
* 0x00B0: DEGREE SIGN
* 0x00BA: MASCULINE ORDINAL INDICATOR
* 0x010A: LATIN CAPITAL LETTER C WITH DOT ABOVE
* 0x010B: LATIN SMALL LETTER C WITH DOT ABOVE
* 0x0120: LATIN CAPITAL LETTER G WITH DOT ABOVE
* 0x0121: LATIN SMALL LETTER G WITH DOT ABOVE
... and 22 others [code: missing-codepoints]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. (googlefonts/metadata/unreachable_subsetting)</summary>
    <div>








- ⚠️ **WARN** ClarityCity-Italic[wght].ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
* U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
* U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, coptic, math, todhri, tifinagh, duployan, syriac, canadian-aboriginal, hebrew, malayalam, tai-le
* U+0326 COMBINING COMMA BELOW: try adding math
* U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
* U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
... and 6 others

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin [code: unreachable-subsetting]
  
  


- ⚠️ **WARN** ClarityCity[wght].ttf: The following codepoints supported by the font are not covered by any subsets defined in the font's metadata file, and will never be served. You can solve this by either manually adding additional subset declarations to METADATA.pb, or by editing the glyphset definitions.

* U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
* U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
* U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
* U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, coptic, math, todhri, tifinagh, duployan, syriac, canadian-aboriginal, hebrew, malayalam, tai-le
* U+0326 COMBINING COMMA BELOW: try adding math
* U+1EB8 LATIN CAPITAL LETTER E WITH DOT BELOW: try adding vietnamese
* U+1EB9 LATIN SMALL LETTER E WITH DOT BELOW: try adding vietnamese
* U+1EBC LATIN CAPITAL LETTER E WITH TILDE: try adding vietnamese
* U+1EBD LATIN SMALL LETTER E WITH TILDE: try adding vietnamese
... and 6 others

Or you can add the above codepoints to one of the subsets supported by the font: latin-ext, latin [code: unreachable-subsetting]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Check for presence of an ARTICLE.en_us.html file (googlefonts/description/has_article)</summary>
    <div>








- ℹ️ **INFO** This font doesn't have an ARTICLE.en_us.html file. [code: missing-article]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Check axis ordering on the STAT table. (googlefonts/STAT/axis_order)</summary>
    <div>








- ℹ️ **INFO** None of the fonts lack a STAT table.

	And these are the most common STAT axis orderings:
	wght-ital: 2 [code: summary]
  
  

</div>
</details>


</div>
</details>


<details><summary>[26] ClarityCity-Italic[wght].ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Check glyphs do not have duplicate components which have the same x,y coordinates. (opentype/glyf_non_transformed_duplicate_components)</summary>
    <div>








- 🔥 **FAIL** quotedblbase: duplicate component comma at 0,0. Duplicate components may cause rendering issues. [code: found-duplicates]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. (name/trailing_spaces)</summary>
    <div>








- 🔥 **FAIL** Name table record 3/1/1033/COPYRIGHT_NOTICE has trailing spaces that must be removed:
`Copyright (c) 2019 VMware, Inc.	` [code: trailing-space]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Font contains glyphs for whitespace characters? (whitespace_glyphs)</summary>
    <div>








- 🔥 **FAIL** Whitespace glyph missing for codepoint 0x00A0 [code: missing-whitespace-glyph-0x00A0]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- 🔥 **FAIL** Failed language shaping:

| Message                                                                             | Languages                    |
|-------------------------------------------------------------------------------------|------------------------------|
| Mandatory orthography codepoints:                                                   | * hu_Latn (Hungarian)        |
|   The following mark characters are missing from the font: ̈, ̋, ́                     |                              |
| Mandatory orthography codepoints:                                                   | * fi_Latn (Finnish)          |
|   The following mark characters are missing from the font: ̌, ̈, ̊, ̃                   |                              |
| Mandatory orthography codepoints:                                                   | * sk_Latn (Slovak)           |
|   The following mark characters are missing from the font: ̈, ́, ̌, ̂                   |                              |
| Mandatory orthography codepoints:                                                   | * it_Latn (Italian)          |
|   The following mark characters are missing from the font: ̈, ̂, ́, ̀                   |                              |
| Mandatory orthography codepoints:                                                   | * ca_Latn (Catalan)          |
|   The following mark characters are missing from the font: ̀, ́, ̈, ̧                   |                              |
| Mandatory orthography codepoints:                                                   | * fr_Latn (French)           |
|   The following mark characters are missing from the font: ́, ̂, ̀, ̈, ̧                 |                              |
| Mandatory orthography codepoints:                                                   | * hr_Latn (Croatian)         |
|   The following mark characters are missing from the font: ̌, ́                       |                              |
| Mandatory orthography codepoints:                                                   | * lt_Latn (Lithuanian)       |
|   The following mark characters are missing from the font: ̄, ̌, ̨                     |                              |
| Mandatory orthography codepoints:                                                   | * nl_Latn (Dutch)            |
|   The following base characters are missing from the font: íj́, ÍJ́                   |                              |
|   The following mark characters are missing from the font: ̈, ̀, ̂, ́                   |                              |
| Mandatory orthography codepoints:                                                   | * en_Latn (English)          |
|   The following mark characters are missing from the font: ̂, ̈, ̀, ̧, ́, ̃               |                              |
| Mandatory orthography codepoints:                                                   | * nb_Latn (Norwegian Bokmål) |
|   The following mark characters are missing from the font: ̂, ̈, ̀, ́, ̊                 |                              |
| Mandatory orthography codepoints:                                                   | * is_Latn (Icelandic)        |
|   The following mark characters are missing from the font: ̈, ́, ̨                     |                              |
| Mandatory orthography codepoints:                                                   | * tr_Latn (Turkish)          |
|   The following mark characters are missing from the font: ̂, ̧, ̈, ̆                   |                              |
| Mandatory orthography codepoints:                                                   | * cs_Latn (Czech)            |
|   The following mark characters are missing from the font: ̊, ̌, ́                     |                              |
| Mandatory orthography codepoints:                                                   | * cy_Latn (Welsh)            |
|   The following mark characters are missing from the font: ̂, ̈, ̀, ́                   |                              |
| Mandatory orthography codepoints:                                                   | * pl_Latn (Polish)           |
|   The following mark characters are missing from the font: ̨, ́                       |                              |
| Mandatory orthography codepoints:                                                   | * da_Latn (Danish)           |
|   The following mark characters are missing from the font: ̊, ́                       |                              |
| Mandatory orthography codepoints:                                                   | * sv_Latn (Swedish)          |
|   The following mark characters are missing from the font: ́, ̊, ̈, ̀                   |                              |
| Mandatory orthography codepoints:                                                   | * mt_Latn (Maltese)          |
|   The following base characters are missing from the font: ċ, għ, Ħ, Ċ, Ġ, GĦ, ġ, ħ |                              |
|   The following mark characters are missing from the font: ̂, ̀                       |                              |
| Mandatory orthography codepoints:                                                   | * ro_Latn (Romanian)         |
|   The following base characters are missing from the font: Ț, ș, Ș, ț               |                              |
|   The following mark characters are missing from the font: ̂, ̆, ̧                     |                              |
| Mandatory orthography codepoints:                                                   | * sq_Latn (Albanian)         |
|   The following mark characters are missing from the font: ̧, ̈                       |                              |
| Mandatory orthography codepoints:                                                   | * de_Latn (German)           |
|   The following base characters are missing from the font: ẞ                        |                              |
|   The following mark characters are missing from the font: ̈, ̀, ́                     |                              |
| Mandatory orthography codepoints:                                                   | * es_Latn (Spanish)          |
|   The following mark characters are missing from the font: ̃, ̈, ́                     |                              |
| Mandatory orthography codepoints:                                                   | * lv_Latn (Latvian)          |
|   The following base characters are missing from the font: Ļ, ļ                     |                              |
|   The following mark characters are missing from the font: ̧, ̌, ̄                     |                              |
| Mandatory orthography codepoints:                                                   | * pt_Latn (Portuguese)       |
|   The following mark characters are missing from the font: ̂, ̈, ̧, ̀, ̃, ́               |                              | [code: failed-language-shaping]
  
  


- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages                    |
|-------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                 | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ǎ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: ǎ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
| Auxiliary orthography codepoints:                                 | * tr_Latn (Turkish)          |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: ẞ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * lt_Latn (Lithuanian)       |
|   The following auxiliary characters are missing from the font: Ą́ |                              |
|   The following auxiliary characters are missing from the font: Ą̃ |                              |
|   The following auxiliary characters are missing from the font: Ę́ |                              |
|   The following auxiliary characters are missing from the font: Ę̃ |                              |
|   The following auxiliary characters are missing from the font: Ė́ |                              |
|   The following auxiliary characters are missing from the font: Ė̃ |                              |
|   The following auxiliary characters are missing from the font: İ́ |                              |
|   The following auxiliary characters are missing from the font: İ́ |                              |
|   The following auxiliary characters are missing from the font: İ̀ |                              |
|   The following auxiliary characters are missing from the font: İ̀ |                              |
|   The following auxiliary characters are missing from the font: İ̃ |                              |
|   The following auxiliary characters are missing from the font: İ̃ |                              |
|   The following auxiliary characters are missing from the font: Ĩ |                              |
|   The following auxiliary characters are missing from the font: Į́ |                              |
|   The following auxiliary characters are missing from the font: Į̇́ |                              |
|   The following auxiliary characters are missing from the font: Į̃ |                              |
|   The following auxiliary characters are missing from the font: Į̇̃ |                              |
|   The following auxiliary characters are missing from the font: J̃ |                              |
|   The following auxiliary characters are missing from the font: J̇̃ |                              |
|   The following auxiliary characters are missing from the font: L̃ |                              |
|   The following auxiliary characters are missing from the font: M̃ |                              |
|   The following auxiliary characters are missing from the font: R̃ |                              |
|   The following auxiliary characters are missing from the font: Ũ |                              |
|   The following auxiliary characters are missing from the font: Ų́ |                              |
|   The following auxiliary characters are missing from the font: Ų̃ |                              |
|   The following auxiliary characters are missing from the font: Ū́ |                              |
|   The following auxiliary characters are missing from the font: Ū̃ |                              |
|   The following auxiliary characters are missing from the font: ą́ |                              |
|   The following auxiliary characters are missing from the font: ą̃ |                              |
|   The following auxiliary characters are missing from the font: ę́ |                              |
|   The following auxiliary characters are missing from the font: ę̃ |                              |
|   The following auxiliary characters are missing from the font: ė́ |                              |
|   The following auxiliary characters are missing from the font: ė̃ |                              |
|   The following auxiliary characters are missing from the font: i̇́ |                              |
|   The following auxiliary characters are missing from the font: i̇̀ |                              |
|   The following auxiliary characters are missing from the font: i̇̃ |                              |
|   The following auxiliary characters are missing from the font: ĩ |                              |
|   The following auxiliary characters are missing from the font: į́ |                              |
|   The following auxiliary characters are missing from the font: į̇́ |                              |
|   The following auxiliary characters are missing from the font: į̃ |                              |
|   The following auxiliary characters are missing from the font: į̇̃ |                              |
|   The following auxiliary characters are missing from the font: j̃ |                              |
|   The following auxiliary characters are missing from the font: j̇̃ |                              |
|   The following auxiliary characters are missing from the font: l̃ |                              |
|   The following auxiliary characters are missing from the font: m̃ |                              |
|   The following auxiliary characters are missing from the font: r̃ |                              |
|   The following auxiliary characters are missing from the font: ũ |                              |
|   The following auxiliary characters are missing from the font: ų́ |                              |
|   The following auxiliary characters are missing from the font: ų̃ |                              |
|   The following auxiliary characters are missing from the font: ū́ |                              |
|   The following auxiliary characters are missing from the font: ū̃ |                              |
|   Shaper didn't attach uni0307 to J when shaping the text 'J̇̃'     |                              |
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)          |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŀ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŀ |                              |
|   The following auxiliary characters are missing from the font: º |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * en_Latn (English)          |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
|   The following auxiliary characters are missing from the font: ʻ |                              |
| Auxiliary orthography codepoints:                                 | * it_Latn (Italian)          |
|   The following auxiliary characters are missing from the font: ª |                              |
|   The following auxiliary characters are missing from the font: ẞ |                              |
|   The following auxiliary characters are missing from the font: º |                              |
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)           |
|   The following auxiliary characters are missing from the font: ẞ |                              |
|   The following auxiliary characters are missing from the font: Ǔ |                              |
|   The following auxiliary characters are missing from the font: ſ |                              |
|   The following auxiliary characters are missing from the font: ǔ |                              |
| Auxiliary orthography codepoints:                                 | * nl_Latn (Dutch)            |
|   The following auxiliary characters are missing from the font: Ĳ |                              |
|   The following auxiliary characters are missing from the font: ĳ |                              |
| Auxiliary orthography codepoints:                                 | * cs_Latn (Czech)            |
|   The following auxiliary characters are missing from the font: Ĕ | * cy_Latn (Welsh)            |
|   The following auxiliary characters are missing from the font: Ĭ | * hu_Latn (Hungarian)        |
|   The following auxiliary characters are missing from the font: Ŏ | * sk_Latn (Slovak)           |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * es_Latn (Spanish)          |
|   The following auxiliary characters are missing from the font: Ĕ | * pt_Latn (Portuguese)       |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ª |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: º |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * da_Latn (Danish)           |
|   The following auxiliary characters are missing from the font: Ǿ |                              |
|   The following auxiliary characters are missing from the font: ǿ |                              |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ċ |                              |
|   The following auxiliary characters are missing from the font: Ǧ |                              |
|   The following auxiliary characters are missing from the font: Ǥ |                              |
|   The following auxiliary characters are missing from the font: Ȟ |                              |
|   The following auxiliary characters are missing from the font: Ħ |                              |
|   The following auxiliary characters are missing from the font: Ǩ |                              |
|   The following auxiliary characters are missing from the font: Ļ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŝ |                              |
|   The following auxiliary characters are missing from the font: Ș |                              |
|   The following auxiliary characters are missing from the font: ẞ |                              |
|   The following auxiliary characters are missing from the font: Ț |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: Ʒ |                              |
|   The following auxiliary characters are missing from the font: Ǯ |                              |
|   The following auxiliary characters are missing from the font: ċ |                              |
|   The following auxiliary characters are missing from the font: ǧ |                              |
|   The following auxiliary characters are missing from the font: ǥ |                              |
|   The following auxiliary characters are missing from the font: ȟ |                              |
|   The following auxiliary characters are missing from the font: ħ |                              |
|   The following auxiliary characters are missing from the font: ǩ |                              |
|   The following auxiliary characters are missing from the font: ļ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŝ |                              |
|   The following auxiliary characters are missing from the font: ș |                              |
|   The following auxiliary characters are missing from the font: ț |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
|   The following auxiliary characters are missing from the font: ʒ |                              |
|   The following auxiliary characters are missing from the font: ǯ |                              |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ſ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * pl_Latn (Polish)           |
|   The following auxiliary characters are missing from the font: ẞ |                              | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 fsType does not impose restrictions. (googlefonts/fstype)</summary>
    <div>








- 🔥 **FAIL** In this font fsType is set to 8 meaning that:
* The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check a font's STAT table contains compulsory Axis Values. (googlefonts/STAT/compulsory_axis_values)</summary>
    <div>








- 🔥 **FAIL** Compulsory STAT Axis Values are incorrect:

| Name       | Axis | Current Value | Expected Value | Current Flags | Expected Flags | Current Linked Value | Expected Linked Value |
|------------|------|---------------|----------------|---------------|----------------|----------------------|-----------------------|
| Black      | wght | N/A           | 900            | N/A           | 0              | N/A                  | N/A                   |
| Bold       | wght | 700           | 700            | 0             | 0              | N/A                  | N/A                   |
| ExtraBold  | wght | 800           | 800            | 0             | 0              | N/A                  | N/A                   |
| ExtraLight | wght | 200           | 200            | 0             | 0              | N/A                  | N/A                   |
| Light      | wght | 300           | 300            | 0             | 0              | N/A                  | N/A                   |
| Medium     | wght | 500           | 500            | 0             | 0              | N/A                  | N/A                   |
| Regular    | wght | 400           | 400            | 2             | 2              | 700                  | 700                   |
| SemiBold   | wght | 600           | 600            | 0             | 0              | N/A                  | N/A                   |
| Thin       | wght | N/A           | 100            | N/A           | 0              | N/A                  | N/A                   |

 [code: bad-axis-values]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (googlefonts/use_typo_metrics)</summary>
    <div>








- 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) was NOT set. [code: missing-os2-fsselection-bit7]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema (googlefonts/vertical_metrics)</summary>
    <div>








- 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1000 when it should be at least 1200 [code: bad-hhea-range]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? (gpos_kerning_info)</summary>
    <div>








- ⚠️ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. (mandatory_avar_table)</summary>
    <div>








- ⚠️ **WARN** The font does not include an avar table.  If the progression rates of axes is linear and no user-mapping is expected, this is fine, and this check can be ignored or excluded. [code: missing-avar]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 594 among a set of 7  math glyphs.
The following math glyphs have a different width, though:
width=534: multiply
width=718: minus
width=593: less
width=590: plus
width=592: greater
width=720: equal [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking that the typoAscender exceeds the yMax of the /Agrave. (typoascender_exceeds_Agrave)</summary>
    <div>








- ⚠️ **WARN** OS/2.sTypoAscender value should be greater than 890, but got 795 instead [code: typoAscender]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* aacute.alt
* abreve.alt
* acircumflex.alt
* adieresis.alt
* agrave.alt
* amacron.alt
* aogonek.alt
* aring.alt
* atilde.alt [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̇ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check the direction of the outermost contour in each glyph (outline_direction)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have a counter-clockwise outer contour:

* X (U+0058) has a counter-clockwise outer contour [code: ccw-outer-contour]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* quotedblbase (U+201E): Line(Line { p0: (61.0, -135.0), p1: (26.0, -103.0) }) has the same coordinates as a previous segment.
* quotedblbase (U+201E): Quad(QuadBez { p0: (26.0, -103.0), p1: (52.0, -80.0), p2: (70.0, -56.0) }) has the same coordinates as a previous segment.
* quotedblbase (U+201E): Quad(QuadBez { p0: (70.0, -56.0), p1: (88.0, -32.0), p2: (101.0, -9.0) }) has the same coordinates as a previous segment.
* quotedblbase (U+201E): Quad(QuadBez { p0: (101.0, -9.0), p1: (82.0, -9.0), p2: (69.5, 3.5) }) has the same coordinates as a previous segment.
* quotedblbase (U+201E): Quad(QuadBez { p0: (69.5, 3.5), p1: (57.0, 16.0), p2: (57.0, 36.0) }) has the same coordinates as a previous segment.
* quotedblbase (U+201E): Quad(QuadBez { p0: (57.0, 36.0), p1: (57.0, 55.0), p2: (66.0, 68.0) }) has the same coordinates as a previous segment.
* quotedblbase (U+201E): Quad(QuadBez { p0: (66.0, 68.0), p1: (75.0, 81.0), p2: (88.5, 88.5) }) has the same coordinates as a previous segment.
* quotedblbase (U+201E): Quad(QuadBez { p0: (88.5, 88.5), p1: (102.0, 96.0), p2: (117.0, 96.0) }) has the same coordinates as a previous segment.
* quotedblbase (U+201E): Quad(QuadBez { p0: (117.0, 96.0), p1: (143.0, 96.0), p2: (156.0, 79.0) }) has the same coordinates as a previous segment.
... and 4 others [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'NONE' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Checking OS/2 fsSelection value. (opentype/xavgcharwidth)</summary>
    <div>








- ℹ️ **INFO** OS/2 xAvgCharWidth is 588 but it should be 587 which corresponds to the average of the widths of all glyphs in the font. These are similar values, which may be a symptom of the slightly different calculation of the xAvgCharWidth value in font editors. There's further discussion on this at https://github.com/fonttools/fontbakery/issues/1622 [code: xAvgCharWidth-close]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. (hinting_impact)</summary>
    <div>








- ℹ️ **INFO** Hinting filesize impact:

 |               | ClarityCity-Italic[wght].ttf     |
 |:------------- | ---------------:|
 | Dehinted Size | 52436 |
 | Hinted Size   | 52460   |
 | Increase      | 24      |
 | Change        | 0.0 %  | [code: size-impact]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? (required_tables)</summary>
    <div>








- ℹ️ **INFO** This font contains the following optional tables:

    loca
    prep
    GPOS
    GSUB
    gasp [code: optional-tables]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table
set to optimize rendering? (googlefonts/gasp)</summary>
    <div>








- ℹ️ **INFO** These are the ppm ranges declared on the gasp table:

| PPM <= 65535 | - Use grid-fitting                                    |
|              | 	- Use grayscale rendering                            |
|              | 	- Use gridfitting with ClearType symmetric smoothing |
|              | 	- Use smoothing along multiple axes with ClearType®  |
|--------------|-------------------------------------------------------|
 [code: ranges]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? (googlefonts/old_ttfautohint)</summary>
    <div>








- ℹ️ **INFO** Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: Version 1.000 [code: version-not-detected]
  
  

</div>
</details>


</div>
</details>


<details><summary>[27] ClarityCity[wght].ttf</summary>
<div>


<details>
    <summary>🔥 <b>FAIL</b> Name table records must not have trailing spaces. (name/trailing_spaces)</summary>
    <div>








- 🔥 **FAIL** Name table record 3/1/1033/COPYRIGHT_NOTICE has trailing spaces that must be removed:
`Copyright (c) 2019 VMware, Inc.	` [code: trailing-space]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Font contains glyphs for whitespace characters? (whitespace_glyphs)</summary>
    <div>








- 🔥 **FAIL** Whitespace glyph missing for codepoint 0x00A0 [code: missing-whitespace-glyph-0x00A0]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. (googlefonts/glyphsets/shape_languages)</summary>
    <div>








- 🔥 **FAIL** Failed language shaping:

| Message                                                                             | Languages                    |
|-------------------------------------------------------------------------------------|------------------------------|
| Mandatory orthography codepoints:                                                   | * ro_Latn (Romanian)         |
|   The following base characters are missing from the font: ș, Ș, Ț, ț               |                              |
|   The following mark characters are missing from the font: ̆, ̧, ̂                     |                              |
| Mandatory orthography codepoints:                                                   | * tr_Latn (Turkish)          |
|   The following mark characters are missing from the font: ̈, ̆, ̧, ̂                   |                              |
| Mandatory orthography codepoints:                                                   | * sv_Latn (Swedish)          |
|   The following mark characters are missing from the font: ̊, ̀, ́, ̈                   |                              |
| Mandatory orthography codepoints:                                                   | * it_Latn (Italian)          |
|   The following mark characters are missing from the font: ́, ̀, ̂, ̈                   |                              |
| Mandatory orthography codepoints:                                                   | * nl_Latn (Dutch)            |
|   The following base characters are missing from the font: ÍJ́, íj́                   |                              |
|   The following mark characters are missing from the font: ̀, ́, ̈, ̂                   |                              |
| Mandatory orthography codepoints:                                                   | * cs_Latn (Czech)            |
|   The following mark characters are missing from the font: ̊, ̌, ́                     |                              |
| Mandatory orthography codepoints:                                                   | * lv_Latn (Latvian)          |
|   The following base characters are missing from the font: Ļ, ļ                     |                              |
|   The following mark characters are missing from the font: ̧, ̄, ̌                     |                              |
| Mandatory orthography codepoints:                                                   | * cy_Latn (Welsh)            |
|   The following mark characters are missing from the font: ̂, ̀, ́, ̈                   |                              |
| Mandatory orthography codepoints:                                                   | * hr_Latn (Croatian)         |
|   The following mark characters are missing from the font: ́, ̌                       |                              |
| Mandatory orthography codepoints:                                                   | * sk_Latn (Slovak)           |
|   The following mark characters are missing from the font: ́, ̌, ̂, ̈                   |                              |
| Mandatory orthography codepoints:                                                   | * nb_Latn (Norwegian Bokmål) |
|   The following mark characters are missing from the font: ̊, ̀, ̂, ́, ̈                 |                              |
| Mandatory orthography codepoints:                                                   | * pl_Latn (Polish)           |
|   The following mark characters are missing from the font: ̨, ́                       |                              |
| Mandatory orthography codepoints:                                                   | * da_Latn (Danish)           |
|   The following mark characters are missing from the font: ́, ̊                       |                              |
| Mandatory orthography codepoints:                                                   | * fi_Latn (Finnish)          |
|   The following mark characters are missing from the font: ̃, ̌, ̈, ̊                   |                              |
| Mandatory orthography codepoints:                                                   | * hu_Latn (Hungarian)        |
|   The following mark characters are missing from the font: ̋, ́, ̈                     |                              |
| Mandatory orthography codepoints:                                                   | * de_Latn (German)           |
|   The following base characters are missing from the font: ẞ                        |                              |
|   The following mark characters are missing from the font: ̈, ̀, ́                     |                              |
| Mandatory orthography codepoints:                                                   | * en_Latn (English)          |
|   The following mark characters are missing from the font: ̃, ̈, ̧, ́, ̂, ̀               |                              |
| Mandatory orthography codepoints:                                                   | * lt_Latn (Lithuanian)       |
|   The following mark characters are missing from the font: ̨, ̄, ̌                     |                              |
| Mandatory orthography codepoints:                                                   | * mt_Latn (Maltese)          |
|   The following base characters are missing from the font: Ħ, ċ, għ, GĦ, Ċ, ġ, ħ, Ġ |                              |
|   The following mark characters are missing from the font: ̂, ̀                       |                              |
| Mandatory orthography codepoints:                                                   | * ca_Latn (Catalan)          |
|   The following mark characters are missing from the font: ̀, ́, ̈, ̧                   |                              |
| Mandatory orthography codepoints:                                                   | * is_Latn (Icelandic)        |
|   The following mark characters are missing from the font: ̨, ́, ̈                     |                              |
| Mandatory orthography codepoints:                                                   | * pt_Latn (Portuguese)       |
|   The following mark characters are missing from the font: ́, ̈, ̀, ̂, ̃, ̧               |                              |
| Mandatory orthography codepoints:                                                   | * sq_Latn (Albanian)         |
|   The following mark characters are missing from the font: ̧, ̈                       |                              |
| Mandatory orthography codepoints:                                                   | * es_Latn (Spanish)          |
|   The following mark characters are missing from the font: ̃, ́, ̈                     |                              |
| Mandatory orthography codepoints:                                                   | * fr_Latn (French)           |
|   The following mark characters are missing from the font: ́, ̈, ̂, ̀, ̧                 |                              | [code: failed-language-shaping]
  
  


- ⚠️ **WARN** Warning language shaping:

| Message                                                           | Languages                    |
|-------------------------------------------------------------------|------------------------------|
| Auxiliary orthography codepoints:                                 | * fr_Latn (French)           |
|   The following auxiliary characters are missing from the font: ẞ |                              |
|   The following auxiliary characters are missing from the font: Ǔ |                              |
|   The following auxiliary characters are missing from the font: ſ |                              |
|   The following auxiliary characters are missing from the font: ǔ |                              |
| Auxiliary orthography codepoints:                                 | * lt_Latn (Lithuanian)       |
|   The following auxiliary characters are missing from the font: Ą́ |                              |
|   The following auxiliary characters are missing from the font: Ą̃ |                              |
|   The following auxiliary characters are missing from the font: Ę́ |                              |
|   The following auxiliary characters are missing from the font: Ę̃ |                              |
|   The following auxiliary characters are missing from the font: Ė́ |                              |
|   The following auxiliary characters are missing from the font: Ė̃ |                              |
|   The following auxiliary characters are missing from the font: İ́ |                              |
|   The following auxiliary characters are missing from the font: İ́ |                              |
|   The following auxiliary characters are missing from the font: İ̀ |                              |
|   The following auxiliary characters are missing from the font: İ̀ |                              |
|   The following auxiliary characters are missing from the font: İ̃ |                              |
|   The following auxiliary characters are missing from the font: İ̃ |                              |
|   The following auxiliary characters are missing from the font: Ĩ |                              |
|   The following auxiliary characters are missing from the font: Į́ |                              |
|   The following auxiliary characters are missing from the font: Į̇́ |                              |
|   The following auxiliary characters are missing from the font: Į̃ |                              |
|   The following auxiliary characters are missing from the font: Į̇̃ |                              |
|   The following auxiliary characters are missing from the font: J̃ |                              |
|   The following auxiliary characters are missing from the font: J̇̃ |                              |
|   The following auxiliary characters are missing from the font: L̃ |                              |
|   The following auxiliary characters are missing from the font: M̃ |                              |
|   The following auxiliary characters are missing from the font: R̃ |                              |
|   The following auxiliary characters are missing from the font: Ũ |                              |
|   The following auxiliary characters are missing from the font: Ų́ |                              |
|   The following auxiliary characters are missing from the font: Ų̃ |                              |
|   The following auxiliary characters are missing from the font: Ū́ |                              |
|   The following auxiliary characters are missing from the font: Ū̃ |                              |
|   The following auxiliary characters are missing from the font: ą́ |                              |
|   The following auxiliary characters are missing from the font: ą̃ |                              |
|   The following auxiliary characters are missing from the font: ę́ |                              |
|   The following auxiliary characters are missing from the font: ę̃ |                              |
|   The following auxiliary characters are missing from the font: ė́ |                              |
|   The following auxiliary characters are missing from the font: ė̃ |                              |
|   The following auxiliary characters are missing from the font: i̇́ |                              |
|   The following auxiliary characters are missing from the font: i̇̀ |                              |
|   The following auxiliary characters are missing from the font: i̇̃ |                              |
|   The following auxiliary characters are missing from the font: ĩ |                              |
|   The following auxiliary characters are missing from the font: į́ |                              |
|   The following auxiliary characters are missing from the font: į̇́ |                              |
|   The following auxiliary characters are missing from the font: į̃ |                              |
|   The following auxiliary characters are missing from the font: į̇̃ |                              |
|   The following auxiliary characters are missing from the font: j̃ |                              |
|   The following auxiliary characters are missing from the font: j̇̃ |                              |
|   The following auxiliary characters are missing from the font: l̃ |                              |
|   The following auxiliary characters are missing from the font: m̃ |                              |
|   The following auxiliary characters are missing from the font: r̃ |                              |
|   The following auxiliary characters are missing from the font: ũ |                              |
|   The following auxiliary characters are missing from the font: ų́ |                              |
|   The following auxiliary characters are missing from the font: ų̃ |                              |
|   The following auxiliary characters are missing from the font: ū́ |                              |
|   The following auxiliary characters are missing from the font: ū̃ |                              |
|   Shaper didn't attach uni0307 to J when shaping the text 'J̇̃'     |                              |
| Auxiliary orthography codepoints:                                 | * en_Latn (English)          |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
|   The following auxiliary characters are missing from the font: ʻ |                              |
| Auxiliary orthography codepoints:                                 | * es_Latn (Spanish)          |
|   The following auxiliary characters are missing from the font: Ĕ | * pt_Latn (Portuguese)       |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ª |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: º |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * nl_Latn (Dutch)            |
|   The following auxiliary characters are missing from the font: Ĳ |                              |
|   The following auxiliary characters are missing from the font: ĳ |                              |
| Auxiliary orthography codepoints:                                 | * pl_Latn (Polish)           |
|   The following auxiliary characters are missing from the font: ẞ |                              |
| Auxiliary orthography codepoints:                                 | * it_Latn (Italian)          |
|   The following auxiliary characters are missing from the font: ª |                              |
|   The following auxiliary characters are missing from the font: ẞ |                              |
|   The following auxiliary characters are missing from the font: º |                              |
| Auxiliary orthography codepoints:                                 | * tr_Latn (Turkish)          |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: ẞ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * ca_Latn (Catalan)          |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŀ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŀ |                              |
|   The following auxiliary characters are missing from the font: º |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * nb_Latn (Norwegian Bokmål) |
|   The following auxiliary characters are missing from the font: Ǎ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: ǎ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
| Auxiliary orthography codepoints:                                 | * cs_Latn (Czech)            |
|   The following auxiliary characters are missing from the font: Ĕ | * cy_Latn (Welsh)            |
|   The following auxiliary characters are missing from the font: Ĭ | * hu_Latn (Hungarian)        |
|   The following auxiliary characters are missing from the font: Ŏ | * sk_Latn (Slovak)           |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              |
| Auxiliary orthography codepoints:                                 | * da_Latn (Danish)           |
|   The following auxiliary characters are missing from the font: Ǿ |                              |
|   The following auxiliary characters are missing from the font: ǿ |                              |
| Auxiliary orthography codepoints:                                 | * fi_Latn (Finnish)          |
|   The following auxiliary characters are missing from the font: Ċ |                              |
|   The following auxiliary characters are missing from the font: Ǧ |                              |
|   The following auxiliary characters are missing from the font: Ǥ |                              |
|   The following auxiliary characters are missing from the font: Ȟ |                              |
|   The following auxiliary characters are missing from the font: Ħ |                              |
|   The following auxiliary characters are missing from the font: Ǩ |                              |
|   The following auxiliary characters are missing from the font: Ļ |                              |
|   The following auxiliary characters are missing from the font: Ŋ |                              |
|   The following auxiliary characters are missing from the font: Ŝ |                              |
|   The following auxiliary characters are missing from the font: Ș |                              |
|   The following auxiliary characters are missing from the font: ẞ |                              |
|   The following auxiliary characters are missing from the font: Ț |                              |
|   The following auxiliary characters are missing from the font: Ŧ |                              |
|   The following auxiliary characters are missing from the font: Ʒ |                              |
|   The following auxiliary characters are missing from the font: Ǯ |                              |
|   The following auxiliary characters are missing from the font: ċ |                              |
|   The following auxiliary characters are missing from the font: ǧ |                              |
|   The following auxiliary characters are missing from the font: ǥ |                              |
|   The following auxiliary characters are missing from the font: ȟ |                              |
|   The following auxiliary characters are missing from the font: ħ |                              |
|   The following auxiliary characters are missing from the font: ǩ |                              |
|   The following auxiliary characters are missing from the font: ļ |                              |
|   The following auxiliary characters are missing from the font: ŋ |                              |
|   The following auxiliary characters are missing from the font: ŝ |                              |
|   The following auxiliary characters are missing from the font: ș |                              |
|   The following auxiliary characters are missing from the font: ț |                              |
|   The following auxiliary characters are missing from the font: ŧ |                              |
|   The following auxiliary characters are missing from the font: ʒ |                              |
|   The following auxiliary characters are missing from the font: ǯ |                              |
| Auxiliary orthography codepoints:                                 | * de_Latn (German)           |
|   The following auxiliary characters are missing from the font: Ĕ |                              |
|   The following auxiliary characters are missing from the font: Ĭ |                              |
|   The following auxiliary characters are missing from the font: Ŏ |                              |
|   The following auxiliary characters are missing from the font: Ŭ |                              |
|   The following auxiliary characters are missing from the font: ĕ |                              |
|   The following auxiliary characters are missing from the font: ĭ |                              |
|   The following auxiliary characters are missing from the font: ŏ |                              |
|   The following auxiliary characters are missing from the font: ſ |                              |
|   The following auxiliary characters are missing from the font: ŭ |                              | [code: warning-language-shaping]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Checking OS/2 fsType does not impose restrictions. (googlefonts/fstype)</summary>
    <div>








- 🔥 **FAIL** In this font fsType is set to 8 meaning that:
* The font may be embedded but must only be installed temporarily on other systems.

No such DRM restrictions can be enabled on the Google Fonts collection, so the fsType field must be set to zero (Installable Embedding) instead. [code: drm]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check a font's STAT table contains compulsory Axis Values. (googlefonts/STAT/compulsory_axis_values)</summary>
    <div>








- 🔥 **FAIL** Compulsory STAT Axis Values are incorrect:

| Name       | Axis | Current Value | Expected Value | Current Flags | Expected Flags | Current Linked Value | Expected Linked Value |
|------------|------|---------------|----------------|---------------|----------------|----------------------|-----------------------|
| Black      | wght | N/A           | 900            | N/A           | 0              | N/A                  | N/A                   |
| Bold       | wght | 700           | 700            | 0             | 0              | N/A                  | N/A                   |
| ExtraBold  | wght | 800           | 800            | 0             | 0              | N/A                  | N/A                   |
| ExtraLight | wght | 200           | 200            | 0             | 0              | N/A                  | N/A                   |
| Light      | wght | 300           | 300            | 0             | 0              | N/A                  | N/A                   |
| Medium     | wght | 500           | 500            | 0             | 0              | N/A                  | N/A                   |
| Regular    | wght | 400           | 400            | 2             | 2              | 700                  | 700                   |
| SemiBold   | wght | 600           | 600            | 0             | 0              | N/A                  | N/A                   |
| Thin       | wght | N/A           | 100            | N/A           | 0              | N/A                  | N/A                   |

 [code: bad-axis-values]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (googlefonts/use_typo_metrics)</summary>
    <div>








- 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) was NOT set. [code: missing-os2-fsselection-bit7]
  
  

</div>
</details>





<details>
    <summary>🔥 <b>FAIL</b> Check font follows the Google Fonts vertical metric schema (googlefonts/vertical_metrics)</summary>
    <div>








- 🔥 **FAIL** The sum of hhea.ascender + abs(hhea.descender) + hhea.lineGap is 1000 when it should be at least 1200 [code: bad-hhea-range]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. (contour_count)</summary>
    <div>








- ⚠️ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are
     inferred from the typical amounts of contours observed in a
     large collection of reference font families. The divergences
     listed below may simply indicate a significantly different
     design on some of your glyphs. On the other hand, some of these
     may flag actual bugs in the font such as glyphs mapped to an
     incorrect codepoint. Please consider reviewing the design and
     codepoint assignment of these to make sure they are correct.


    The following glyphs do not have the recommended number of contours:
* a.alt (unencoded): found 3, expected one of: [2, 369]
* aacute.alt (unencoded): found 4, expected one of: [2, 3]
* abreve.alt (unencoded): found 4, expected one of: [2, 3]
* acircumflex.alt (unencoded): found 4, expected one of: [2, 3]
* adieresis.alt (unencoded): found 5, expected one of: [3, 4]
* agrave.alt (unencoded): found 4, expected one of: [2, 3]
* amacron.alt (unencoded): found 4, expected one of: [2, 3]
* aogonek.alt (unencoded): found 4, expected one of: [2, 3]
* aring.alt (unencoded): found 5, expected one of: [2, 4]
... and 1 others [code: contour-count]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Does GPOS table have kerning information? (gpos_kerning_info)</summary>
    <div>








- ⚠️ **WARN** GPOS table lacks kerning information. [code: lacks-kern-info]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. (mandatory_avar_table)</summary>
    <div>








- ⚠️ **WARN** The font does not include an avar table.  If the progression rates of axes is linear and no user-mapping is expected, this is fine, and this check can be ignored or excluded. [code: missing-avar]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. (math_signs_width)</summary>
    <div>








- ⚠️ **WARN** The most common width is 593 among a set of 7  math glyphs.
The following math glyphs have a different width, though:
width=534: multiply
width=595: divide
width=719: minus
width=721: equal
width=591: plus [code: width-outliers]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure indic fonts have the Indian Rupee Sign glyph. (rupee)</summary>
    <div>








- ⚠️ **WARN** Font is missing the Indian Rupee Sign glyph. Please add a glyph for Indian Rupee Sign (₹) at codepoint U+20B9. [code: missing-rupee]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking that the typoAscender exceeds the yMax of the /Agrave. (typoascender_exceeds_Agrave)</summary>
    <div>








- ⚠️ **WARN** OS/2.sTypoAscender value should be greater than 890, but got 795 instead [code: typoAscender]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs (unreachable_glyphs)</summary>
    <div>








- ⚠️ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

* aacute.alt
* abreve.alt
* acircumflex.alt
* adieresis.alt
* agrave.alt
* amacron.alt
* aogonek.alt
* aring.alt
* atilde.alt [code: unreachable-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts have relatively consistent sidebearings. (suspicious_sidebearings)</summary>
    <div>








- ⚠️ **WARN** Glyph "Ygrave" has suspiciously high variation (z-score 10.12) in right sidebearings at locations:
    wght=100.00
    wght=199.99
    wght=300.01 [code: large-rsb-variation]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Font has correct separator glyphs? (googlefonts/separator_glyphs)</summary>
    <div>








- ⚠️ **WARN** Missing separator glyph U+2028 [code: missing-separator-glyphs]
  
  


- ⚠️ **WARN** Missing separator glyph U+2029 [code: missing-separator-glyphs]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. (dotted_circle)</summary>
    <div>








- ⚠️ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that
replace the dot. (soft_dotted)</summary>
    <div>








- ⚠️ **WARN** The dot of soft dotted characters _should_ disappear in other cases, for example:

* į̇
* i̇
* j̇ [code: soft-dotted]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? (outline_alignment_miss)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

* - Ccaron (U+010C): X=408,Y=797 (should be at ascender 795?)
* - Dcaron (U+010E): X=341,Y=797 (should be at ascender 795?)
* - Ecaron (U+011A): X=356,Y=797 (should be at ascender 795?)
* - G (U+0047): X=505,Y=686.5 (should be at cap-height 687?)
* - G (U+0047): X=505,Y=1 (should be at baseline 0?)
* - Gbreve (U+011E): X=505,Y=686.5 (should be at cap-height 687?)
* - Gbreve (U+011E): X=505,Y=1 (should be at baseline 0?)
* - uni0122 (U+0122): X=505,Y=686.5 (should be at cap-height 687?)
* - uni0122 (U+0122): X=505,Y=1 (should be at baseline 0?)
... and 59 others [code: found-misalignments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Check there are no overlapping path segments (overlapping_path_segments)</summary>
    <div>








- ⚠️ **WARN** The following glyphs have overlapping path segments:

* A (U+0041): Line(Line { p0: (328.0, 687.0), p1: (413.0, 687.0) }) has the same coordinates as a previous segment.
* Aacute (U+00C1): Line(Line { p0: (328.0, 687.0), p1: (413.0, 687.0) }) has the same coordinates as a previous segment.
* Abreve (U+0102): Line(Line { p0: (328.0, 687.0), p1: (413.0, 687.0) }) has the same coordinates as a previous segment.
* Acircumflex (U+00C2): Line(Line { p0: (328.0, 687.0), p1: (413.0, 687.0) }) has the same coordinates as a previous segment.
* Adieresis (U+00C4): Line(Line { p0: (328.0, 687.0), p1: (413.0, 687.0) }) has the same coordinates as a previous segment.
* Agrave (U+00C0): Line(Line { p0: (328.0, 687.0), p1: (413.0, 687.0) }) has the same coordinates as a previous segment.
* Amacron (U+0100): Line(Line { p0: (328.0, 687.0), p1: (413.0, 687.0) }) has the same coordinates as a previous segment.
* Aogonek (U+0104): Line(Line { p0: (328.0, 687.0), p1: (413.0, 687.0) }) has the same coordinates as a previous segment.
* Aring (U+00C5): Line(Line { p0: (328.0, 687.0), p1: (413.0, 687.0) }) has the same coordinates as a previous segment.
... and 2 others [code: overlapping-path-segments]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (googlefonts/meta/script_lang_tags)</summary>
    <div>








- ⚠️ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
  
  

</div>
</details>





<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. (googlefonts/vendor_id)</summary>
    <div>








- ⚠️ **WARN** OS/2 VendorID value 'NONE' is not yet recognized.
If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Checking OS/2 fsSelection value. (opentype/xavgcharwidth)</summary>
    <div>








- ℹ️ **INFO** OS/2 xAvgCharWidth is 588 but it should be 587 which corresponds to the average of the widths of all glyphs in the font. These are similar values, which may be a symptom of the slightly different calculation of the xAvgCharWidth value in font editors. There's further discussion on this at https://github.com/fonttools/fontbakery/issues/1622 [code: xAvgCharWidth-close]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. (hinting_impact)</summary>
    <div>








- ℹ️ **INFO** Hinting filesize impact:

 |               | ClarityCity[wght].ttf     |
 |:------------- | ---------------:|
 | Dehinted Size | 48332 |
 | Hinted Size   | 48356   |
 | Increase      | 24      |
 | Change        | 0.0 %  | [code: size-impact]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? (required_tables)</summary>
    <div>








- ℹ️ **INFO** This font contains the following optional tables:

    loca
    prep
    GPOS
    GSUB
    gasp [code: optional-tables]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table
set to optimize rendering? (googlefonts/gasp)</summary>
    <div>








- ℹ️ **INFO** These are the ppm ranges declared on the gasp table:

| PPM <= 65535 | - Use grid-fitting                                    |
|              | 	- Use grayscale rendering                            |
|              | 	- Use gridfitting with ClearType symmetric smoothing |
|              | 	- Use smoothing along multiple axes with ClearType®  |
|--------------|-------------------------------------------------------|
 [code: ranges]
  
  

</div>
</details>





<details>
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? (googlefonts/old_ttfautohint)</summary>
    <div>








- ℹ️ **INFO** Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: Version 1.000 [code: version-not-detected]
  
  

</div>
</details>


</div>
</details>






### Summary

| 🔥 FAIL | ⚠️ WARN | ℹ️ INFO | ✅ PASS | ⏩ SKIP | 
| ---|---|---|---|---|
| 23 | 34 | 12 | 207 | 92 | 
| 6% | 9% | 3% | 58% | 26% | 



