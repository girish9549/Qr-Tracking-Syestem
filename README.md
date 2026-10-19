# QR Bundle Tracking System

QR Bundle Tracking System ko GitHub par upload aur GitHub Pages se host karne ke liye package.

## GitHub par upload kaise karein

1. GitHub.com par login karein.
2. **New repository** par click karein.
3. Repository name rakhein: `qr-bundle-tracking-system`.
4. Public ya Private choose karein (agar GitHub Pages use karna hai to plan/settings ke mutabik access check karein).
5. **Add file → Upload files** par click karein.
6. Is folder ki `index.html` aur `README.md` files upload karke **Commit changes** karein.
7. Repository me **Settings → Pages** kholein.
8. **Deploy from a branch** choose karein, branch `main`, folder `/(root)` select karke **Save** karein.
9. Pages ka URL kuch der baad Settings → Pages par dikh jayega.

## Zaroori baat: data aur login

Is HTML file ki current configuration `local` mode par hai. Is mode me data browser/local computer me save hota hai. **GitHub Pages par upload karne se alag-alag PCs ka data automatically common nahi hoga.** Local-mode users/login bhi centralized authentication nahi hain.

Agar office ke sabhi PCs par same data/history chahiye, to app ko Firebase (ya doosre cloud database) se configure karna hoga. Iske liye Firebase project, Authentication, database rules aur app config set karne padenge. Firebase secrets/service-account keys kabhi `index.html` ya public GitHub repository me upload na karein. Browser Firebase config public ho sakti hai, lekin database ko secure rules se protect karna zaroori hai.

## Is package me kya hai?

- `index.html` — aapki di hui HTML app, GitHub Pages ke liye sahi entry filename.
- `README.md` — upload aur hosting ke steps.

Yeh package hosting ke liye tayyar hai; cloud database setup alag kaam hai.
