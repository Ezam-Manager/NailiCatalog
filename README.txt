
NailiCatalog - Firebase Product Catalog

1. Open Firebase Console: https://console.firebase.google.com
2. Create a project and enable Firestore + Storage + Hosting
3. Replace firebaseConfig in both admin.html and index.html with your Firebase project config
   (Project Settings > Your apps > Web > SDK Setup and Configuration)
4. Deploy with Firebase Hosting:

   - Install Firebase CLI (only once):
     npm install -g firebase-tools
     firebase login

   - In your project folder:
     firebase init hosting
     firebase deploy

Now share your link to users!
