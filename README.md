# Kay's Calendar V6

1. Export a backup from the current laptop calendar.
2. Run `supabase-setup.sql` once in Supabase SQL Editor.
3. In Supabase Authentication URL Configuration, set Site URL and Redirect URLs to the final HTTPS address.
4. Upload this folder's contents unchanged to an HTTPS static host. Do not use `file://`.
5. Open the hosted address on the laptop, sign in, and let it show Synced.
6. On iPhone and iPad, open the same address in Safari, choose Share > Add to Home Screen, launch the icon, and sign in with the same account.

The mobile week and month views preserve event text through horizontal swipe, dialogs use safe-area-aware bottom sheets, and the desktop layout remains intact. Never add a Supabase service-role or secret key to browser files.
