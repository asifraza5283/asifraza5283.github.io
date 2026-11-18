# Asif Raza — personal academic website

Live at **https://asifraza5283.github.io**

Plain HTML and CSS, hosted free on GitHub Pages. Any change you commit goes live in about a minute.

## What is where

| File | What it contains |
|---|---|
| `index.html` | Home page: name, position, intro, photo, research overview |
| `academic-background.html` | Current position, education, teaching, internship, CV |
| `research.html` | The four research projects with figures |
| `publications.html` | Journal articles and conference talks |
| `achievements.html` | Fellowships, awards, academic distinctions, leadership, hobbies |
| `gallery.html` | Conference photos with captions |
| `courses.html` | Coursework |
| `contact.html` | Address, email, phone, profile links |
| `styles.css` | All colours, fonts and layout (shared by every page) |
| `images/` | `profile.jpg`, `logos/`, `research/`, `gallery/`, `hobbies/` |
| `cv.pdf` | Your CV (upload it with exactly this name) |

## How to edit (in the browser, no software needed)

1. Open the repository on github.com and click the file you want to change (e.g. `publications.html`).
2. Click the **pencil icon** (top right of the file) to edit.
3. Make the change. Every section has a comment like `<!-- ===== JOURNAL ARTICLES ===== -->` so you can find it. Text between the tags is what shows on the page.
4. Click **Commit changes** (green button), then **Commit changes** again.
5. Wait about a minute and refresh your site (Ctrl+Shift+R / Cmd+Shift+R).

Tip: on the repository page, press the **`.`** key to open a full editor (github.dev) in your browser. It's handy for editing several files at once. Commit from the left-hand "Source Control" panel.

## Common edits

**Add a journal paper** (`publications.html`): copy one whole `<li> ... </li>` block in the Journal Articles list, paste it at the top of the list, and change the authors, title, journal and the two links.

**Add a gallery photo**: upload the photo into `images/gallery/` (Add file → Upload files). Then in `gallery.html` copy one `<figure> ... </figure>` line and change the file name (twice) and the caption.

**Add a new conference section in the gallery**: copy a whole `<section class="section"> ... </section>` block in `gallery.html` and change the heading, place, date and photos.

**Change your photo**: upload a new photo named `profile.jpg` into `images/`. GitHub will ask to replace the old one.

**Update your CV**: upload the new PDF as `cv.pdf` to the main folder (it replaces the old one).

**Change a link**: find the text, and change the address inside `href="..."` just before it.

**Change colours or fonts**: open `styles.css`; the colours are listed at the top under `:root`. Change `--accent` to change the highlight colour everywhere.

**Add your cricket photos** (`achievements.html`): upload them into `images/hobbies/`, then in the Hobbies section delete the two lines that say `PHOTOS START` and `PHOTOS END`, and change the file names and captions.

**Add an award** (`achievements.html`): copy one `<li> ... </li>` line in the right list and change the text and year.

**Edit the top menu or footer**: these are repeated on every page, so make the same change in all eight `.html` files.

## Things to keep in mind

- File names are case-sensitive: `Photo.JPG` and `photo.jpg` are different files.
- Avoid spaces in file names; use hyphens (`emi-07.jpg`).
- Compress photos before uploading (e.g. tinypng.com); aim for under 400 KB each.
- If something breaks, open the file's **History** on GitHub to see or restore an earlier version.
