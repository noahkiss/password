# Simple Password Generator

This is a simple web-based password generator which generates passwords the way I prefer -
that is to say, the way I've found most sites to accept without modification.

Everything is calculated in JavaScript locally, and the passwords are not sent to the server for logging.
You should be able to download this code and run it offline.

This password generator started out as Aaron Toponce's [webpassgen](https://github.com/atoponce/webpassgen),
but has been heavily modified and does not come with any security guarantees beyond face value
(load page, get password).

## Why I built this

This was born out of frustration with current options for generating a password (pass*phrase*) -
some give you words, but no numbers.
Some give you words and numbers, but no capital letters.
Some don't give good options for selecting a word separator.
None allow specifying of character length,
so some may require trimming or be very different lengths with the same number of words.
Bitwarden's *Free Password Generator* checks most of my boxes, but is now mostly ads
(I almost just modified their page, but it was a 5.9mb download using SinglePage!).