# whileyouwait

Static coming-soon page for whileyouwait.io.

## Local Preview

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

## Files

- `index.html` contains the page markup, styles, analytics tag, and marquee behavior.
- `assets/wyw-logo.png` is the logo used in the page lockup.
- `assets/linkedin-icon.png` is used as the LinkedIn icon mask.
- `favicon.svg` is the browser icon.
- `og-image.jpg` is the social sharing image referenced by Open Graph and Twitter/X tags.

## Notes

- There is no build step or package manager.
- Google Analytics uses measurement ID `G-Z4JKYTF3BC`.
- The page requests Alte Haas Grotesk Bold via local font lookup. Add a webfont file and update `@font-face` if the font needs to render consistently for all visitors.
- Keep social image metadata in sync with the actual image filename, MIME type, and dimensions.
