# Vexzion Lite MPA

Vexzion Lite is a Cloudflare Pages-ready multi-page file tools platform.

## Routes

- `/` homepage
- `/tools/` tools directory
- `/tools/<tool-id>/` individual tool pages
- `/categories/` category directory
- `/categories/<category>/` category pages
- `/pricing.html` separate pricing/payment page

## Cloudflare Pages settings

Framework preset: None  
Build command: leave blank  
Output directory: `/`

If Cloudflare requires a build command:

```txt
echo "No build needed"
```

## Backend

`_worker.js` handles the Cloudflare Pages API routes.

## Notes

This Lite version avoids heavy processor tools like video conversion, audio conversion, Office conversion, OCR, and AI tools. Those can be added later with a processing backend.
