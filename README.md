# Mohamed Khaled Eissa | AI Engineer

A responsive, dependency-free portfolio focused on Generative AI, RAG, AI agents and workflow automation.

## Stack and hosting

Plain HTML, CSS and JavaScript. GitHub Pages serves the root of the `main` branch. No build process, API keys, paid APIs or backend are needed. Google Fonts is the only optional third-party request; local system fonts are fallbacks.

## Updating content

- Edit `index.html` to update project descriptions, skills, experience, education and contact links.
- Each project is an `<article>` with a `data-category` of `genai`, `automation`, or `ml`.
- The CSS is in the `<style>` block near the top of `index.html`.
- JavaScript is in the `<script>` block at the end of `index.html`.
- Commit changes to `main`; GitHub Pages republishes automatically.
- Upload a 1200 x 630 sharing image, then update the `og:image` URL in `index.html`.

## Features

Responsive mobile navigation, category filters with accessible pressed state, native project/skill disclosures, reduced-motion support, skip link, smooth scrolling, keyboard focus styles, back-to-top link and email clipboard action.

Contact uses `mailto:` and copying an address, not a form that pretends to submit. No visitor tracking is included. Project illustrations explain architecture; they are not screenshots of running products.

## Local preview

Run `python3 -m http.server 8000` from this folder, then visit `http://localhost:8000`.

## Content boundaries

Project descriptions are based on the owner's GitHub READMEs and supplied professional information. EduPilot AI is explicitly described as an early-stage graduation project, not a completed platform. Hotel operations is deterministic automation, not an AI payment system. No invented client results or professional metrics are included.

## Sharing artwork

![Portfolio sharing artwork](https://github.com/user-attachments/assets/86608f7a-4197-4ceb-aa62-0f9fcebed052)
