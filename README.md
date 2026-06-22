**A lightweight developer tool. Specially Optimised for mobile browsers.**

---


**Step 1**:
  - Copy the code below
```javascript
javascript:fetch("https://unpkg.com/famshot").then(r=>r.text()).then(eval)
```

**Step 2**: 
   - Save it as a bookmark
     - On desktop, open your bookmarks bar (`Ctrl+Shift+B` on Windows/Linux, `Cmd+Shift+B` on Mac), right-click and select **Add bookmark**, then paste the code above as the URL.
     - On mobile, first bookmark any page, then edit that bookmark and replace the URL with the code above. Give it a name like **DevTools** and save.

**Step 3**:
  - Open any web page, then tap or click the bookmark. The tool loads and runs automatically on that page.


**Notes**:
  - The javascript fetches the latest version of tool every time it is tapped or clicked
      - Always pulls from main branch, so any update pushed to the repo is live immediately.
  - It does not run automatically on page load, only when you trigger it
  - If nothing happens, the site may be blocking external scripts via its content security policy (CSP). This is expected on some sites.
