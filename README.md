# Alex Morgan — Personal Portfolio (Demo)

A responsive 4-page static portfolio built using **HTML5, CSS3, Bootstrap 5 and vanilla JavaScript**.

## Pages
- `index.html`: Home, sticky navigation, hero, skills/education/projects highlights, footer.
- `about.html`: Biography, academic background, progress bars, soft skills, interests.
- `gallery.html`: Responsive photo gallery and HTML5 motivation video section.
- `contact.html`: Contact details, validated form (mailto), OpenStreetMap embed.

## Customize before submitting
1. Replace **Alex Morgan**, **Example University**, the degree, biography and coursework with your real details.
2. Replace demo contact details (`student@example.com`, `+256 700 000 000`) and GitHub/LinkedIn URLs in all pages and `js/script.js`.
3. Replace SVG images in `images/` with your own photos/screenshots and update HTML `src` and `alt` text.
4. **Mandatory:** record yourself explaining your motivation for your degree. Save the recording as `videos/motivation.mp4` (H.264 MP4) so the HTML5 player loads it. The provided ZIP intentionally contains no fabricated personal video.
5. Update the demo skill percentages and sample project claims to reflect your own work.

## Contact form
The form validates required fields and opens a prepared message using `mailto:`. It **does not send emails automatically** because GitHub Pages is static hosting. Replace the placeholder email in both `contact.html` and `js/script.js`. For real online submissions, integrate a reputable form endpoint/service.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server 8000` inside this folder and visit `http://localhost:8000`. Bootstrap, Bootstrap Icons and Google Fonts need internet access.

## Suggested incremental Git commits
```bash
git init
git add index.html about.html gallery.html contact.html
git commit -m "Create portfolio pages and navigation"
git add css images
git commit -m "Style responsive layouts and add gallery illustrations"
git add js videos README.md
git commit -m "Add form validation, video placeholder and documentation"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```
Create an empty public GitHub repository first, and configure Git user identity if required. The commits shown are suggested steps, not an existing commit history.

## Publish with GitHub Pages
1. Open your GitHub repository → **Settings** → **Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select `main` and `/ (root)` → **Save**.
4. After deployment, the site should be at `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.
5. Submit **both** the repository URL and live Pages URL, plus the project ZIP.

## Credits
Demo SVG illustrations were generated for this project. Framework: Bootstrap 5.3.3 via jsDelivr; icons: Bootstrap Icons 1.11.3; fonts: Google Fonts; map: OpenStreetMap embed.
