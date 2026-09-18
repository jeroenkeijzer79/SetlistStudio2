Setlist Studio componentized

Shared components used by desktop.html and mobile.html:
- components/topbar.html
- components/library.html
- components/setlists.html
- components/active-setlist.html

styles.css remains shared. The pages load these fragments before the existing app script runs.
Use HTTP(S) hosting for reliable component loading; browsers may restrict XHR from file://.
