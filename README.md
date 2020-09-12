# ao3-hide-stats-site-skin
AO3 Site Skin to hide all user stats from browsing on Archive of Our Own (AO3), which means it applies to all laptop and mobile platforms. Provides clean interface to write and browse without seeing popularity of works. This is based off of the default skin - if anyone needs this for Reversi, please let me know.

Across all AO3 pages, hides the following:

- comments
- kudos
- views
- bookmarks
- comments button
- inbox button

**NOTE:** If you still wish the inbox to be visible, delete the following text in ao3-stats-hiding.css: a[href="/users/yourusername/inbox"]{display:none !important;}

1. On AO3, hover over your username and click My Dashboard.
2. Click Skins.
3. On the My Site Skins Tab (should be default), click the Create Site Skin button.
4. On the Create New Skin page that launches, enter a title (note it needs to be unique across entire AO3, so you may have to retry a few times to name it).
5. In the CSS section, paste all of the CSS that is in the ao3-stats-hiding.css file in this repository.
6. Replace the text yourusername with your ao3 pseudonym (without doing this, the inbox won't be hidden).
6. Click Submit.
7. This will take you to a page that shows the Site Skin you just created. At the bottom of the page, click Use to apply it.
