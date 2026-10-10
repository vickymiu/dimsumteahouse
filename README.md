# Dim Sum Teahouse website starter — replaceable logo and photos

## Files
- `index.html` — homepage
- `site-config.js` — phone, email, menu and social links
- `images/` — upload your logo and restaurant photos here

## Replace the logo
1. Prepare your logo image as a transparent PNG if possible.
2. Name it exactly `logo.png`.
3. Upload it into the `images` folder, replacing the placeholder file if one exists.
4. If your logo has a different filename, edit `src="images/logo.png"` in `index.html` to match it.
5. The logo is displayed inside a circular space; a square logo with transparent background usually works best.

## Replace the food photos
Upload photos to the `images` folder using these exact filenames:
- `hero-dim-sum.jpg` — large hero image at the top
- `dim-sum.jpg` — dim sum card
- `chinese-food.jpg` — Chinese food card
- `tea.jpg` — tea card
- `restaurant-interior.jpg` — restaurant/story image

Use JPG or PNG images. If using PNG, either rename to the matching `.jpg` and actually convert it to JPG, or update the matching filename in `index.html`. Best results: horizontal landscape photos, ideally 1200 px wide or larger. Use your own restaurant photos or images you have permission to use.

## Edit contact links
Open `site-config.js` and fill in the official phone, email, public menu URL and official social profile links.

## Booking form limitation
The current form opens a pre-filled email using the visitor's email app. It does not store bookings or send automatically; the visitor must press Send, and the restaurant must reply to confirm. For a hosted form that sends without opening the visitor's email app, connect a form service or Google Forms and test it before launch.

## Publish free with GitHub Pages
1. Create a public repository on GitHub.
2. Upload `index.html`, `site-config.js`, `README.md`, and the whole `images` folder.
3. Open Settings → Pages.
4. Select “Deploy from a branch”, choose `main` and `/(root)`, then Save.
5. Open the published URL and test all photos and links on mobile and desktop.
You can update the website later by uploading replacement photos with the same filenames. GitHub Pages hosting is free for public repositories; a custom domain is optional and normally costs annually.

## Map and Street View
The embedded map uses the supplied Faulkner Street address. Verify the pin and entrance before launch. Street View availability depends on Google's imagery.
