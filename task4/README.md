# Responsive Webpage Conversion

This project updates a static desktop-only HTML page to be fully responsive using CSS Flexbox and media queries.

## ✅ Key Enhancements

- **Meta Viewport Tag**: Enables proper scaling on mobile devices.
- **Flexible Containers**: Converted fixed widths to percentage-based widths using `.container`, `.row`, and `.col`.
- **Responsive Typography**: Font sizes adjusted for smaller screens.
- **Responsive Navigation**: Horizontal navigation collapses into a vertical stack on screens ≤768px.
- **Media Scaling**: Images now scale with container using `max-width: 100%` and `height: auto`.
- **Touch Optimization**: Comfortable spacing added for links and readable font sizes.

## 🧪 How to Test

1. Open `index.html` in Chrome.
2. Open **Chrome DevTools (F12)** → Click **Device Toolbar (Ctrl+Shift+M)**.
3. Test on devices like:
   - iPhone SE (375×667)
   - iPhone 12 Pro (390×844)
   - iPhone XR (414×896)
4. Confirm:
   - No horizontal scrolling
   - Navigation stacks vertically
   - Images and text scale correctly
   - Text is readable and links are tap-friendly

## 📸 Screenshots to Capture (manually in DevTools)

1. **Desktop View** (e.g., 1280px wide)
2. **Mobile View** at:
   - 375×667 (iPhone SE)
   - 390×844 (iPhone 12 Pro)
   - 414×896 (iPhone XR)

Take screenshots from Chrome DevTools and attach them for submission.

---

## 📁 Files Included

- `index.html` – Updated HTML with viewport
- `style.css` – Responsive CSS
- `README.md` – Summary of changes
