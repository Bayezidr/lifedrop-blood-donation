# LifeDrop — Real Online Blood Donation Network

## Firebase setup
1. Create a project at https://console.firebase.google.com/
2. Add a Web App.
3. Copy the Firebase Web SDK configuration.
4. Open `index.html` and replace the `PASTE_*` values in `firebaseConfig`.
5. Enable Authentication → Email/Password.
6. Create Firestore Database.
7. Use authenticated-user Firestore rules; do not leave a production database open to everyone.

## GitHub Pages
Repository: `Bayezidr/lifedrop-blood-donation`

GitHub → Settings → Pages → Deploy from branch → `main` → `/ (root)` → Save.

The site URL will be:
`https://bayezidr.github.io/lifedrop-blood-donation/`

The Firebase configuration is intentionally left as placeholders until you add your own project settings.

## Privacy
Donor phone numbers and blood information are personal data. Use consent, moderation, deletion procedures and restrictive Firestore rules before public/community use.