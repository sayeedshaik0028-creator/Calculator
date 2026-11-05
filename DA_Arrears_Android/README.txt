D.A ARREARS CALCULATOR - ANDROID PROJECT

This wraps your supplied calculator HTML in a standalone Android app named D.A Arrears Calculator.
It keeps the existing calculator fields, formulas, add-month/surrender controls, local saved data and Excel export. In the Android app, Excel exports are saved to the phone's Downloads folder.

BUILD THE APK WITHOUT A COMPUTER (using GitHub Actions)
1. On your phone, open https://github.com and sign in or create an account.
2. Create a NEW PUBLIC or PRIVATE repository named DA-Arrears-Calculator.
3. Upload the CONTENTS of this ZIP (not the ZIP itself) into the repository. Make sure .github/workflows/build-apk.yml is included. If the GitHub mobile page hides dot-folders, use your browser's Desktop site or upload using github.com in desktop mode.
4. Open the repository's Actions tab. Enable Actions if asked.
5. Choose 'Build D.A Arrears Calculator APK' and tap 'Run workflow'. (A push to main also starts a build automatically.)
6. Wait for the green success check. Open the completed workflow run, scroll to Artifacts, and download 'DA-Arrears-Calculator-APK'.
7. Extract the downloaded artifact ZIP. Tap app-debug.apk and install it. If Android asks, allow your browser/file manager to install unknown apps.

IMPORTANT
- This is a debug APK for personal installation/testing, not a Play Store release.
- The spreadsheet export library is loaded from the internet (cdnjs), so Excel export requires an internet connection.
- The HTML calculator's calculation formulas and default sample values are retained from the supplied file. Review sample employee details before using real data.
- Never upload confidential employee information to a public repository. The source project contains the calculator's original default sample data; choose a private repository or remove sample details before uploading.
