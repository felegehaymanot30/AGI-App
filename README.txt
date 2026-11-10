HOW TO GET YOUR .APK (no hidden folders needed)
1. Create a free account at github.com and make a NEW repository.
2. Click "uploading an existing file" and drag in: www (folder), package.json, capacitor.config.json. Commit.
3. Click Add file > Create new file. In the name box type exactly:
      .github/workflows/build-apk.yml
   (typing the "/" creates the folders for you).
4. Open workflow-copy/build-apk.yml.txt from this zip, copy ALL its text, paste it into the big box, click Commit.
5. Open the Actions tab > "Build APK" > wait ~5 minutes for the green check.
6. Open the finished run > Artifacts > download "Aurelia-APK" (zip holding app-debug.apk).
7. Send app-debug.apk to your phone, tap it, allow "Install unknown apps", install.
