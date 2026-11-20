WEDDING PHOTOGRAPHY WEBSITE - HOW TO RUN IN VS CODE

OPTION 1 (easiest): Live Server
1. Unzip this folder.
2. Open VS Code > File > Open Folder > select "photo-studio-website".
3. When VS Code asks to install the recommended extension "Live Server", click Install.
   (Or open the Extensions tab and search "Live Server" by Ritwick Dey.)
4. Right-click index.html > "Open with Live Server". The site opens in your browser.

OPTION 2: Terminal (needs Node.js)
1. In VS Code open Terminal > New Terminal.
2. Run: npm start
3. Open the link it shows (usually http://localhost:3000).

OPTION 3: just double-click index.html (works in Chrome/Edge).

EDITING
- Prices, packages, team, phone, Instagram: open index.html, find <script id="data"> near the top, change values.
- Add photo: copy it into the media folder, add to "gallery":
  {"url":"media/new.jpg","cap":"","cat":"Wedding"}   (cat: Wedding / Pre-wedding / Haldi / Details)
- Add video (mp4, keep under ~20MB): copy into media, add to "films":
  {"title":"My Film","cat":"Wedding Film","url":"","video":"media/myfile.mp4","cover":"media/cover.jpg"}

GO LIVE: drag this folder to https://app.netlify.com/drop (free).
