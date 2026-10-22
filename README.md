# Student Pickup — Demo

Static demo of the Guestrar student pickup flow.

- `index.html` — landing page
- `student-pickup-prototype.html` — clickable end-to-end prototype (admin web, parent portal, security app, Pickup Display)
- `parent-portal-flow.html` — all parent and pickup-person screens

Sample data only; no backend, SMS or real OTP (demo OTP is `1234`).

## Updating

The pages are generated from the design canvases in the app repo:

```bash
python3 docs/prototype/build_prototype.py   # in newGuetrar
cp docs/prototype/*.html /path/to/student-pickup-demo/
```

Commit and push; GitHub Pages redeploys automatically.
