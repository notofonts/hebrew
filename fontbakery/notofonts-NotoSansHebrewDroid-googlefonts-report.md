## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[12] NotoSansHebrewDroid[wght].ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour order differs in glyph 'uni05B80591': [0, 1] in wght=400, [1, 0] in wght=700.
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- NULL

- uniFB4F.salt
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansHebrewDroid/googlefonts/variable-ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, cherokee, coptic</li>
<li>U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>hebrew</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Aghem (Latn, 38,843 speakers), Dii (Latn, 71,000 speakers), Ebira (Latn, 2,200,000 speakers), Han (Latn, 6 speakers), Heiltsuk (Latn, 300 speakers), Vute (Latn, 21,000 speakers), Mundani (Latn, 34,000 speakers), Ejagham (Latn, 120,000 speakers), Kaska (Latn, 125 speakers), Lugbara (Latn, 2,200,000 speakers), South Central Banda (Latn, 244,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Bafut (Latn, 158,146 speakers), Fur (Latn, 1,230,163 speakers), Belarusian (Cyrl, 10,064,517 speakers), Yala (Latn, 200,000 speakers), Southern Kisi (Latn, 360,000 speakers), Dan (Latn, 1,099,244 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Mfumte (Latn, 79,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Navajo (Latn, 166,319 speakers), Zapotec (Latn, 490,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Nzakara (Latn, 50,000 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Gulay (Latn, 250,478 speakers), Ma’di (Latn, 584,000 speakers), Nateni (Latn, 100,000 speakers), Makaa (Latn, 221,000 speakers), Basaa (Latn, 332,940 speakers), Igbo (Latn, 27,823,640 speakers), Mango (Latn, 77,000 speakers), Kom (Latn, 360,685 speakers), Ngbaka (Latn, 1,020,000 speakers), Sar (Latn, 500,000 speakers), Ekpeye (Latn, 226,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* G (U+0047): X=537.0,Y=-1.0 (should be at baseline 0?)

* Gbreve (U+011E): X=537.0,Y=-1.0 (should be at baseline 0?)

* uni0122 (U+0122): X=537.0,Y=-1.0 (should be at baseline 0?)

* Gdotaccent (U+0120): X=537.0,Y=-1.0 (should be at baseline 0?)

* uni1E9E (U+1E9E): X=326.5,Y=-1.5 (should be at baseline 0?)

* S (U+0053): X=136.0,Y=-1.0 (should be at baseline 0?)

* Sacute (U+015A): X=136.0,Y=-1.0 (should be at baseline 0?)

* Scaron (U+0160): X=136.0,Y=-1.0 (should be at baseline 0?)

* Scedilla (U+015E): X=136.0,Y=-1.0 (should be at baseline 0?)

* uni0218 (U+0218): X=136.0,Y=-1.0 (should be at baseline 0?)

* Uogonek (U+0172): X=449.0,Y=1.0 (should be at baseline 0?)

* ae (U+00E6): X=710.5,Y=-1.5 (should be at baseline 0?)

* braceleft (U+007B): X=150.0,Y=1.0 (should be at baseline 0?)

* colon (U+003A): X=177.5,Y=2.0 (should be at baseline 0?)

* colon (U+003A): X=90.0,Y=2.0 (should be at baseline 0?)

* e (U+0065): X=408.0,Y=-1.5 (should be at baseline 0?)

* eacute (U+00E9): X=408.0,Y=-1.5 (should be at baseline 0?)

* ecaron (U+011B): X=408.0,Y=-1.5 (should be at baseline 0?)

* ecircumflex (U+00EA): X=408.0,Y=-1.5 (should be at baseline 0?)

* edieresis (U+00EB): X=408.0,Y=-1.5 (should be at baseline 0?)

* edotaccent (U+0117): X=408.0,Y=-1.5 (should be at baseline 0?)

* egrave (U+00E8): X=408.0,Y=-1.5 (should be at baseline 0?)

* ellipsis (U+2026): X=177.5,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=90.0,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=439.5,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=352.0,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=700.5,Y=2.0 (should be at baseline 0?)

* ellipsis (U+2026): X=613.0,Y=2.0 (should be at baseline 0?)

* emacron (U+0113): X=408.0,Y=-1.5 (should be at baseline 0?)

* eogonek (U+0119): X=408.0,Y=-1.5 (should be at baseline 0?)

* Euro (U+20AC): X=468.5,Y=-0.5 (should be at baseline 0?)

* exclam (U+0021): X=177.5,Y=2.0 (should be at baseline 0?)

* exclam (U+0021): X=90.0,Y=2.0 (should be at baseline 0?)

* f (U+0066): X=327.0,Y=688.0 (should be at x-height 686?)

* germandbls (U+00DF): X=317.0,Y=-1.0 (should be at baseline 0?)

* oe (U+0153): X=791.0,Y=-1.5 (should be at baseline 0?)

* period (U+002E): X=177.5,Y=2.0 (should be at baseline 0?)

* period (U+002E): X=90.0,Y=2.0 (should be at baseline 0?)

* question (U+003F): X=222.0,Y=2.0 (should be at baseline 0?)

* question (U+003F): X=134.5,Y=2.0 (should be at baseline 0?)

* s (U+0073): X=123.5,Y=-1.0 (should be at baseline 0?)

* sacute (U+015B): X=123.5,Y=-1.0 (should be at baseline 0?)

* scaron (U+0161): X=123.5,Y=-1.0 (should be at baseline 0?)

* scedilla (U+015F): X=123.5,Y=-1.0 (should be at baseline 0?)

* uni0219 (U+0219): X=123.5,Y=-1.0 (should be at baseline 0?)

* three (U+0033): X=137.0,Y=-1.5 (should be at baseline 0?)

* w (U+0077): X=258.0,Y=1.0 (should be at baseline 0?)

* w (U+0077): X=158.0,Y=1.0 (should be at baseline 0?)

* w (U+0077): X=626.0,Y=1.0 (should be at baseline 0?)

* w (U+0077): X=523.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=258.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=158.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=626.0,Y=1.0 (should be at baseline 0?)

* wacute (U+1E83): X=523.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=258.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=158.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=626.0,Y=1.0 (should be at baseline 0?)

* wcircumflex (U+0175): X=523.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=258.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=158.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=626.0,Y=1.0 (should be at baseline 0?)

* wdieresis (U+1E85): X=523.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=258.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=158.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=626.0,Y=1.0 (should be at baseline 0?)

* wgrave (U+1E81): X=523.0,Y=1.0 (should be at baseline 0?)

* y (U+0079): X=217.0,Y=-2.0 (should be at baseline 0?)

* yacute (U+00FD): X=217.0,Y=-2.0 (should be at baseline 0?)

* ycircumflex (U+0177): X=217.0,Y=-2.0 (should be at baseline 0?)

* ydieresis (U+00FF): X=217.0,Y=-2.0 (should be at baseline 0?)

* ygrave (U+1EF3): X=217.0,Y=-2.0 (should be at baseline 0?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Is there kerning info for non-ligated sequences? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gpos.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>GPOS table lacks kerning info for the following non-ligated sequences:</p>
<pre><code>- uniFB4F + uni05B1

- uniFB4F + uni05B5

- uniFB4F + uni05B6
</code></pre>
 [code: lacks-kern-info]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there caret positions declared for every ligature? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.gdef.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font lacks caret position values for ligature glyphs on its GDEF table.</p>
 [code: lacks-caret-pos]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.os2.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansHebrewDroid/googlefonts/variable-ttf/NotoSansHebrewDroid[wght].ttf'].</p>
 [code: missing-os2-fsselection-bit7]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 2 | 11 | 95 | 7 | 136 | 0 | 
| 0% | 0% | 1% | 4% | 38% | 3% | 54% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
