# Dimah Academy Students' Continuous Assessment Record

Offline-capable PWA based on the approved Students' Continuous Assessment Record structure with CSV exchange.

## CSV score exchange
- Open Assessment and choose **Download Blank CSV Template** to create a class-specific roster CSV with `Student Name, Admission Number, CA, Exam` columns.
- Enter the subject's assessment scores in the app, then open **Live Final Result** for that subject. Enter examination marks in the EXAM column if available and choose **Export CSV for Form Teacher**.
- The exported CSV contains the exact four columns expected by the report app's subject-score CSV import. In the report app, the form teacher should select the matching class, arm, subject and term before importing.

## Deployment
Upload the files in this folder to the root of a GitHub Pages repository. Data is stored locally in the browser. Use Settings → Data Management → Export Backup regularly.

Default login: `admin` / `admin123`. Change it in App / Admin Settings.


V32 updates: the default palette matches the Dimah Academy Report App; uploaded logo colours are sampled and applied to the login screen and app interface; the dashboard uses compact section tiles designed to show every section together on a phone screen; exact duplicate names in the same class trigger a warning, while differently spelled names are accepted; bulk import reports exact duplicates it skips. Existing CSV exchange, CA calculation, exam score persistence, offline support, and other features are retained.
