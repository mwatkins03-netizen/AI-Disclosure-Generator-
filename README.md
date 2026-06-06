# AI Disclosure Note Generator

A single-file, self-contained web tool that helps students generate a clear,
student-friendly AI use disclosure based on the AI Assessment Scale (AIAS),
with a disclosure format inspired by Monash University.

Author: Marc Watkins · Licensed CC BY 4.0 · Built with AI assistance.

## How to host it on GitHub Pages

1. Create a new repository (for example, `ai-disclosure`).
2. Upload **`index.html`** (keep the name lowercase — this is required).
3. Go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/ (root)**, then **Save**.
6. Wait about a minute. Your tool will be live at:
   `https://<your-username>.github.io/<repository-name>/`

## Most common reason it "doesn't work"

GitHub Pages is **case-sensitive** and only serves a file named exactly
`index.html` (all lowercase) as the homepage. A file named `Index.html`,
`INDEX.html`, or anything else shows a 404 at the root URL. This package
already uses the correct lowercase name.

## Embedding in Blackboard

Add an HTML item and paste:

    <iframe src="https://<your-username>.github.io/<repository-name>/"
            width="100%" height="900" style="border:0"
            title="AI Disclosure Note Generator"></iframe>

## Privacy

Runs entirely in the browser. No data is collected, stored, or transmitted.
