## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[7] NotoSansBuginese-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check that texts shape as per expectation (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/shaping/regression">com.google.fonts/check/shaping/regression</a>)</summary><div>


* 🔥 **FAIL** qa/shaping_tests/issues.json: Expected and actual shaping not matching
<div class="shaping">


<style type="text/css">
    @font-face {font-family: "TestFont"; src: url(../../fonts/NotoSansBuginese/googlefonts/ttf/NotoSansBuginese-Regular.ttf);}
    .tf { font-family: "TestFont"; }
    .shaping pre { font-size: 1.2rem; }
    .shaping li {
        font-size: 1.2rem;
        border-top: 1px solid #ddd;
        padding: 12px;
        margin-top: 12px;
    }
    .shaping-svg {
        height: 100px;
        margin: 10px;
        transform: matrix(1, 0, 0, -1, 0, 0);
    }
</style>

<h4>qa/shaping_tests/issues.json: Expected and actual shaping not matching</h4>


</div>
<div class="shaping">

<li>Shaping did not match: <span class="tf">ᨑᨚᨓ ᨑᨚᨉ</span> (See #1)</li>


<pre>Expected: uni1A11=0+689|uni1A1A=0+690|uni1A13=2+1219|space=3+260|uni1A11=4+689|uni1A1A=4+540|uni1A09=6+945</pre>



<pre>Got     : uni1A11=0+689|uni1A1A=0+540|uni1A13=2+1219|space=3+260|uni1A11=4+689|uni1A1A=4+540|uni1A09=6+945</pre>



<pre>                                  ^^
</pre>


Got: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 4882 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M73.0,124.0L15.0,190.0L262.0,415.0Q299.0,448.0 331.0,468.0Q363.0,488.0 405.0,488.0Q441.0,488.0 469.5,470.0Q498.0,452.0 537.0,407.0L674.0,248.0L618.0,198.0L512.0,321.0Q479.0,359.0 458.0,378.5Q437.0,398.0 411.0,398.0Q385.0,398.0 364.0,382.0Q343.0,366.0 309.0,336.0L73.0,124.0ZM256.0,15.0L196.0,80.0L381.0,250.0Q397.0,265.0 407.5,271.5Q418.0,278.0 435.0,278.0Q453.0,278.0 468.0,263.5Q483.0,249.0 506.0,223.0L646.0,63.0L590.0,15.0L477.0,145.0Q464.0,160.0 457.0,166.5Q450.0,173.0 440.0,173.0Q427.0,173.0 392.0,139.0L256.0,15.0Z"  transform="translate(0, 793)"/>
<path d="M617.0,2.0L318.0,328.0Q299.0,350.0 286.5,361.5Q274.0,373.0 267.0,373.0Q254.0,373.0 240.0,362.5Q226.0,352.0 215.0,341.0L85.0,217.0L25.0,283.0L175.0,424.0Q203.0,450.0 220.0,460.5Q237.0,471.0 255.0,471.0Q276.0,471.0 292.5,460.0Q309.0,449.0 334.0,422.0L673.0,52.0L617.0,2.0Z"  transform="translate(689, 793)"/>
<path d="M81.0,21.0L15.0,81.0L224.0,311.0Q262.0,352.0 287.5,368.5Q313.0,385.0 341.0,385.0Q372.0,385.0 394.0,365.0Q416.0,345.0 447.0,304.0L538.0,187.0Q564.0,154.0 578.5,136.0Q593.0,118.0 609.0,118.0Q622.0,118.0 637.5,134.5Q653.0,151.0 677.0,177.0L798.0,311.0Q835.0,352.0 861.5,368.5Q888.0,385.0 916.0,385.0Q947.0,385.0 969.0,365.0Q991.0,345.0 1023.0,303.0L1204.0,64.0L1147.0,21.0L996.0,218.0Q968.0,254.0 953.5,274.5Q939.0,295.0 923.0,295.0Q906.0,295.0 891.0,280.5Q876.0,266.0 846.0,232.0L731.0,105.0Q697.0,68.0 671.5,44.5Q646.0,21.0 615.0,21.0Q581.0,21.0 559.0,44.5Q537.0,68.0 506.0,108.0L380.0,275.0Q365.0,295.0 349.0,295.0Q333.0,295.0 318.0,281.5Q303.0,268.0 272.0,232.0L81.0,21.0Z"  transform="translate(1229, 793)"/>
<path d=""  transform="translate(2448, 793)"/>
<path d="M73.0,124.0L15.0,190.0L262.0,415.0Q299.0,448.0 331.0,468.0Q363.0,488.0 405.0,488.0Q441.0,488.0 469.5,470.0Q498.0,452.0 537.0,407.0L674.0,248.0L618.0,198.0L512.0,321.0Q479.0,359.0 458.0,378.5Q437.0,398.0 411.0,398.0Q385.0,398.0 364.0,382.0Q343.0,366.0 309.0,336.0L73.0,124.0ZM256.0,15.0L196.0,80.0L381.0,250.0Q397.0,265.0 407.5,271.5Q418.0,278.0 435.0,278.0Q453.0,278.0 468.0,263.5Q483.0,249.0 506.0,223.0L646.0,63.0L590.0,15.0L477.0,145.0Q464.0,160.0 457.0,166.5Q450.0,173.0 440.0,173.0Q427.0,173.0 392.0,139.0L256.0,15.0Z"  transform="translate(2708, 793)"/>
<path d="M617.0,2.0L318.0,328.0Q299.0,350.0 286.5,361.5Q274.0,373.0 267.0,373.0Q254.0,373.0 240.0,362.5Q226.0,352.0 215.0,341.0L85.0,217.0L25.0,283.0L175.0,424.0Q203.0,450.0 220.0,460.5Q237.0,471.0 255.0,471.0Q276.0,471.0 292.5,460.0Q309.0,449.0 334.0,422.0L673.0,52.0L617.0,2.0Z"  transform="translate(3397, 793)"/>
<path d="M435.0,0.0Q394.0,0.0 365.5,21.5Q337.0,43.0 303.0,81.0L15.0,409.0L71.0,460.0L328.0,167.0Q360.0,130.0 381.5,110.0Q403.0,90.0 429.0,90.0Q455.0,90.0 476.0,106.0Q497.0,122.0 531.0,152.0L870.0,460.0L930.0,394.0L577.0,73.0Q540.0,40.0 508.5,20.0Q477.0,0.0 435.0,0.0ZM443.0,320.0Q382.0,320.0 382.0,388.0Q382.0,455.0 443.0,455.0Q506.0,455.0 506.0,388.0Q506.0,352.0 487.5,336.0Q469.0,320.0 443.0,320.0Z"  transform="translate(3937, 793)"/>
</svg>
 Expected: <svg class="shaping-svg" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 5032 2362" transform="matrix(1 0 0 -1 0 0)">
<path d="M73.0,124.0L15.0,190.0L262.0,415.0Q299.0,448.0 331.0,468.0Q363.0,488.0 405.0,488.0Q441.0,488.0 469.5,470.0Q498.0,452.0 537.0,407.0L674.0,248.0L618.0,198.0L512.0,321.0Q479.0,359.0 458.0,378.5Q437.0,398.0 411.0,398.0Q385.0,398.0 364.0,382.0Q343.0,366.0 309.0,336.0L73.0,124.0ZM256.0,15.0L196.0,80.0L381.0,250.0Q397.0,265.0 407.5,271.5Q418.0,278.0 435.0,278.0Q453.0,278.0 468.0,263.5Q483.0,249.0 506.0,223.0L646.0,63.0L590.0,15.0L477.0,145.0Q464.0,160.0 457.0,166.5Q450.0,173.0 440.0,173.0Q427.0,173.0 392.0,139.0L256.0,15.0Z"  transform="translate(0, 793)"/>
<path d="M617.0,2.0L318.0,328.0Q299.0,350.0 286.5,361.5Q274.0,373.0 267.0,373.0Q254.0,373.0 240.0,362.5Q226.0,352.0 215.0,341.0L85.0,217.0L25.0,283.0L175.0,424.0Q203.0,450.0 220.0,460.5Q237.0,471.0 255.0,471.0Q276.0,471.0 292.5,460.0Q309.0,449.0 334.0,422.0L673.0,52.0L617.0,2.0Z"  transform="translate(689, 793)"/>
<path d="M81.0,21.0L15.0,81.0L224.0,311.0Q262.0,352.0 287.5,368.5Q313.0,385.0 341.0,385.0Q372.0,385.0 394.0,365.0Q416.0,345.0 447.0,304.0L538.0,187.0Q564.0,154.0 578.5,136.0Q593.0,118.0 609.0,118.0Q622.0,118.0 637.5,134.5Q653.0,151.0 677.0,177.0L798.0,311.0Q835.0,352.0 861.5,368.5Q888.0,385.0 916.0,385.0Q947.0,385.0 969.0,365.0Q991.0,345.0 1023.0,303.0L1204.0,64.0L1147.0,21.0L996.0,218.0Q968.0,254.0 953.5,274.5Q939.0,295.0 923.0,295.0Q906.0,295.0 891.0,280.5Q876.0,266.0 846.0,232.0L731.0,105.0Q697.0,68.0 671.5,44.5Q646.0,21.0 615.0,21.0Q581.0,21.0 559.0,44.5Q537.0,68.0 506.0,108.0L380.0,275.0Q365.0,295.0 349.0,295.0Q333.0,295.0 318.0,281.5Q303.0,268.0 272.0,232.0L81.0,21.0Z"  transform="translate(1379, 793)"/>
<path d=""  transform="translate(2598, 793)"/>
<path d="M73.0,124.0L15.0,190.0L262.0,415.0Q299.0,448.0 331.0,468.0Q363.0,488.0 405.0,488.0Q441.0,488.0 469.5,470.0Q498.0,452.0 537.0,407.0L674.0,248.0L618.0,198.0L512.0,321.0Q479.0,359.0 458.0,378.5Q437.0,398.0 411.0,398.0Q385.0,398.0 364.0,382.0Q343.0,366.0 309.0,336.0L73.0,124.0ZM256.0,15.0L196.0,80.0L381.0,250.0Q397.0,265.0 407.5,271.5Q418.0,278.0 435.0,278.0Q453.0,278.0 468.0,263.5Q483.0,249.0 506.0,223.0L646.0,63.0L590.0,15.0L477.0,145.0Q464.0,160.0 457.0,166.5Q450.0,173.0 440.0,173.0Q427.0,173.0 392.0,139.0L256.0,15.0Z"  transform="translate(2858, 793)"/>
<path d="M617.0,2.0L318.0,328.0Q299.0,350.0 286.5,361.5Q274.0,373.0 267.0,373.0Q254.0,373.0 240.0,362.5Q226.0,352.0 215.0,341.0L85.0,217.0L25.0,283.0L175.0,424.0Q203.0,450.0 220.0,460.5Q237.0,471.0 255.0,471.0Q276.0,471.0 292.5,460.0Q309.0,449.0 334.0,422.0L673.0,52.0L617.0,2.0Z"  transform="translate(3547, 793)"/>
<path d="M435.0,0.0Q394.0,0.0 365.5,21.5Q337.0,43.0 303.0,81.0L15.0,409.0L71.0,460.0L328.0,167.0Q360.0,130.0 381.5,110.0Q403.0,90.0 429.0,90.0Q455.0,90.0 476.0,106.0Q497.0,122.0 531.0,152.0L870.0,460.0L930.0,394.0L577.0,73.0Q540.0,40.0 508.5,20.0Q477.0,0.0 435.0,0.0ZM443.0,320.0Q382.0,320.0 382.0,388.0Q382.0,455.0 443.0,455.0Q506.0,455.0 506.0,388.0Q506.0,352.0 487.5,336.0Q469.0,320.0 443.0,320.0Z"  transform="translate(4087, 793)"/>
</svg>


</div> [code: shaping-regression]
</div></details><details><summary>⚠ <b>WARN:</b> Are there caret positions declared for every ligature? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/ligature_carets">com.google.fonts/check/ligature_carets</a>)</summary><div>


* ⚠ **WARN** This font lacks caret position values for ligature glyphs on its GDEF table. [code: lacks-caret-pos]
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- uni1A15 + uni1A17

	- uni1A17 + uni200D 

	- And uni200D + uni1A10 [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- nbspace
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>> 

	* And 64 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-short-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 6 | 108 | 7 | 105 | 0 |
| 0% | 0% | 3% | 48% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
