# Gabriel's Plover Setup

Although I'm just starting out with Plover and steno, I have compiled a collection of dictionaries that I find the most personally useful. There are currently five git submodules that I either use, or keep around and hope to use to some extent in the near future.

## CharleyShattuck

Charley Shattuck is the creator of the [TinyMod](https://stenomod.blogspot.com/), which is what I will be using to steno.

### TinyMod_layout.json

A layout file for the Layout Display plugin.

## EPLHREU_symbols

Emily's Symbol Dictionary provides a consistent method to type symbols in steno.

## aerickt

### movement.modal

Provides a way to repeat successive movement keystrokes.

### plover-base.json

A dictionary replacement for Plover's default main.json based more definitively on Plover theory than the standard dictionary. It also removes all of the "misstroke" entries from the default dictionary, making learning through word lookups much more reliable.

This dictionary also contains a replacement for the default commands.json and a number input method that replaces the standard.

### raw.py

Creates a way to output raw steno.

## paulfioravanti

### dictionaries/q-and-a.json

Provides strokes for court reporting.

## praging

### base-adds.json

Missing entries from aerickt's plover-base.json provided for ease of merge.

### vidonnus.json

Personal dictionary replacement to user.json default.

## Currently Unused

### CharleyShattuck/thumb_numbers.json

Provides an easier way to input numbers when using the TinyMod. Will need to parse for conflicts before using this.

### morinted/custom.json

Ted Morin's unmerged additions to Plover's main.json may be interesting to look at later down the road.

### paulfioravanti

This dictionaries library is vast and provides for a lot of use-cases. The following number dictionaries provide important features that will have to be remembered when looking at the completeness of a steno dictionary collection.

#### dictionaries/number/number-ordinals.json

Provides for input of ordinal numbers.

#### dictionaries/number/number-other.json

Provides for input of large and hyphenated numbers.

#### dictionaries/number/number-time.json

Provides for more granular input of times.
