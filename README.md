# boyantasevski.github.io

Public pages for Boyan Tasevski's iPhone apps, served free by GitHub Pages.

Each app has its own folder with the two pages App Store Connect needs:

- `meals/` — app page and `icon.png`
- `meals/privacy/` — Privacy Policy URL: https://boyantasevski.github.io/meals/privacy/
- `meals/support/` — Support URL: https://boyantasevski.github.io/meals/support/

## Adding the next app

1. Copy the `meals` folder and rename it to the app's short name.
2. Rewrite both pages for that app. The privacy policy must describe exactly what the app does with data.
3. Add the app to `index.html`.
4. Push to `main`. GitHub Pages publishes within a minute or two.

## Keeping the privacy policy true

Update `privacy/index.html`, with a new date, before releasing any version that sends a new kind of data off the phone. At most two things leave it: barcode numbers (Open Food Facts) and, where the app's closer look is switched on, plate photos (Apple's Private Cloud Compute, which keeps nothing). In the app's builds so far the closer look is off.
