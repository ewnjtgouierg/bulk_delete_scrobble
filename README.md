# bulk_delete_scrobble
how to delete lots of accidental/error scrobbles from last.fm relatively quickly

1. go to your library page (e.g. recent -> more tracks)

3. open devtools / console, copy paste this:

for (var button of document.querySelectorAll('[class*="more-item--delete"')) button.click();

3. hit Enter - this will delete 50 last scrobbles

4. hit F5 and repeat from step 3 as many times as required
