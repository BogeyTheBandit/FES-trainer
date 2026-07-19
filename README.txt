FES INSTRUCTOR I — ADAPTIVE TRAINER (iPhone web app)
=====================================================

WHAT'S IN THIS FOLDER
  index.html            The entire app (all 120 questions built in)
  manifest.webmanifest  App settings (name, icon, full-screen mode)
  sw.js                 Makes the app work offline once installed
  icon-180.png          Home screen icon (iPhone)
  icon-512.png          App icon (larger displays)

HOW TO PUT IT ON YOUR IPHONE (one-time setup, ~10 minutes)

The app needs to live at a web address so Safari can install it.
The free, no-maintenance way is GitHub Pages:

  1. Create a free account at github.com (if you don't have one)
  2. Click the + in the top right > "New repository"
     - Name it: fes-trainer
     - Set it to Public
     - Click "Create repository"
  3. Click "uploading an existing file" and drag in ALL 5 files
     from this folder (not the folder itself, the files inside it)
  4. Click "Commit changes"
  5. Go to Settings > Pages (left sidebar)
     - Under "Branch" choose: main, folder: / (root) > Save
  6. Wait ~2 minutes. Your app is now live at:
     https://YOUR-USERNAME.github.io/fes-trainer/

ON YOUR IPHONE
  1. Open that address in SAFARI (must be Safari, not Chrome)
  2. Tap the Share button (square with arrow)
  3. Scroll down, tap "Add to Home Screen"
  4. Tap "Add"

Done. You now have an FES app icon on your home screen. It opens
full screen, works offline, and saves all your progress on the
phone itself.

PROTECT YOUR PROGRESS
  Your history is stored on the phone. Once a week, open the app,
  tap "Export progress", copy the text, and paste it into your
  Notes app. If you ever get a new phone or clear Safari data,
  tap "Restore from backup" and paste it back. Nothing lost.

ALTERNATIVE (zero setup): the version already in your Claude
project works inside the Claude iPhone app, and its progress is
saved to your Claude account automatically.
