# Just Drive Games

Nine two-minute games that teach kids to put the phone down. In memory of Mitchel Kiefer.

## Files
- index.html: the whole app (HTML, CSS, and JavaScript in one file)
- mitchel.jpg: photo used on the home screen
- icon.png: home screen icon

## Run it
Open index.html in any browser, or upload all three files to any web host (Netlify, Vercel, GitHub Pages, or mkiefer.org).
No build step, no server, no database. Google Fonts (Montserrat) loads from the web.

## Where things live in index.html
- Styles: the <style> block in <head>
- Games: each is one object in the <script> block (eyesup, goalie, aces, reaction, dnd, speak, spot, streak, quiz), plus the pledge
- Home screen grid: built from the GAMES list near the end of the script
- APP_URL: the link the Share button sends. Change it once the app has its permanent address.
