# Tarun Delivery Manager — Android project v2.0

## New in v2.0
- Multiple screenshot selection with on-device ML Kit OCR.
- Basic address candidate extraction and locality tagging for Nallakunta, Ramnagar and Musheerabad.
- Local persistence: parcel list, starting hub and daily target survive app restarts.
- Manual parcel entry and area selection.
- Pending / Delivered / Failed filters and status changes.
- Share/export parcel list as text.
- Open a suggested multi-stop driving route in Google Maps (up to 9 stops per launch).

## Important accuracy and privacy notes
OCR is best-effort and can merge or split address lines incorrectly. Review every candidate and edit/remove incorrect entries before delivery. Locality detection only recognizes the listed area names; other addresses are marked for review.
The route is a suggested stop order, not a live traffic-optimized route. Google Maps may reorder or interpret addresses differently. Verify all stops in the official delivery workflow.
This app is independent and does not connect to Flipkart or mark orders delivered in Flipkart.
The parcel list is stored locally in Android SharedPreferences. Avoid sharing screenshots containing unnecessary customer personal data.

## Build APK
1. Install Android Studio on a computer.
2. Extract this ZIP and open the `TarunDeliveryManager_v2` folder.
3. Allow Gradle sync and install the SDK components Android Studio requests.
4. Connect your Android phone with USB debugging enabled, or select an emulator.
5. Choose **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. Use Android Studio's notification to locate the APK, then transfer and install it on your phone.

Version: 2.0 (versionCode 2)
Application ID: com.tarun.deliverymanager
Minimum Android: Android 6.0 (API 23)
