# Intendant Privacy Policy

Nov 8, 2026 · @Alex

Intendant shows no ads, uses no analytics or tracking, and never sells your data. It keeps what you add in your account, so you see the same inventory on every phone you sign in on.

This policy covers the Intendant app for Android, made by Aliaksandr Shumeika. It says what the app collects, why, who else handles it, and how to delete it.

## What the app collects

The app collects your sign-in details and the inventory you type into it, and nothing else.

| Data | Why | Where it's kept |
| --- | --- | --- |
| Your email address | To sign you in, and to send a password-reset email when you ask for one | Firebase Authentication |
| Your password | To sign you in. The app never stores it itself | Firebase Authentication |
| Your IP address and your phone's user agent when you sign up or sign in | To stop abuse of sign-up and sign-in | Firebase Authentication, for a few weeks |
| An account ID, a random code Firebase creates when you sign up | To keep your data apart from everyone else's | Firebase Authentication and Cloud Firestore |
| Your categories, boxes and items: their names, notes, barcodes, stock quantities and units, low-stock levels, expiry dates and reminder settings | To show your inventory and keep it the same on every phone you sign in on | Cloud Firestore, under your account |
| Your 10 most recent searches | To list them on the Search screen | Only on your phone |

The app doesn't collect your name, contacts, location, photos or files. It asks for no permissions apart from internet access.

When you scan a barcode, Google Play services opens the camera, not the app. The image is processed on your phone, and the app receives only the barcode's number.

## How your data is used

Your data is used only to run the app: to sign you in, save and sync your inventory, send the password-reset emails you ask for, and list your recent searches. It isn't used for advertising, profiling or anything else.

No one looks at your data, except to fix a problem you report or when the law requires it.

## Who your data is shared with

Your data goes to one company, Google, which runs the services the app is built on. Your data is never sold or shared with advertisers, data brokers or anyone else.

- **Google Firebase** (Firebase Authentication and Cloud Firestore) signs you in and stores your inventory. Google handles this data on the app's behalf, as a data processor, under the [Firebase Data Processing and Security Terms](https://firebase.google.com/terms/data-processing-terms). [Firebase's privacy page](https://firebase.google.com/support/privacy) says more.
- **Google Play services** runs the [barcode scanner](https://developers.google.com/ml-kit/vision/barcode-scanning/code-scanner). It processes the camera image on your phone, and Google doesn't store the image or the result.

Your data would be disclosed to anyone else only if the law required it.

A backup you export is saved where you choose, and the app doesn't send it anywhere. If Android backup is on for your Google account, Android may also back up the app's data on your phone, such as your recent searches, under [Google's privacy policy](https://policies.google.com/privacy).

## Storage, security and how long data is kept

Your data travels encrypted over HTTPS, and Firebase encrypts it where it's stored. Firebase Authentication runs only in US data centres, and Cloud Firestore keeps your inventory on Google's servers, which may be outside your country.

Your data is kept until you delete it. An item, box or category you delete leaves Cloud Firestore straight away. When you delete your account, Firebase removes your sign-in details from its live and backup systems within 180 days.

## Your choices and rights

You can see, change, export and delete all your data yourself, in the app.

- **See and change it.** Everything the app keeps about your inventory is on its screens, where you can edit or delete it at any time.
- **Export it.** Account → Export a backup saves all your categories, boxes and items as a JSON file, wherever you choose.
- **Delete your account in the app.** Account → Delete account deletes your account and all its categories, boxes and items, straight away and for good. Your recent searches stay on your phone until you uninstall the app or clear its storage.
- **Delete your account without the app.** Email IntendantApp@shumeika.dev from your account's email address and ask for it to be deleted. Your account and all its data will be deleted within 30 days, and you'll get a reply to confirm.

Wherever you live, you can also ask what data is held about you, or object to how it's used, at IntendantApp@shumeika.dev. If you're in the EU or the UK, you can complain to your data protection authority.

## Children

Intendant isn't meant for children under 13, and it doesn't knowingly collect data from them. If you think a child has made an account, email IntendantApp@shumeika.dev and it will be deleted.

## Changes to this policy

When this policy changes, the date at the top changes with it.

## Contact

For any question about this policy or your data, email Aliaksandr Shumeika at IntendantApp@shumeika.dev.
