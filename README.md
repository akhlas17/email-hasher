# Email Hasher

Hash CSV email addresses to SHA-256 locally in your browser. No server, no uploads.

## Quick start

1. Open `index.html` in any modern browser.
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
