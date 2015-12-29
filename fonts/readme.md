This folder contains the AOSP stock fonts with the Sony fonts added to them.

Every font included is updated to the latest upstream available.

Due to changes in Unicode8.0 several emoji are shown as text by default.
The list of emoji that do this is here: http://www.unicode.org/Public/emoji/2.0/emoji-data.txt

AOSP has a script that hacks some fonts to change some of these emoji to their colored variants, i do not have these hacks in this version.

The keyboard app used will have to use the correct unicode format to display the colored emoji.
moji modifier sequence — A sequence of the following form:

(emoji_modifier_base | emoji_base_variation_sequence) emoji_modifier

emoji variation selector — Either of the two variation selectors used to request a text or emoji presentation for an emoji character:

U+FE0E VARIATION SELECTOR-15 (VS15) for a text presentation
U+FE0F VARIATION SELECTOR-16 (VS16) for an emoji presentation

More information is available here: http://unicode.org/reports/tr51/