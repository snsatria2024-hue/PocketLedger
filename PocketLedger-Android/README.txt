POCKET LEDGER - Android app (works offline, data stays on your phone)

You need ONE of these two ways to turn this folder into an APK file.

WAY 1 - GitHub (no Android Studio, free)
 1. Make a free account at github.com and create a new repository (private is fine).
 2. Upload everything in this folder to it. The folder named ".github" must be included.
    (Easiest on a computer: unzip, then drag all files and folders into the repository page.)
 3. Open the "Actions" tab > "Build APK" > "Run workflow". Wait about 5 minutes.
 4. Open the finished run, download "PocketLedger-apk", unzip it, and you get app-debug.apk.
 5. Send app-debug.apk to your phone and open it. Allow "Install unknown apps" when asked.

WAY 2 - Android Studio (on a computer)
 1. Install Android Studio, choose File > Open and pick this folder.
 2. Wait for Gradle sync, then Build > Build APK(s). Copy the APK to your phone.

Needs Android 10 or newer.
Backups: Settings > Save backup writes a file to your phone's Downloads folder.
Uninstalling the app erases its data, so save a backup first.
