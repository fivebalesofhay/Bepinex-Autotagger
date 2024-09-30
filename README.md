# Bepinex-Autotagger
A mod for automatically tagging bibites by gene. Made with Bepinex.

This mod was made using version 0.5.1. It will likely work on every version past 0.5.1, but it may not.

To Install:
<ul>
<li><a href="https://docs.bepinex.dev/articles/user_guide/installation/index.html">Install Bepinex into your copy of The Bibites</a> (Don't forget to run the game once to generate the config files.)</li>
<li><a href="https://github.com/BepInEx/BepInEx/releases/tag/v5.4.23.2">Note: the latest stable build of Bepinex as of this mod is here.</a></li>
<li>Download Autotagger.dll and place it in the BepInEx/plugins folder.</li>
</ul>

To tag bibites, write the desired tag in the tag input field, the gene you want to check in the gene input field, and the minimum and maximum values in the min and max input fields, and click the write button next to the input fields. Bibites with a gene value greater than the minimum and lower than the maximum, inclusive, will be tagged. The gene name must be written exactly as it is written in the game, though it is not case sensitive. You may also use the gene index number instead of the gene name.

Here is an example of a possible configuration:
![Autotagger](https://github.com/fivebalesofhay/Bepinex-Autotagger/assets/124223106/1fb982a8-7ad2-46e1-95a7-a5f0d20c9455)
