# Auto-generated README (Round 2)

**Project brief:** Show an aria-live alert #github-status that reports when a lookup starts, succeeds, or fails. Display account age in #github-account-age. Cache last lookup in localStorage under github-user-.

**Attachments:**


**Checks to meet:**
document.querySelector('#github-status').getAttribute('aria-live') === 'polite'\n!!document.querySelector('script').textContent.includes('github-status')\nparseInt(document.querySelector('#github-account-age').textContent, 10) >= 0\ndocument.querySelector('#github-account-age').textContent.toLowerCase().includes('years')\n!!document.querySelector('script').textContent.includes('localStorage.setItem(github-user-')\n!!document.querySelector('script').textContent.includes('localStorage.getItem(github-user-')

## Setup
1. Open `index.html` in a browser.
2. No build steps required.

## Notes
This README was generated as a fallback (OpenAI or AI Pipe failed).