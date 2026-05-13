Fee Approval Android app build guide
====================================

This is an Android Studio project for the CEO approval app.

App name: Fee Approval
Package: com.athena.feeapproval
Portal API: https://www.fees.athenaop.com/
Firebase: google-services.json is already included in app/google-services.json.

Build APK:
1. Install Android Studio on a Windows PC.
2. Open this folder: FeeApprovalApp
3. Let Android Studio finish Gradle sync.
4. Go to Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Android Studio will create an APK under app/build/outputs/apk/debug/.
6. Install the APK on your Android test phone.

Before testing:
1. Upload all PHP API files from the V33 Mobile API ZIP to the portal root folder.
2. Upload Firebase service account JSON as:
   data/firebase-service-account.json
3. Login to the app using an admin/approver account.
4. The app will register the phone for push notifications.

CEO usage:
- Install APK.
- Login once.
- He sees pending approvals.
- Tap an item to Approve or Reject.
