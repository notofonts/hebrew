## FontBakery report

fontbakery version: 0.10.4

<details><summary><b>[1] Experimental checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 🔥 **FAIL** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| br_Latn (Breton) | Some base glyphs were missing: CʼH, cʼh |
|  ^  | Shaper produced a .notdef |
| haw_Latn (Hawaiian) | Some base glyphs were missing: ʻ |
|  ^  | Shaper produced a .notdef |
| mh_Latn (Marshallese) | Some base glyphs were missing: Ḷ, ḷ, Ṃ, ṃ, Ṇ, ṇ, Ọ, ọ |
|  ^  | Some mark glyphs were missing: ◌̣ |
|  ^  | Shaper produced a .notdef |
| qu_Latn (Quechua) | Some base glyphs were missing: CHʼ, Kʼ, Pʼ, Qʼ, Tʼ, chʼ, kʼ, pʼ, qʼ, tʼ |
|  ^  | Shaper produced a .notdef |
| scn_Latn (Sicilian) | Some base glyphs were missing: Ḍ, ḍ |
|  ^  | Shaper produced a .notdef |
| teo_Latn (Teso) | Some base glyphs were missing: Ɔ, Ɛ, Ɨ, Ʉ, ɔ, ɛ, ɨ, ʉ, ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᵘ, ᶤ, ᶶ, ⁱ |
|  ^  | Shaper produced a .notdef |

 [code: failed-language-shaping]
* ⚠ **WARN** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| lg_Latn (Ganda) | No variant glyphs were found for Eng |
| dyo_Latn (Jola-Fonyi) | No variant glyphs were found for Eng |
| ny_Latn (Nyanja) | No variant glyphs were found for Eng |
| wo_Latn (Wolof) | No variant glyphs were found for Eng |

 [code: warning-language-shaping]
</div></details><br></div></details><details><summary><b>[16] NotoSansHebrewDroid[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansHebrewDroid/googlefonts/variable/NotoSansHebrewDroid[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that legacy accents aren't used in composite glyphs. (derived from com.google.fonts/check/legacy_accents) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* 🔥 **FAIL** Glyph "Aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ccedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Dcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Tcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acutecomb" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0306" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030C" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0327" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0302" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0308" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0307" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gravecomb" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030B" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0328" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030A" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "tildecomb" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
</div></details><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, math, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: tifinagh, old-permic
 * U+0307 COMBINING DOT ABOVE: try adding one of: old-permic, canadian-aboriginal, malayalam, tifinagh, coptic, syriac, math, tai-le
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+200C ZERO WIDTH NON-JOINER: try adding one of: tai-viet, syloti-nagri, malayalam, thaana, mahajani, batak, modi, takri, meetei-mayek, sundanese, sogdian, syriac, hanifi-rohingya, rejang, tirhuta, avestan, khojki, tai-tham, myanmar, devanagari, dogra, javanese, mongolian, chakma, saurashtra, brahmi, mandaic, nko, warang-citi, kannada, tai-le, buginese, kayah-li, tibetan, bengali, thai, pahawh-hmong, oriya, telugu, balinese, gurmukhi, khmer, sinhala, yi, phags-pa, gunjala-gondi, cham, siddham, tamil, limbu, tagalog, newa, hatran, new-tai-lue, tagbanwa, tifinagh, buhid, manichaean, khudawadi, duployan, kaithi, psalter-pahlavi, lepcha, hanunoo, grantha, gujarati, kharoshthi, sharada
 * U+200D ZERO WIDTH JOINER: try adding one of: tai-viet, syloti-nagri, malayalam, thaana, mahajani, batak, modi, takri, meetei-mayek, sundanese, syriac, old-hungarian, hanifi-rohingya, rejang, tirhuta, avestan, khojki, tai-tham, myanmar, devanagari, dogra, javanese, mongolian, chakma, saurashtra, brahmi, mandaic, nko, warang-citi, kannada, tai-le, buginese, kayah-li, tibetan, bengali, thai, pahawh-hmong, oriya, telugu, balinese, gurmukhi, sinhala, yi, phags-pa, gunjala-gondi, cham, siddham, tamil, limbu, tagalog, newa, new-tai-lue, tagbanwa, tifinagh, buhid, manichaean, khudawadi, duployan, kaithi, psalter-pahlavi, lepcha, hanunoo, grantha, gujarati, kharoshthi, sharada
 * U+200E LEFT-TO-RIGHT MARK: try adding one of: phags-pa, syriac, thaana, nko
 * U+200F RIGHT-TO-LEFT MARK: try adding one of: phags-pa, syriac, thaana, nko
 * U+2010 HYPHEN: try adding one of: kayah-li, syloti-nagri, kaithi, sora-sompeng, yi, cham, lisu, coptic, kharoshthi, sundanese
 * U+FB1D HEBREW LETTER YOD WITH HIRIQ: not included in any glyphset definition
 * U+FB1E HEBREW POINT JUDEO-SPANISH VARIKA: not included in any glyphset definition
 * U+FB1F HEBREW LIGATURE YIDDISH YOD YOD PATAH: not included in any glyphset definition
 * U+FB20 HEBREW LETTER ALTERNATIVE AYIN: not included in any glyphset definition
 * U+FB21 HEBREW LETTER WIDE ALEF: not included in any glyphset definition
 * U+FB22 HEBREW LETTER WIDE DALET: not included in any glyphset definition
 * U+FB23 HEBREW LETTER WIDE HE: not included in any glyphset definition
 * U+FB24 HEBREW LETTER WIDE KAF: not included in any glyphset definition
 * U+FB25 HEBREW LETTER WIDE LAMED: not included in any glyphset definition
 * U+FB26 HEBREW LETTER WIDE FINAL MEM: not included in any glyphset definition
 * U+FB27 HEBREW LETTER WIDE RESH: not included in any glyphset definition
 * U+FB28 HEBREW LETTER WIDE TAV: not included in any glyphset definition
 * U+FB29 HEBREW LETTER ALTERNATIVE PLUS SIGN: not included in any glyphset definition
 * U+FB4C HEBREW LETTER BET WITH RAFE: not included in any glyphset definition
 * U+FB4D HEBREW LETTER KAF WITH RAFE: not included in any glyphset definition
 * U+FB4E HEBREW LETTER PE WITH RAFE: not included in any glyphset definition
 * U+FB4F HEBREW LIGATURE ALEF LAMED: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `hebrew`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uniFB4F + uni05B1

	- uni05B1 + uni05B5

	- uni05B5 + uni05B6 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Hebrew Droid' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/fonttools/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure variable fonts include an avar table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/mandatory_avar_table">com.google.fonts/check/mandatory_avar_table</a>)</summary><div>


* ⚠ **WARN** This variable font does not have an avar table. [code: missing-avar]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- NULL

	- uniFB4F.salt
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Detect any interpolation issues in the font. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/interpolation_issues">com.google.fonts/check/interpolation_issues</a>)</summary><div>


* ⚠ **WARN** Interpolation issues were found in the font:

	- Contour order differs in glyph 'uni05B80591': [0, 1] in <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7f67e491db10>, [1, 0] in <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7f67e0003010>. [code: interpolation-issues]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* exclam (U+0021): X=177.5,Y=2.0 (should be at baseline 0?)

	* exclam (U+0021): X=90.0,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=177.5,Y=2.0 (should be at baseline 0?)

	* period (U+002E): X=90.0,Y=2.0 (should be at baseline 0?)

	* three (U+0033): X=137.0,Y=-1.5 (should be at baseline 0?)

	* colon (U+003A): X=177.5,Y=2.0 (should be at baseline 0?)

	* colon (U+003A): X=90.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=222.0,Y=2.0 (should be at baseline 0?)

	* question (U+003F): X=134.5,Y=2.0 (should be at baseline 0?)

	* G (U+0047): X=537.0,Y=-1.0 (should be at baseline 0?)

	* S (U+0053): X=136.0,Y=-1.0 (should be at baseline 0?)

	* e (U+0065): X=408.0,Y=-1.5 (should be at baseline 0?)

	* f (U+0066): X=327.0,Y=688.0 (should be at x-height 686?)

	* s (U+0073): X=123.5,Y=-1.0 (should be at baseline 0?)

	* w (U+0077): X=258.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=158.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=626.0,Y=1.0 (should be at baseline 0?)

	* w (U+0077): X=523.0,Y=1.0 (should be at baseline 0?)

	* y (U+0079): X=217.0,Y=-2.0 (should be at baseline 0?)

	* braceleft (U+007B): X=150.0,Y=1.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=317.0,Y=-1.0 (should be at baseline 0?)

	* ae (U+00E6): X=710.5,Y=-1.5 (should be at baseline 0?)

	* egrave (U+00E8): X=408.0,Y=-1.5 (should be at baseline 0?)

	* eacute (U+00E9): X=408.0,Y=-1.5 (should be at baseline 0?)

	* ecircumflex (U+00EA): X=408.0,Y=-1.5 (should be at baseline 0?)

	* edieresis (U+00EB): X=408.0,Y=-1.5 (should be at baseline 0?)

	* oslash (U+00F8): X=232.0,Y=-1.5 (should be at baseline 0?)

	* yacute (U+00FD): X=217.0,Y=-2.0 (should be at baseline 0?)

	* ydieresis (U+00FF): X=217.0,Y=-2.0 (should be at baseline 0?)

	* emacron (U+0113): X=408.0,Y=-1.5 (should be at baseline 0?)

	* edotaccent (U+0117): X=408.0,Y=-1.5 (should be at baseline 0?)

	* eogonek (U+0119): X=408.0,Y=-1.5 (should be at baseline 0?)

	* ecaron (U+011B): X=408.0,Y=-1.5 (should be at baseline 0?)

	* Gbreve (U+011E): X=537.0,Y=-1.0 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=537.0,Y=-1.0 (should be at baseline 0?)

	* uni0122 (U+0122): X=537.0,Y=-1.0 (should be at baseline 0?)

	* oe (U+0153): X=791.0,Y=-1.5 (should be at baseline 0?)

	* Sacute (U+015A): X=136.0,Y=-1.0 (should be at baseline 0?)

	* sacute (U+015B): X=123.5,Y=-1.0 (should be at baseline 0?)

	* Scedilla (U+015E): X=136.0,Y=-1.0 (should be at baseline 0?)

	* scedilla (U+015F): X=123.5,Y=-1.0 (should be at baseline 0?)

	* Scaron (U+0160): X=136.0,Y=-1.0 (should be at baseline 0?)

	* scaron (U+0161): X=123.5,Y=-1.0 (should be at baseline 0?)

	* Uogonek (U+0172): X=449.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=258.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=158.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=626.0,Y=1.0 (should be at baseline 0?)

	* wcircumflex (U+0175): X=523.0,Y=1.0 (should be at baseline 0?)

	* ycircumflex (U+0177): X=217.0,Y=-2.0 (should be at baseline 0?)

	* uni0218 (U+0218): X=136.0,Y=-1.0 (should be at baseline 0?)

	* uni0219 (U+0219): X=123.5,Y=-1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=258.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=158.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=626.0,Y=1.0 (should be at baseline 0?)

	* wgrave (U+1E81): X=523.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=258.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=158.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=626.0,Y=1.0 (should be at baseline 0?)

	* wacute (U+1E83): X=523.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=258.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=158.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=626.0,Y=1.0 (should be at baseline 0?)

	* wdieresis (U+1E85): X=523.0,Y=1.0 (should be at baseline 0?)

	* uni1E9E (U+1E9E): X=326.5,Y=-1.5 (should be at baseline 0?)

	* ygrave (U+1EF3): X=217.0,Y=-2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=177.5,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=90.0,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=439.5,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=352.0,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=700.5,Y=2.0 (should be at baseline 0?)

	* ellipsis (U+2026): X=613.0,Y=2.0 (should be at baseline 0?)

	* Euro (U+20AC): X=468.5,Y=-0.5 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Koonzime (Latn, 40,000 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers), Mango (Latn, 77,000 speakers), Kom (Latn, 360,685 speakers), Navajo (Latn, 166,319 speakers), Sar (Latn, 500,000 speakers), Aghem (Latn, 38,843 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ebira (Latn, 2,200,000 speakers), Avokaya (Latn, 100,000 speakers), Dan (Latn, 1,099,244 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Lugbara (Latn, 2,200,000 speakers), Nateni (Latn, 100,000 speakers), Basaa (Latn, 332,940 speakers), Ma’di (Latn, 584,000 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 5 | 12 | 103 | 8 | 127 | 0 |
| 0% | 2% | 5% | 40% | 3% | 50% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
