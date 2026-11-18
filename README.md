# GSC GDh. Staff Dashboard

Quick-access dashboard for staff of the Government Services Centre – Gaafu Dhaalu Atoll.

- Live site: https://iyaash-ahmed.github.io/gsc-gdh-dashboard/
- Protected by a 4-digit PIN. The app links are stored encrypted (AES-256-GCM, key derived from the PIN with PBKDF2-SHA256, 310,000 iterations), so they cannot be read from the page source without the PIN.
- The page asks search engines not to index it.

To change the links or the PIN, regenerate `index.html` with the build script (kept outside this repo).
