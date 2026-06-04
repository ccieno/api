# API Demo Pages

A static GitHub Pages site hosting interactive demo pages for Zoom Contact Centre API calls. Used for live demonstrations and testing ZCC integrations.

## Contents

| Path | Description |
|---|---|
| `index.html` | Landing page |
| `zoom/index.html` | Zoom API demo index |
| `zoom/webleads.html` | Web leads / address book contact creation demo |
| `zoom/copy.html` | Copy utility page |

## How it works

The pages are plain HTML with embedded JavaScript that calls Zoom Contact Centre APIs directly from the browser (via a worker proxy or directly). They're designed for use during demos and sales calls — no build step required.

The site is deployed via GitHub Pages. The `CNAME` file points the custom domain.

## Local development

Open any `.html` file directly in a browser. No server or build process needed.
