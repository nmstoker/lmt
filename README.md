# lmt
LMT: Levenshtein Matching Tool - efficiently match lists

**View an online version of the tool hosted on GitHub pages here:** https://about.nmstoker.com/lmt.html

## About this tool

This Levenshtein Matching Tool is a simple tool to efficiently match a potentially noisy user input list with a clean "match list" (optionally including an associated lookup value or ID).

To get a quick idea of how it works, try out the example data links above and click on "Set Selections", then play around with the various options.

It makes use of the [Levenshtein Distance](https://en.wikipedia.org/wiki/Levenshtein_distance), matching items in the user input list with the closest items in the "match list". The closest match is automatically selected in a drop-down list next to the user input item, showing any optional lookup value/ID in the following column and highlighting the distance of the selected item, colour coding it:

* **Green**  for an exact match (distance zero)
* **Blue**    for items within a designated threshold
* **Red**     for any entries the user has manually selected that are above the threshold
* **Grey**    where no selection is made automatically, which happens when there is no match below the threshold

The tool's focus is on desktop experience as it works closely with the clipboard for adding items to the two lists.

Click within either of the two tables to paste data into that table. Use the Export to Clipboard button to copy out the selected matches and associated details.

The page operates as a static page with all processing happening locally, so it can be easily hosted online, [as here](https://about.nmstoker.com/lmt.html), or as a local file you open in your browser.

Source code and license details are available here: https://github.com/nmstoker/lmt
