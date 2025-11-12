# ScholarSpot
ScholarSpot

## Deploying to Vercel (Windows PowerShell)

1. Install Vercel CLI (optional):

```powershell
npm install -g vercel
```

2. Login to Vercel:

```powershell
vercel login
```

3. (Optional) If you need Firebase CLI for emulation or functions:

```powershell
npm install -g firebase-tools
firebase login
```

4. Deploy from the project root:

```powershell
cd "c:\Users\VISHNU V\Downloads\Study-Adda-main (1)\Study-Adda-main"
vercel --prod
```

Notes:
- Firebase client config values were updated in HTML files to the values you provided.
- Uploadcare public key was updated to `a7207f99523ca79a93d9` in `chat.html` and `dashboard.html`.
- Consider securing any server-side secret (if you add one) by using Vercel Environment Variables.

## Deploying to Firebase Hosting (Windows PowerShell)

1. Install Firebase CLI (if not already installed):

```powershell
npm install -g firebase-tools
```

2. Login to Firebase:

```powershell
firebase login
```

3. Ensure the `.firebaserc` `default` project is set to your Firebase project ID (`ss99-a0bc7`). If you want to use a different project, run:

```powershell
firebase use --add
```

4. Deploy hosting (from project root):

```powershell
cd "c:\Users\VISHNU V\Downloads\Study-Adda-main (1)\Study-Adda-main"
firebase deploy --only hosting
```

Notes:
- `firebase deploy` will publish the files in the project root. `firebase.json` is configured to serve static files from the repository root and rewrite all routes to `index.html` for SPA behaviour.
- Make sure your Firestore/Firebase rules are configured in the Firebase Console to prevent unauthorized reads/writes.
