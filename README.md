# Color Studio

A small, self-contained color tool built with HTML, CSS, and JavaScript. It runs as a normal web page and can also be embedded in a Framer project page.

## Run it on your computer

Open `index.html` in a web browser. No install or build step is needed.

## Publish it with GitHub Pages

GitHub Pages can publish this project directly because the app is a static web page. Publishing makes the app available publicly on the internet.

1. Save your changes in Git, then push them to the repository's `main` branch.
2. On GitHub, open this repository and choose **Settings**.
3. In the sidebar, choose **Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main**, folder **/(root)**, then choose **Save**.
6. Wait for GitHub Pages to finish its first deployment. The **Pages** screen will show the public website address.

For this repository, the expected address is `https://colbyfrancis.github.io/color-builder/`. Add `?embed=1` to that address when embedding Color Studio so it opens without the standalone page heading and footer.

GitHub's guide: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Add it to the Color Studio Framer CMS page

1. Open the Framer CMS project page for Color Studio.
2. Add an **Embed** component where you want the interactive tool to appear.
3. Paste the published app address with `?embed=1` at the end.
4. Set the Embed component to the width of the content column. Give it enough height to show the complete app; check both desktop and mobile previews and adjust the height at each breakpoint if needed.
5. Add the written case study and images as regular Framer content below the Embed component.

The embed mode only hides Color Studio's outer page heading, introduction, and footer. The editor, color palette, locks, refresh controls, and SVG export remain in the app.
