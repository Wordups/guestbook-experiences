# Off the Record (working name)

Concept marketing site for two event recording experiences:

- **The Booth**: mirrored full-body video guestbook triggered by a retro phone.
- **The Confessional**: private seated video lounge with a CONFESS button.

Static site, no build step. Served by GitHub Pages from `main` at the repo root.

## Structure

```text
index.html                     The whole site (HTML, CSS, JS in one file)
images/                        Concept renders and screens from the working app
media/phone-booth-demo-v2.mp4     16s concept demo of the 3-2-1 sequence
media/phone-booth-demo-poster-v2.jpg
```

## Editing

- Copy lives directly in `index.html`. Search for the text you want to change.
- Colors and fonts are tokens at the top of the `<style>` block (`--gold`, `--wine`, `--display`, `--body`).
- The two on-page simulators are driven by the `EXPERIENCES` object near the bottom of the file. Add a new experience there.

## Status

- All booth and lounge images are concept renders, labeled as such on the page. Replace with event photography after the first builds.
- The inquiry form validates and confirms on screen but does not send anything yet. Connect it to the booking backend before launch.
- Brand name is a placeholder.
