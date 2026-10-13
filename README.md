# LUMORA Gold Curtain Launch Countdown

Static, mobile-friendly Vercel website using a black/navy + gold cinematic launch style, countdown, curtain-opening reveal, $37/month offer and $10 daily goal.

## Files
- `index.html` — full website and countdown logic
- `assets/lumora-logo.png` — supplied LUMORA logo
- `assets/reference-design.png` — user-provided reference image

## Before publishing
- Replace `YOUR_EMAIL@example.com` in `index.html` with a real support email, or replace the button `href` with your sign-up/payment URL.
- The launch time is set to `2026-10-15T10:00:00+05:30` (Sri Lanka time). Change it if the launch time has changed.
- `$10 daily profit goal` is labelled as a target, not guaranteed income.

## Vercel
1. Extract this ZIP.
2. Upload `index.html` and the whole `assets` folder to a GitHub repository.
3. In Vercel, create a new project and import that repository.
4. Choose the `Other` framework preset. No build command is needed; output directory can be `.`.
5. Deploy and share the `.vercel.app` URL.


## Updated launch behavior
- When the countdown reaches zero, the reveal takes over the full browser viewport and the curtains open.
- The `Get Started Now` button navigates to https://lumora-scalp.vercel.app/.
