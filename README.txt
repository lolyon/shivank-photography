PORTFOLIO - HOW TO EDIT
=======================
1. Open index.html in any browser (double-click). Edit it in any text editor (VS Code, Notepad++, Sublime).
2. Everything you will want to change is in the <script> near the bottom, under "Edit these":
   - SITE: your name, email, Instagram link, location
   - CATS: the filter category names (must match the "c" value on each photo)
   - PHOTOS: one line per photo. s = image path, c = category, t = title, d = date,
     m = camera details, w/h = pixel size of the image, hero = true marks the opening photo (unused now; hero is images/hero.jpg)
3. To add a photo: drop the file in /images, then copy a PHOTOS line and change s, t, c, w, h.
4. Colours and fonts: the :root block at the top of the <style> section.
5. Text (tagline, About, Contact): search index.html for the sentence and edit it.
6. To put it online, upload the whole folder (index.html + images/) to any static host
   (Netlify Drop, GitHub Pages, Cloudflare Pages, etc).
