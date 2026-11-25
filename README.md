# Profitable Progress (fitness only)

Fitness, Calories, Camera (barcode scanner + food search) and Psyche.

## Get the APK
1. Create a new GitHub repository (Private is fine).
2. Upload everything in this folder, keeping the folder structure (www, assets, .github, package.json, capacitor.config.json).
3. Open the repository's Actions tab. The "Build Android APK" job starts by itself (or click it, then Run workflow).
4. Wait about 5 to 8 minutes for a green check.
5. Open the finished run and download "Profitable-Progress-APK" from Artifacts. Unzip it to get app-debug.apk.
6. Move app-debug.apk to your Samsung S24 FE, tap it, and allow "Install unknown apps" when asked.

## First launch
- Allow notifications (workout reminders and Psyche alarms).
- Allow the camera (barcode scanner). Barcode lookups need internet.
- For alarms to ring on time: Settings > Apps > Profitable Progress > Alarms & reminders > Allow,
  and set Battery to Unrestricted.

## Your logo
Replace the three images in the assets folder with your own, same file names, 1024x1024 PNG:
icon-only.png (full icon), icon-foreground.png (logo on transparent, kept in the middle 60%), icon-background.png (solid black).
