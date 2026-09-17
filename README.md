# Need & Know — complete website

Includes the globe hero, all brand assets, founder photos, platform preview, UN SDG logo, and the four SVG illustrations in section 07.

## Run locally

From this extracted folder:

```sh
python3 -m http.server 8000 --directory dist
```

Then visit http://localhost:8000. Use a local server because the page loads content.json with fetch.

## Edit

- dist/content.json: text and structured content
- dist/app.js: sections and interactions
- dist/styles.css: styling and responsive layout
- dist/index.html: page shell and metadata
- dist/assets/: complete image and SVG assets

Section 07: #starting. SDG alignment panel: #sdg-alignment.
The Switzerland, Conversations and Pilot SVGs are white; Climate Action retains its supplied green colour.

## Hosting

Upload the contents of dist to any static web host. No build step or dependencies are required.
.openai/hosting.json identifies the existing Sites project; it is unnecessary on other hosts.

Source revision: 550770b163a46ba0d3b79f97700e278df80a71ba
