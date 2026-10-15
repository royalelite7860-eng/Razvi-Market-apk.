# Razvi Market — mobile-friendly installable app

This is a simple static Progressive Web App (PWA) for Razvi Market. It is designed to work on mobile browsers and can be installed on an Android home screen after hosting over HTTPS.

## Included
- Product categories for Barkati Topi, Omani Topi, Qadri/Azhari/Embroidery Amama, customized gifts, attars, Janamaz, Hijab and Islamic books.
- Search, product details and WhatsApp enquiry buttons.
- Buy buttons open WhatsApp chat with `919227018919` and a prefilled product enquiry.
- Demo admin for adding/editing/deleting products, uploading your own photos, and exporting/importing a JSON catalogue.
- PWA manifest, icon and basic offline cache.

## Important limitations
- The admin PIN `2580` is a demonstration only, not secure authentication.
- Products and uploaded photos are saved in the current browser's local storage only. They do NOT sync to other phones or customers.
- To have full control from one phone and show product updates to every customer, connect a hosted database and real admin authentication (for example Supabase/Firebase) before public launch.
- This app does not collect payments. Payment, delivery and order confirmation are handled directly in WhatsApp as requested.
- Product photos are placeholders until the owner uploads their own original product images.
- No live website or APK is included in this ZIP; hosting/building is still required.

## Phone-only next steps
1. Upload the extracted files to a GitHub repository (upload the contents, not the ZIP itself).
2. Enable GitHub Pages in repository Settings → Pages, using the main branch/root.
3. Open the published HTTPS URL on Android Chrome. Use Chrome menu → Add to Home screen / Install app.
4. Before public use, replace the demo local-only admin with a secure shared backend. Do not rely on the demo PIN for private control.

## WhatsApp number
Configured as India country code +91 and number 9227018919.
