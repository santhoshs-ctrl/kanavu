KANAVU - songs website

FILES
 index.html  - public website (songs play aagum)
 songs.json  - songs list
 songs/      - un MP3 files inge podu
 covers/     - song cover images (jpg/png, square nalladhu) inge podu
 admin.html  - songs.json-ah easy-ah create panna (sirf neenga use pannunga, public-ku link kudukaadheenga)

HOST PANNA (FREE)
 Netlify: app.netlify.com/drop -> indha folder-ah drag & drop.
 (illana GitHub Pages / Cloudflare Pages)

SONG ADD PANNA
 1. MP3-ah songs/ folder-la, cover image-ah covers/ folder-la podu
 2. admin.html open panni title + file name add pannu, songs.json download pannu
 3. songs.json-ah replace panni, folder-ah thirumba upload pannu

SONG DELETE PANNA
 songs.json-la irundhu entry remove pannu, MP3-ah folder-la irundhu delete pannu, thirumba upload pannu.

NOTE: local-la file:// la open panna songs load aagaadhu; hosting-la (or "python -m http.server") use pannunga.
