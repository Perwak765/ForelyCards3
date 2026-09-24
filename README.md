# ForelCards — phone-safe build

This version is packaged for opening from Android file managers (including content:// URLs). CSS and JavaScript are embedded directly into index.html, so the page does not depend on sibling style.css/app.js files loading.

## On Android
1. Extract the ZIP.
2. Open `ForelCards_USE_MY_FISH/index.html`.
3. To add cards, open `admin/admin.html` in the same browser/profile.

Cards are stored in the browser's localStorage. They are not automatically transferred between phones/browsers. If a browser blocks storage for content:// pages, use the same browser/profile or a local web server.
