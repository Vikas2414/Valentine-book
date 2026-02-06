# Entry page (password gate)

This folder includes `entry.html` — a simple local password gate that mimics an entry page.

Features
- Hint displayed: "51ST DATE"
- Password: `21022026` (DDMMYYYY — your wedding date)
- On correct entry the page redirects to `index.html` (local)

How to test locally (Windows PowerShell)
1. Open the project folder in PowerShell and run:

```powershell
ii .\entry.html
```

2. Enter the password `21022026` and click "Unlock ❤️". The page will redirect to `index.html` if present.

Notes
- This is a static client-side gate (no server). For higher security you'd implement server-side validation.
- If you want the unlocked content to be shown inline (instead of redirecting), or want different styling/animations, tell me and I can update it.
