# Qorably Redesign

A design canvas proposing a redesign of Qorably, an AI assisted QA test case tool, with five artboards (a project first home screen, the run automation preflight, Generate form validation, a mobile navigation drawer and a first run blank workspace) plus strategy notes.

Live page: https://oliveira-teixeira.github.io/design-qorably-redesign/

## Stack

- Claude Design canvas editor (preview build) packaged in a single HTML file, with the artboards stored as JSON inside the page
- React 19.2.7 and React 18.3.1, bundled inline
- Tailwind CSS v4.3.1, compiled into the page
- Artboards use Google Fonts: Inter
- claude.ai runtime: the page calls `window.claude`, using the self capability to save edits as a new version and the downloads capability to export files. Outside claude.ai the canvas opens view only and those features stay inactive.

Exported from a claude.ai artifact on 9 Oct 2026.
