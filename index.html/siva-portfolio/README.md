# Siva Charan — My first portfolio

A responsive portfolio with a continuous Earth → atmosphere → space → solar system → galaxy → universe flight. Scroll or use the chapter dots to explore. The locally rendered sphere uses approximate continent shapes, orbital planets, star depth, scroll-triggered flight streaks, and a spiral galaxy. No external 3D library is required.

## Preview

Double-click `dist/index.html` to open it in your browser. Internet access is optional and only used for the Google Fonts; system fonts work offline.

For a local server, run `node server.cjs` in this folder, then visit http://localhost:4173.

## Save your first commit

Open a terminal in this folder and run:

```powershell
git status
git add dist README.md server.cjs .openai/hosting.json
git commit -m "Build my first portfolio"
```

The publishing workflow may already have created the first commit. Run `git log --oneline -3` to see your snapshots. After editing files, repeat `git add` and `git commit` with a message describing the change.

If Git requests your identity, set your own name and email using `git config user.name "Your Name"` and `git config user.email "your actual email"`, then retry the commit.

## Make it yours

- Edit your introduction, education, and skills in `dist/index.html`.
- Add real projects to the Work section when ready.
- Edit your email, phone, and LinkedIn links in the Contact section. Add a GitHub link when available.
- The opening portrait is AI-stylized from the supplied face photo and labeled accordingly. Replace `dist/siva-portrait.png` to change it.
- The supplied 98% is displayed under Intermediate education. Correct it if you intended another qualification.
- Base styles live in `dist/style.css`; the cosmic theme and responsive layouts live in `dist/cosmic.css`.
- Scene rendering and scroll transitions live in `dist/cosmic.js`.
- This is an original Earth-to-universe interpretation; the reference website could not be inspected.
- Use the footer motion button to pause the animation. Device reduced-motion preferences are respected automatically.
