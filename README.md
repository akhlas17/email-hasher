# Email Hasher

Hash CSV email addresses to SHA-256 locally in your browser. No server, no uploads.

## Live demo

Use the deployed app at [akhlas17.github.io/email-hasher](https://akhlas17.github.io/email-hasher/).

## Quick start

1. Open the [live app](https://akhlas17.github.io/email-hasher/) or `index.html` locally in any modern browser.
2. Upload a CSV with first row `email`, one address per line.
3. Click **Process** → **Download hashed CSV**.

## CSV format

```
email
user@example.com
other@domain.org
```

## Notes

- 100% client-side — data never leaves your device
- Output: 64-char lowercase hex (Meta-compatible)
- Handles large files (50k–500k+ rows) with progress
- UTF-8, Poppins font
