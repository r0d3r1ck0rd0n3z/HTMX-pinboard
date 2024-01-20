# HTMX pinboard


See demo here:
https://r0d3r1ck0rd0n3z.github.io/HTMX-pinboard/


Uses HTMX to create a minimal pseudo pinterest-clone. Note that this is very barebones and minimal as it was only created for self-study.


HTMX loads all text files saved in the `text` directory and displays them as an ideaboard (via CSS magic).


It works, but getting files to show updates is painfully slow. The 'refresh time' is very dependent on how fast GitHub cascades the changes to its CDN:
* [How long do GitHub Pages take to update?](https://joshdance.medium.com/how-long-do-github-pages-take-to-update-52018f98f781)
* [How long does it take for GitHub page to show changes](https://stackoverflow.com/questions/24851824/how-long-does-it-take-for-github-page-to-show-changes-after-changing-index-html)


It's possible to add more functions via the GitHub API, which requires generating a GitHub token. Maybe some other time.  ^__^ 
<br>
