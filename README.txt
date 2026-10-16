Road to IRONMAN: install as an app on your phone
================================================

A web app has to be served from a web address (https) before a phone will
install it. Opening index.html straight from your files will show the plan,
but it won't install or work offline.

1. Put it online (free, about 2 minutes)
   Netlify Drop: open https://app.netlify.com/drop on a computer and drag this
   whole folder (the one containing index.html) onto the page. You'll get an
   https address. Create a free account if you want to keep the site.
   Or GitHub Pages: upload these files to a repository and turn on Pages.

2. Install it
   iPhone (Safari): open the address, tap Share, then "Add to Home Screen".
   Android (Chrome): open the address, tap the ⋮ menu, then "Install app" or
   "Add to Home screen".

3. Use it
   It opens full screen like an app and works offline after the first visit.
   Your numbers and ticks are saved in the phone's browser storage. Use
   "Save a backup file" under Your numbers now and then, and "Restore from
   backup" on a new phone.

Files
   index.html             the app
   manifest.webmanifest   app name, icon and colours
   service-worker.js      offline support
   *.png                  home-screen icons
