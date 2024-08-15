# bulk_delete_scrobble
how to delete lots of accidental/error scrobbles from last.fm relatively quickly

open devtools / console, copy paste this:

for (var button of document.querySelectorAll('[class*="more-item--delete"')) button.click();

and hit Enter
this will delete 50 last scrobbles

then hit F5 and repeat as many times as required
