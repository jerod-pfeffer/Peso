# Peso — Weight Tracker

**Peso** is a lightweight, mobile-friendly web app for logging and tracking your body weight.  
It’s designed to run as a static site (no backend needed) and works perfectly when hosted on **GitHub Pages**.  

## Features
- 📅 **Date picker** (uses iOS/Android’s native rolling calendar)
- ⚖️ **Weight input in pounds** with 0.1 precision
- ✏️ **Edit / delete entries**
- 💾 **Stored locally** in the browser (data stays on your device)
- 📤 **Export options:**
  - Share / email CSV
  - Download CSV file
  - Copy CSV to clipboard
  - Print to PDF (clean export view)

## Usage
1. Open the app in Safari or Chrome.
2. Select a date and enter your weight (e.g., `175.4`).
3. Tap **Save Entry**.
4. Scroll down to see your history. You can edit or delete entries anytime.
5. Use the export buttons to back up or share your data.

## Deploy on GitHub Pages
1. Create a new **public** repo (e.g., `peso`).
2. Add `index.html` (and optionally this README).
3. Commit to the **main** branch.
4. In **Settings → Pages**, set:
   - Source: **Deploy from a branch**
   - Branch: `main` / `(root)`
5. Wait about a minute. Your app will be live at  
   `https://<your-username>.github.io/peso/`.

## Add to Home Screen (iPhone)
1. Open the URL in **Safari**.
2. Tap the **Share** button.
3. Choose **Add to Home Screen** → **Add**.  
   You now have a Peso app icon on your phone.

---

✅ Data is saved **only in your browser’s local storage**. No accounts, no servers, no tracking.
