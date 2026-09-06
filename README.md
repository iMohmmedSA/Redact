# Redact — live demo

A browser-only PII redaction tool. Paste text or drop a `.txt` / `.md` /
`.pdf` and it flags names, emails, phone numbers, national IDs, IBANs,
payment cards, credentials and locations — in English and Arabic — then
gives you a redacted copy. No backend, no upload: the document never leaves
your tab.

**→ https://imohmmedsa.github.io/Redact/**

This repository holds only the built static site so GitHub Pages can serve
it. On first scan the ~580 MB name/organisation/location model downloads
from the Hugging Face CDN and is then cached by your browser; your text is
never sent anywhere. A self-hosted build serves that model from its own
origin too.
