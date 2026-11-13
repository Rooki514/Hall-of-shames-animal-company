# Hall of Shame

A website made of three files: index.html, stories.js and this README. No server, no database, no account.

## On an iPad or phone
Opening index.html from the Files app does not run the site, so put it online and open the address in Safari.
GitHub Pages works from Safari:
1. Tap the zip once in Files to unzip it.
2. On github.com create a repository, tap Add file > Upload files, and upload index.html and stories.js.
3. Open Settings > Pages, choose Deploy from a branch, pick main and the root folder, and save.
After a minute your site is at https://YOUR-NAME.github.io/REPOSITORY-NAME/. Any other static host works too.

## One-tap publish (GitHub)
1. On github.com open Settings > Developer settings > Personal access tokens > Fine-grained tokens > Generate new token.
2. Under Repository access choose Only select repositories and pick your site's repository.
3. Under Permissions > Repository permissions set Contents to Read and write. Generate the token and copy it.
4. On your site, enter your PIN, write something, and tap Publish now. The first time, type your GitHub username, the repository name and paste the token. They are saved only in that browser.
Visitors see the update about a minute later. Never share the token. If it leaks, delete it on GitHub and make a new one.

## Publish by hand (no token)
1. Open your site, tap through the logo and enter your PIN. The first time, you create one.
2. Add stories, conspiracy theories and supporters.
3. Tap "Copy as text" in the bar at the top. In your GitHub repository open stories.js, tap the pencil, select all, paste, and tap Commit changes.
   Or tap "Download stories.js" and upload it over the old one. Safari may rename a repeat download to "stories 2.js", so copying is safer.
Visitors see the update a minute after you commit. What you write is kept as a draft in that browser until then.
Safari can clear a site's saved drafts after about a week without a visit, so publish soon after writing.

## On a computer
Double-click index.html and it works as it is. To share it, upload the files to any static host.

## Light and dark
The Theme button at the top right cycles Auto, Light and Dark and remembers your choice.

## About the PIN
The PIN is stored as a hash inside stories.js, so a determined person could download the file and try all 10,000 four-digit PINs.
It keeps casual visitors out of the writing tools. What really protects the site is that only you can change files on your host.
