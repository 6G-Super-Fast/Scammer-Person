# Verified Fraud Alert List & Admin Panel

Ye project specifically GitHub Pages ke liye banaya gaya hai jisme aap **Admin Panel** (`admin.html`) ke zariye direct entry kar sakte ho aur woh automatically `data.json` mein store hokar **Index.html** par live show hone lagegi.

## Features:
1. **Admin Panel (`admin.html`)**:
   - Screenshot upload karo (automatically base64 / json format mein convert hota hai).
   - WhatsApp URL enter karo.
   - GitHub API integration ke zariye direct `data.json` update/commit hota hai.
   - View Data List, Edit Data, aur Delete options available hain.
2. **Public Index (`index.html`)**:
   - `#S_NO. 1`, `#S_NO. 2`, `#S_NO. 3` format mein direct cards show karta hai.
   - Image preview modal aur WhatsApp direct chat button.

## Setup Instructions:
1. GitHub par ek naya repository banao (e.g. `fraud-list`).
2. Yeh saari files (`index.html`, `admin.html`, `data.json`) us repository mein upload kar do.
3. GitHub Settings -> Pages par jaakar branch select karo (`main` / `root`) aur save karo.
4. Apni site open karo: `https://<your-username>.github.io/<repo-name>/admin.html`
5. Admin panel mein apna **GitHub Username** aur **Repository Name** dalo. Ab aap wahan se naye fraud records add, edit aur delete kar sakte ho!
